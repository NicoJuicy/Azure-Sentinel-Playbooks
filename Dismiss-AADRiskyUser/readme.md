# Confirm-AADRiskyUser
author: Nicholas DiCola

This playbook will set the Risky User property in AAD using Graph API using a Beta API.  NOTE:  You must create an app registration for graph api with appropriate permissions.  NOTE:  You will need to add the managed identity that is created by the logic app to the Security Administrator role in Azure AD.

<a href="https://azuredeploy.net/?repository=https://github.com/swiftsolves-msft/Azure-Sentinel-Playbooks/blob/master/Dismiss-AADRiskyUser" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSwiftsolves-MSFT%2FAzure-Sentinel-Playbooks%2Fmaster%2FDismiss-AADRiskyUser%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>