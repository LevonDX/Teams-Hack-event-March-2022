# Build Tabs for Microsoft Teams

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


1. Download [sample app from github](https://github.com/OfficeDev/microsoft-teams-sample-tabs.git) or create from scratch.
2. Change **"Personl Tab"** page to show list of submitted tickets.
3. Publish your application to Azure App Service.
4. Open **"Developer Portal"**(recommended) or "App Studio" and open your application.
5. Add Personal Tab to your application and change the app version.
6. Press **"Submit new version"**.
7. Go to Admin Center to approve published application.
8. Go to Teams Store (bottom of your Teams) and install the updated version of the app.

## Success Criteria
* Describe what are the main prerequisites to create Teams Tab
* Demonstrate to your coach a personal tab that shows the list of current incidents.



<br/>

# Authenticate a user in a Microsoft Teams tab (Optional)

There are many services that you may want to consume inside your Teams app, and most of those services require authentication and authorization to get access to the service. Services include Facebook, Twitter, and Teams. Teams user profile information is stored in Azure AD using Microsoft Graph and this article will focus on authentication using Azure AD to get access to this information.

Add authentication support to your Teams Tab:



## Learning Resources
1. 
