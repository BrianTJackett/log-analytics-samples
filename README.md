# log-analytics-samples

Sample KQL queries for Azure Log Analytics against Office 365 audit logs and Azure AD Audit or Sign-in logs.

## Getting started with Azure Log Analytics / Azure Sentinel

- [Azure Sentinel - Quick start](https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard)
- [Azure Sentinel - Connect to O365 data](https://docs.microsoft.com/en-us/azure/sentinel/connect-office-365)

## KQL queries

- [Office 365 usage](./Queries/Office365Usage.kql)
- [OneDrive user uploads](./Queries/OneDriveUserUploads.kql)
- [Azure AD group creation](./Queries/AzureADGroupCreation.kql)
- [Office 365 group creation initiated by](./Queries/Office365GroupCreationInitiatedBy.kql)
- [SharePoint Online Site Creation](./Queries/SPOSiteCreation.kql)
- [SharePoint Online Sharing Content](./Queries/SPOSharing.kql)
- [Users uploading Git repos](./Queries/UsersUploadGitRepo.kql)

**Note** Recommend installing [Azure Log Analytics / Kusto Syntax Highlighting extension](
https://marketplace.visualstudio.com/items?itemName=josin.kusto-syntax-highlighting) for Visual Studio Code to easily view KQL queries.

### Resources

[Kusto Query Language overview](https://docs.microsoft.com/en-us/azure/kusto/query/)

## Disclaimer

Microsoft provides programming examples for illustration only, without warranty either expressed or implied, including, but not limited to, the implied warranties of merchantability and/or fitness for a particular purpose. We grant You a nonexclusive, royalty-free right to use and modify the Sample Code and to reproduce and distribute the object code form of the Sample Code, provided that You agree: (i) to not use Our name, logo, or trademarks to market Your software product in which the Sample Code is embedded; (ii) to include a valid copyright notice on Your software product in which the Sample Code is embedded; and (iii) to indemnify, hold harmless, and defend Us and Our suppliers from and against any claims or lawsuits, including attorneys' fees, that arise or result from the use or distribution of the Sample Code.