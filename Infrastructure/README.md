
# INFRASTRUCTURE

## Overview

This project is associated with building the Infrastructure components for the SAP Replatform Pilot onto Azure

## Contents

The project contains the Azure ARM templates, Terradata and PowerShell scripts that have been used to create the 
Pilot environment.  These scripts have been used to build the components in the Capgemini Tenant.

ARM templates are written in .json format and edited in Visual studio.

The Main Contents is contained within

azuredeploy.json - The main files detailing the resources
azurrdeploy.parameters.json - The parameters file

# General Deploy Links

This template will deploy 2 new VMs (along with a new VNet, Storage Account and Load Balancer) and create a new  AD forest and domain, each VM will be created as a DC for the new domain and will be placed in an availability set. Each VM will also have an RDP endpoint added with a public load balanced IP address.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnikkh%2FSap30%2Fmaster%2Finfrastructure%2Fazuredeploy.json" target="_blank">
   Deploy VNet and Domain Controllers
</a>
<br>


# Links specifically for Nick

<a href="https://portal.azure.com/microsoft.onmicrosoft.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnikkh%2FSap30%2Fmaster%2Finfrastructure%2Fazuredeploy.json" target="_blank">
   Nick Deploy VNet and Domain Controllers
</a>
