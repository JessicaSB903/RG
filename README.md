# RG
# azure-resource-group-creation
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Azure Logo"/>
</p>

<h1>Creating and Deploying Resource Groups in Microsoft Azure</h1>
This tutorial outlines the process of creating and deploying Resource Groups within Microsoft Azure using automated scripts and the Azure portal.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How to Create and Deploy Resource Groups in Azure](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource Manager)
- Azure Portal
- Azure CLI / PowerShell
- Resource Groups
- Infrastructure as Code

<h2>Operating Systems Used</h2>

- Windows 10 / 11
- Windows Server 2022 (for PowerShell-based scripting, if applicable)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Log into the Azure Portal
- Step 2: Create a new Resource Group via the Portal or CLI
- Step 3: Validate Resource Group settings (location, naming convention, tags)
- Step 4: Automate deployment using script (optional)

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Azure Resource Group Creation"/>
</p>
<p>
Begin by signing into the Azure Portal. Navigate to the “Resource groups” section and select “Create”. Enter the required details such as subscription, region, and a unique resource group name. Tags can be applied for better organization.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Azure CLI Resource Group Creation"/>
</p>
<p>
Alternatively, use the Azure CLI or PowerShell to create a resource group. For example:
<br /><br />
<code>az group create --name MyResourceGroup --location eastus</code><br />
or<br />
<code>New-AzResourceGroup -Name "MyResourceGroup" -Location "East US"</code><br /><br />
This allows for easy automation and repeatable deployments across environments.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Azure Tags and Management"/>
</p>
<p>
After creation, resource groups can be managed using Azure policies, role-based access control, and tagging structures to ensure proper cost management and compliance. This setup provides a foundational structure for deploying additional Azure services efficiently.
</p>
<br />
