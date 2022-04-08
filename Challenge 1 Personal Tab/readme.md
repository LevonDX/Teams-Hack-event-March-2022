# Build Tabs for Microsoft Teams: Personal tab

Tabs are Teams-aware webpages embedded in Microsoft Teams. They are simple HTML <iframe\> tags that point to domains declared in the app manifest and can be added as part of a channel inside a team, group chat, or personal app for an individual user. You can include custom tabs with your app to embed your own web content in Teams or add Teams-specific functionality to your web content.
<br/><br/>
There are two types of tabs available in Teams, **personal** and **channel or group**. Personal tabs, along with personally-scoped bots, are part of personal apps and are scoped to a single user. It this challange we are going to create a personal tab that will show list of support tickets. You can use prepopulated list of tickets from Challenge 2, or hardcode it in HTML, if you prefer.

The following image shows personal tab:<br/>
![Personal tab](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/personal_tab.png "Personal tab")
<br>

## Description

Your mission for this challenge is to **create** a personal tab for Teams that shows the list of submitted tickets.

## Getting Started

For step-by-step tutorial, how to create a custom Personal tab and add it to Teams, please follow  [Create Personal Tab](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/how-to/create-personal-tab?tabs=aspnetcore).


1. Download sample app from GitHub ["Personal tab quick-start"](https://github.com/OfficeDev/microsoft-teams-sample-tabs.git).
2. Publish your application to Azure App Service. If you do it from VS, [this tutorial](https://docs.microsoft.com/en-us/azure/app-service/quickstart-dotnetcore?tabs=net60&pivots=development-environment-vs#publish-your-web-app) may help.
4. Open "Developer Portal" (app or website) and open your application.
5. Add Personal Tab to your application and change the app version.
6. Press "Submit new version".
7. Go to Admin Center to approve published application.
8. Go to Teams Store (bottom of your Teams) and install the updated version of the app.

## Success Criteria
* Successfully publish the application in Azure App Service and run it in browser
* Successfully add your tab to Teams.
* Demonstrate to your coach a personal tab.



## Learning Resources
1. [Build Tabs for Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/what-are-tabs).
2. [Prerequisites](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/how-to/tab-requirements)
3. [Create a personal tab](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/how-to/create-personal-tab?tabs=nodejs).
4. Code samples:
    1. [Tabs samples](https://github.com/OfficeDev/Microsoft-Teams-Samples#tabs-samples).
