# Scaleable SYSLOG CEF Collection using VMSS
author: Nicholas DiCola

Sample is an ARM template that will deploy a Linux (RedHat or Ubuntu) Virtual Machine Scale Set.

The ARM template will deploy everything needed:
* Virtual Machine Scale
* Autoscale settings
* Storage Account
* Network Security Group
* Virtual Network
* Subnet
* Public IP Address
* Load Balancer

The ARM template includes the cloud init files which runs commands on the VM instance when it is deployed.


## Deploy Ubuntu VMSS
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjpbruckler%2Fdataconnectors%2Fmain%2FFCEF-VMSS%2FCEF-VMSS-UB-Templatev2.json)

