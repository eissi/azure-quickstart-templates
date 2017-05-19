

from azuredeploy.json to lgeid.json
-virtual network -publicip fqdn +lb 8080


### Deploy a VM Scale Set based on a Windows Custom Image ###

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2FMyAzureRGTemplate%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-vmss-windows-customimage%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Using the existing vnet
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Feissi%2Fazure-quickstart-templates%2Fmaster%2F201-vmss-windows-customimage%2Flgeid.json" target="_blank">
   <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

without PSH to create multiple VMSS with managed disk
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Feissi%2FMyAzureRGTemplate%2Fmaster%2FMyAzureRGTemplate%2FMyAzureRGTemplate%2FTemplates%2Fvmss-userimage.json" target="_blank">
<img src="http://azuredeploy.net/deploybutton.png"/>
</a>


https://raw.githubusercontent.com/eissi/MyAzureRGTemplate/master/MyAzureRGTemplate/Templates/vmss-userimage.json
https://raw.githubusercontent.com/eissi/MyAzureRGTemplate/master/MyAzureRGTemplate/MyAzureRGTemplate/Templates/vmss-userimage.json

Adding SSH, RDP, 8080
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Feissi%2Fazure-quickstart-templates%2Fmaster%2F201-vmss-windows-customimage%2Fwithoutvnet.json" target="_blank">
   <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
