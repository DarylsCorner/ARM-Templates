# Create a Virtual Machine from a User Image

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDarylsCorner%2FARM-Templates%2Fmaster%2Fvm-from-user-image%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Prerequisite - The Storage Account should already exist and the custom user VHD image should be present in the storage account.

This template allows you to create a Virtual Machine from a custom user image. This template also deploys a Virtual Network, a Network Security Group attached to the Subnet, a Public IP address and a Network Interface. Three rules are created for the NSG to allow RDP, HTTP, and HTTPS access.

