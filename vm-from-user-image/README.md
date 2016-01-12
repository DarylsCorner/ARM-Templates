# Create a Virtual Machine from a User Image

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/DarylsCorner/ARM-Templates/blob/master/vm-from-user-image/azuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Prerequisite - The Storage Account should already exist and the custom user VHD image should be present in the storage account.

This template allows you to create a Virtual Machine from a custom user image. This template also deploys a Virtual Network, a Network Security Group attached to the Subnet, a Public IP address and a Network Interface. Three rules are created for the NSG to allow RDP, HTTP, and HTTPS access.

