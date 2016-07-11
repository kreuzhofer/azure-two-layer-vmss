# azure-vmss-docker
An ARM template to deploy a two layer linux environment with two virtual machine scalesets and a jumphost
The public ip and vnet deployment has been seperated out into the sharedresources project to have a static ip in another resource group that will not change even if you redeploy the vm environments
