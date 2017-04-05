# Deploy ASP.NET MVC Application to a Virtual Machine Scale Set using WebDeploy and Visual Studio Team Services

The template above can deploy a WebDeploy package to a VMSS instance. It is used as part of a VSTS workflow.

You can enhance the workflow by doing the following:

- Delete artifacts after the build process using The Azure CLI 2.0: ``az storage blob delete --connection-string (az storage account show-connection-string -n vmssstorassets -g ASPNETtoVMSS --query connectionString) --container-name dynamic-deployment --name 20170405.2/Basic.Web.zip``.

- Update the tempalate to ``Manual`` deployment and use the instructions here (https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-upgrade-scale-set) to do a rolling update of Virtual Machine instances.
