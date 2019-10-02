# log-analytics-samples
Sample KQL queries for Azure Log Analytics against Office 365 audit logs.

### Getting started with Azure Log Analytics / Azure Sentinel
- [Azure Sentinel - Quick start](https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard)
- [Azure Sentinel - Connect to O365 data](https://docs.microsoft.com/en-us/azure/sentinel/connect-office-365)

### KQL queries
- [Office 365 usage](.\Queries\Office365Usage.kql)
- OneDrive usage
- [OneDrive user uploads](.\Queries\OneDriveUserUploads.kql)
- SharePoint usage
- [Azure AD group creation](.\Queries\AzureADGroupCreation.kql)
- [Office 365 group creation initiated by](.\Queries\Office365GroupCreationInitiatedBy.kql)
- [Users uploading Git repos](.\Queries\UsersUploadGitRepo.kql)

**Note** Recommend installing [Azure Log Analytics / Kusto Syntax Highlighting extension](
https://marketplace.visualstudio.com/items?itemName=josin.kusto-syntax-highlighting) for Visual Studio Code to easily view KQL queries.