# Creating a Virutal Machine using the Azure CLI 2.0
<h2 id="configure-your-environment">Configure Your Environment</h2>
<h3 id="install-xplat-cli">Install Azure CLI 2.0 Prerequisites</h3>
<ol style="list-style-type: decimal">
    <li><p>First, you must ensure that you have <a href="https://www.python.org/downloads/" target="_blank">Python 3.5</a> installed on your local machine.</p></li>
</ol>
<h4>Linux</h4>
<ol style="list-style-type: decimal">
    <li><p>If you are using a Linux distribution, you should install specific prerequisites listed as this link: <a href="https://docs.microsoft.com/en-us/cli/azure/install-azure-cli#linux-prerequisites" target="_blank">https://docs.microsoft.com/en-us/cli/azure/install-azure-cli</a>.</p></li>
</ol>
<h3 id="open-cli-and-configure-for-arm">Install Azure CLI 2.0</h3>
<ol style="list-style-type: decimal">
    <li><p>Open the command-line interface application for your operating system:</p>
        <ul>
            <li><p><strong>Windows:</strong> Command Prompt</p></li>
            <li><p><strong>Mac/Linux:</strong> Terminal</p></li>
        </ul>
        <p><strong>Note:</strong> Leave the application open for the remainder of this lab as you will be using it to manage your resources.</p>
    </li>
</ol>
<h4>Linux and OSX</h4>
<ol style="list-style-type: decimal">
    <li><p>Install the CLI using the following <code>curl</code> command:</p>
        <pre class="prettyprint sh"><code>curl -L https://aka.ms/InstallAzureCli | bash</code></pre>
    </li>
    <li><p>Restart your command-line interface application for the changes to take effect.</p></li>
</ol>
<h4>Windows</h4>
<ol style="list-style-type: decimal">
    <li><p>Install the CLI using the <code>pip</code> tool.</p>
        <pre class="prettyprint sh"><code>pip install --user azure-cli</code></pre>
    </li>
</ol>
<h3 id="validate-installation">Validate Installation</h3>
<ol style="list-style-type: decimal">
    <li>Use the following command to validate that the Azure CLI 2.0 tool is installed. You should see a description of potential commands:
        <pre class="prettyprint sh"><code>az --help</code></pre>
    </li>
</ol>
<h3 id="connect-to-your-azure-subscription">Connect to Your Azure Subscription</h3>
<ol style="list-style-type: decimal">
    <li>Use the <strong>interactive login</strong> to log in to Azure using your enterprise credentials or Microsoft account identity:
        <pre class="prettyprint sh"><code>az login</code></pre>
    </li>
    <li><p>Open a browser and navigate to <a href="https://aka.ms/devicelogin" class="uri">https://aka.ms/devicelogin</a>. The command prompt will display a device code that you can use to authenticate to Azure.</p></li>
    <li><p>Once you enter the code, you will be prompted to allow access to the <strong>Microsoft Azure CLI</strong>. Click <strong>Continue</strong>.</p></li>
    <li><p>Sign in using your identity associated with your Azure subscription.</p></li>
    <li><p>Once you receive confirmation that you are signed in, you can close your browser window.</p></li>
</ol>
<h2 id="create-your-network-resources">Create Your Network Resources</h2>
<h3 id="create-a-resource-group">Create a Resource Group</h3>
<ol style="list-style-type: decimal">
    <li>Use the following command to list all possible CLI options for <strong>Resource Groups</strong>:
        <pre class="prettyprint sh"><code>az group --help</code></pre>
    </li>
    <li><p>Use the following command to create a new resource group with the following details:</p>
        <ul>
            <li><p><strong>Name:</strong> CLITestGroup</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az group create –-name "CLITestGroup" –-location "West US"</code></pre>
    </li>
    <li><p>Use the following command to show the details of your resource group:</p>
        <ul>
            <li><strong>Name:</strong> CLITestGroup</li>
        </ul>
        <pre class="prettyprint sh"><code>az group show --name "CLITestGroup"</code></pre>
    </li>
</ol>
<h3 id="create-a-virtual-network">Create a Virtual Network</h3>
<ol style="list-style-type: decimal">
    <li><p>Use the following command to list all possible CLI options for network components in Azure:</p>
        <pre class="prettyprint sh"><code>az network --help</code></pre>
    </li>
    <li><p>Use the following command to list all possible CLI options for <strong>Virtual Networks</strong>:</p>
        <pre class="prettyprint sh"><code>az network vnet --help</code></pre>
    </li>
    <li><p>Use the following command to create a new resource group with the following details:</p>
        <ul>
            <li><p><strong>Name:</strong> TestVNET</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network vnet create –-resource-group "CLITestGroup" –-name "TestVNET" --location "West US"</code></pre>
    </li>
    <li><p>View your new virtual network in the list of virtual networks using this command:</p>
        <pre class="prettyprint sh"><code>az network vnet list</code></pre>
    </li>
    <li><p>View the details of your new virtual network using this command:</p>
        <ul>
            <li><p><strong>Name:</strong> TestVNET</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network vnet show –-resource-group "CLITestGroup" –-name "TestVNET"</code></pre>
        <p><strong>Note:</strong> Notice that some Virtual Network details (such as address prefix) were specified for you. This is because you did not specify any options when using your command. Default options were used.</p>
    </li>
</ol>
<h3 id="create-a-subnet">Create a Subnet</h3>
<ol style="list-style-type: decimal">
    <li><p>Use the following command to list all possible CLI options for Subnets:</p>
        <pre class="prettyprint sh"><code>az network vnet subnet --help</code></pre>
    </li>
    <li><p>Use the following command to create a subnet in your existing Virtual Network with the following options:</p>
        <ul>
            <li><p><strong>Name:</strong> TestSubnet</p></li>
            <li><p><strong>Address Prefix:</strong> 10.0.1.0/24</p></li>
            <li><p><strong>VNET Name:</strong> TestVNET</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network vnet subnet create --resource-group "CLITestGroup" --vnet-name "TestVNET" --name "TestSubnet" --address-prefix 10.0.1.0/24</code></pre>
    </li>
    <li><p>View the details of your new subnet using this command:</p>
        <ul>
            <li><p><strong>Name:</strong> TestSubnet</p></li>
            <li><p><strong>Address Prefix:</strong> 10.0.1.0/24</p></li>
            <li><p><strong>VNET Name:</strong> TestVNET</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network vnet subnet show --resource-group "CLITestGroup" --vnet-name "TestVNET" --name "TestSubnet"</code></pre>
    </li>
</ol>
<h3 id="create-a-public-ip-address">Create a Public IP Address</h3>
<ol style="list-style-type: decimal">
    <li><p>Use the following command to list all possible CLI options for <strong>Public IP Addresses</strong>:</p>
        <pre class="prettyprint sh"><code>az network public-ip --help</code></pre>
    </li>
    <li><p>Use the following command to create a new public IP address in your resource group with the following options:</p>
        <ul>
            <li><p><strong>Name:</strong> TestPIP</p></li>
            <li><p><strong>Allocation Method:</strong> Dynamic</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network public-ip create --resource-group "CLITestGroup" --name "TestPIP" --location "West US" –-allocation-method "Dynamic"</code></pre>
    </li>
    <li><p>Update the public IP address by giving it a unique <strong>domain name label</strong>. This name must be globally unique in Azure, only consist of alphabetic characters, and is recommended to be at-least 8 characters:</p>
        <p><strong>Note:</strong> This label will be used to construct the url for yoru virtual machine. For example, if you label is <strong>demexample</strong> and your resources are located in the <strong>West US</strong> region, then your domain will be <strong>demoexample.westus.cloudapp.azure.com</strong>.</p>
        <ul>
            <li><p><strong>Name:</strong> TestPIP</p></li>
            <li><p><strong>Domain Name Label:</strong> [Your unique name here]</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network public-ip update --resource-group "CLITestGroup" --name "TestPIP" --dns-name "demoexample"</code></pre>
        <p><strong>Note:</strong> if you label is not unique or otherwise not valid, you will receive a message that your request has failed when you try to set the domain name. Simply try again with another domain name label.</p>
    </li>
    <li><p>View the details of your new public IP address using this command:</p>
        <ul>
            <li><p><strong>Name:</strong> TestPIP</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network public-ip show --resource-group "CLITestGroup" --name "TestPIP"</code></pre>
    </li>
</ol>
<h3 id="create-a-network-interface-card">Create a Network Interface Card</h3>
<ol style="list-style-type: decimal">
    <li><p>Use the following command to list all possible CLI options for <strong>Network Interface Cards</strong>:</p>
        <pre class="prettyprint sh"><code>az network nic --help</code></pre>
    </li>
    <li><p>Use the following command to create a Network Interface Card in your resource group with the following options:</p>
        <ul>
            <li><p><strong>Name:</strong> TestNIC</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Public IP Address Name:</strong> TestPIP</p></li>
            <li><p><strong>Subnet Name:</strong> TestSubnet</p></li>
            <li><p><strong>VNET Name:</strong> TestVNET</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network nic create --resource-group "CLITestGroup" --location "West US" --name "TestNIC" --subnet "TestSubnet" --vnet-name "TestVNET" --public-ip-address "TestPIP"</code></pre>
    </li>
    <li><p>View the details of your new network interface cards using this command:</p>
        <ul>
            <li><p><strong>Name:</strong> TestNIC</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network nic show –-resource-group "CLITestGroup" –-name "TestNIC"</code></pre>
    </li>
</ol>
<h2 id="create-a-virtual-machine">Create a Virtual Machine</h2>
<h3 id="list-windows-server-images">List Windows Server Images</h3>
<ol style="list-style-type: decimal">
    <li><p>Use the following command to list all possible CLI options for <strong>images</strong>:</p>
        <pre class="prettyprint sh"><code>az vm image --help</code></pre>
    </li>
    <li><p>Use the following command to list all image <strong>publishers</strong> that match the following options:</p>
        <ul>
            <li><strong>Location:</strong> West US</li>
        </ul>
        <pre class="prettyprint sh"><code>az vm image list-publishers --location "West US"</code></pre>
    </li>
    <li><p>Use the following command to list all image <strong>offers</strong> that match the following options:</p>
        <ul>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Publisher:</strong> MicrosoftWindowsServer</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az vm image list-offers --location "West US" --publisher "MicrosoftWindowsServer"</code></pre>
    </li>
    <li><p>Use the following command to list all image <strong>skus</strong> that match the following options:</p>
        <ul>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Publisher:</strong> MicrosoftWindowsServer</p></li>
            <li><p><strong>Offer:</strong> WindowsServer</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az vm image list-skus --location "West US" --publisher "MicrosoftWindowsServer" --offer "WindowsServer"</code></pre>
    </li>
    <li><p>Use the following command to list all images that match the following options:</p>
        <ul>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Publisher:</strong> MicrosoftWindowsServer</p></li>
            <li><p><strong>Offer:</strong> WindowsServer</p></li>
            <li><p><strong>SKU:</strong> 2016-Datacenter</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az vm image list --location "West US" --publisher "MicrosoftWindowsServer" --offer "WindowsServer" --sku "2016-Datacenter" --all</code></pre>
        <p><strong>Note:</strong> In the future, you can use these set of commands to look up the Image URNs for many different operating systems available for Azure Virtual Machines.</p>
    </li>
<h3 id="create-a-virtual-machine-from-image">Create A Virtual Machine from Image</h3>
<ol style="list-style-type: decimal">
    <li><p>Use the following command to list all possible CLI options for <strong>Virtual Machine</strong>:</p>
        <pre class="prettyprint sh"><code>az vm --help</code></pre>
    </li>
    <li><p>Use the following command to list all possible CLI options for creating a <strong>Virtual Machine</strong>:</p>
        <pre class="prettyprint sh"><code>az vm create --help</code></pre>
    </li>
    <li><p>Use the following command to create a virtual machine with the following options:</p>
        <ul>
            <li><p><strong>Name:</strong> TestVM</p></li>
            <li><p><strong>Network Interface Card Name:</strong> TestNIC</p></li>
            <li><p><strong>OS Type:</strong> Windows</p></li>
            <li><p><strong>Image URN:</strong> MicrosoftWindowsServer:WindowsServer:2016-Datacenter:2016.0.20170127</p></li>
            <li><p><strong>Admin Username:</strong> Attendee</p></li>
            <li><p><strong>Admin Password:</strong> #1AzurePro$</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az vm create --resource-group "CLITestGroup" --name "TestVM" --location "West US" --nics "TestNIC" --image MicrosoftWindowsServer:WindowsServer:2016-Datacenter:2016.0.20170127 --admin-username "Attendee" --admin-password "#1AzurePro$"</code></pre>
        <p><strong>Note:</strong> It can take anywhere from five to fifteen minutes for your virtual machine to be created and ready for use.</p>
    </li>
    <li><p>View the details of your new Virtual Machine using this command:</p>
        <ul>
            <li><p><strong>Name:</strong> TestVM</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az vm show --resource-group "CLITestGroup" --name "TestVM"</code></pre>
    </li>
</ol>
<h3 id="optional-connect-to-your-virtual-machine"><em>(OPTIONAL)</em> Connect to your Virtual Machine</h3>
<ol style="list-style-type: decimal">
    <li><p>If you do not have it already installed, Install a Remote Desktop Connection client to your local machine:</p>
        <ul>
            <li><p><strong>Windows:</strong> The software should be pre-installed if you have Windows 7, 8, 8.1 or 10</p></li>
            <li><p><strong>Mac:</strong> https://itunes.apple.com/us/app/microsoft-remote-desktop/id715768417?mt=12</p></li>
            <li><p><strong>Linux:</strong> There are a variety of RDP client applications available depending on your distro.</p></li>
        </ul>
    </li>
    <li><p>In the command line interface, use the following command to view details of your public IP address:</p>
        <ul>
            <li><p><strong>Name:</strong> TestPIP</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network public-ip show --resource-group "CLITestGroup" --name "TestPIP"</code></pre>
    </li>
  	<li><p>Observe the value of the <code>dnsSettings.fqdn</code> property. While we could record this manually, we will instead use a query in the next step to get this value.</p></li>
    <li><p>In the command line interface, use the following command to view details of your public IP address:</p>
        <ul>
            <li><p><strong>Name:</strong> TestPIP</p></li>
            <li><p><strong>Location:</strong> West US</p></li>
            <li><p><strong>Group Name:</strong> CLITestGroup</p></li>
        </ul>
        <pre class="prettyprint sh"><code>az network public-ip show --resource-group "CLITestGroup" --name "TestPIP" --query dnsSettings.fqdn</code></pre>
    </li>
    <li><p>Observe and record the results of this query. The result is the url for the virtual machine.</p></li>
    <li><p>Open the Remote Desktop Connection software on your local machine.</p></li>
    <li><p>For the remote computer name, use the url recorded in the previous steps.</p></li>
    <li><p>For the username and password, use the following values:</p>
        <ul>
            <li><p><strong>Username:</strong> Attendee</p></li>
            <li><p><strong>Password:</strong> #1AzurePro$</p></li>
        </ul>
        <p><strong>Note:</strong> In Windows, you may need to add a leading backslash before typing the username so that it doesn't use your current machine's domain. For example, you would type <code>\Attendee</code> in the <em>User name</em> prompt.</p>
    </li>
    <li><p>Connect to the virtual machine and validate that it is working correctly.</p></li>
    <li><p>Close the Remote Desktop Connection software.</p></li>
    <li><p>Return to the command line interface.</p></li>
</ol>
<h2 id="clean-up-your-environment">Clean Up Your Environment</h2>
<h3 id="remove-resources">Remove Resources</h3>
<ol style="list-style-type: decimal">
    <li><p>Remove the <strong>CLITestGroup</strong> resource group using the following command:</p>
        <pre class="prettyprint"><code>az group delete –-name "CLITestGroup"</code></pre>
    </li>
    <li><p>When prompted, type <strong>y</strong> and then press <strong>Enter</strong> or <strong>Return</strong> to confirm the delete action.</p>
		<p><strong>Note:</strong> Alternatively, you could have used the <code>--yes</code> parameter to skip this prompt.</p>
  	</li>
    <li><p>Close the command line interface application.</p></li>
</ol>
<script src="https://cdn.rawgit.com/google/code-prettify/master/loader/run_prettify.js"></script>
