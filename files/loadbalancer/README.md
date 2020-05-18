# Deployment of 3 Windows VMs 1vNET

This template allows you to deploy 3 VMs called myVM1 myVM2 myVM3, they are linked to a custom VM extention that will deploy IIS and a test page to each vm

The vms are all attached to the same vNET

This is in preperation for the load balancing lab

The NSG has port 80 opened


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkramit%2FAZ300%2D	Notes%2Fmaster%2Ffiles%2Floadbalancer%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>