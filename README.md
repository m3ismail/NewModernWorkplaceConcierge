:exclamation: Thank you for using the Modern Workplace Concierge and your support. This project is now maintained by Mostafa Ismail. Feel free to clone or deploy it to your own Azure tenant.
About

The Modern Workplace Concierge is a helper tool to simplify your daily work with Microsoft 365 services. It allows you to:

    Import and export Intune configuration and settings
    Import and export Conditional Access policies
    Document Conditional Access policies
    Deploy a Conditional Access baseline
    Download OSD-ready offline Autopilot profiles
    Re-download uploaded PowerShell scripts from Intune
    Import Trello boards to Microsoft Planner

The tool is built on ASP.NET and works with the Microsoft Graph Beta API.
Supported Entities

Supported configuration in imports and exports is documented in this project's wiki.
Consent and Permissions

To authenticate with the Microsoft Graph API, a multi-tenant Azure AD application performs authentication, and you will need to provide admin consent to the Azure AD application before using this tool.
Privacy

The app uses Azure Application Insights and traces performance markers what-does-application-insights-monitor. All data is processed in memory and is not stored persistently or used for further processing.
Host Your Own Instance

If you are not allowed or do not want to use the public instance of the Modern Workplace Concierge, you can deploy an instance in your Azure tenant & set up an app registration. Wiki documentation for Self-hosting a custom instance.

Deploy to Azure
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/m3ismail/ModernWorkplaceConcierge/main/azuredeploy.json" target="_blank"> <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true"/> </a>
