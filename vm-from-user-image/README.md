# Create a Virtual Machine from a User Image

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDarylsCorner%2FARM-Templates%2Fmaster%2Fvm-from-user-image%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Prerequisite - The Storage Account should already exist and the custom user VHD image should be present in the storage account that will host the virtual machine OSdisk.

This template allows you to create a Virtual Machine from a custom user image. Ensure that you are using a Sysprep generalized image. This template also deploys a Virtual Network with one subnet, a Network Security Group attached to the Subnet, a  static Public IP address and a Network Interface with a static private IP address. Three security rules are created for the NSG to allow inbound access for RDP, HTTP, and HTTPS.

