# Challenge 1-1: Setup a Bot using Bot Framework and Azure Bot Service

## Prerequisites

Complete Challenge #0, for setting up your environment.

## Description

Your mission for this challenge is to **setup** all required moving parts in order to have a Bot with a Teams Channel.

## Setting the context

This challenge is more a ***tutorial*** than a ***challenge***. There are easier and faster approaches to accomplishing the desired outcome, however these approaches hide the actual complexity of all needed moving parts, and while they accelerate the ***getting started***, they can set obstacles while moving towards ***production***. So, the idea is to setup everything manually in order to get a ***working knowledge*** of all needed parts and how they work together.

## Getting Started

1. Login in to your Azure Subscription
2. [Start by creating an Azure Application Registration](https://docs.microsoft.com/en-us/azure/active-directory/develop/quickstart-register-app)
    1. Make sure you select a Multi-tenant version.
    2. Keep the Application (Client) ID to use in the next step![Application (Client) ID](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/AppRegistrationClientID.jpg)
    3. [Make sure you create a client secret to use in the next step](https://docs.microsoft.com/en-us/azure/active-directory/develop/quickstart-register-app#add-credentials)
3. [Next create an Azure Bot](https://docs.microsoft.com/en-us/azure/bot-service/abs-quickstart?view=azure-bot-service-4.0&tabs=userassigned)
    1. Make sure you setup manually the Application Registration ID and Secret from the previous step. ![Azure Bot Config](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/AzureBotConfig.jpg)
4. Configure your Azure Bot
    1. To use a custom icon, via Bot Profile. [You can use this icon](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/custom-bot-framework-icon.png)
    2. To have a Teams Channel, via Channels.
5. [Next using Teams Development Portal, create a new App](https://dev.teams.microsoft.com/apps)
    1. Configure the Basic Information and make sure you set the Web Site Url, Privacy Policy and Terms of Use.
    2. Add a new Bot Feature from the App Features selection, and configure it by setting the bot ID manually. The bot ID is the same as the Azure AD Application Registration ID.
     ![bot id](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/TeamsPortalBotConfig.jpg)
     ![bot id config](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/TeamsPortalBotConfig_2.jpg)
    3. Select a Personal Scope
    4. Select ***Preview in Teams*** to add your Bot to Teams.
    ![Teams 0](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/TeamsAdd_0.jpg)
    ![Teams 1](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/TeamsAdd_1.jpg)
    ![Teams 2](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/TeamsAdd_2.jpg)

## Success Criteria

1. Make sure you are able to answer the below questions to your coach:
    1. What is an App Registration and why is it needed when running a Bot?
    2. What is an Azure Bot and why is it needed when running a Bot?
    3. How is your Bot packaged within the Teams Application?
    4. Where will be the actual Bot hosted?
    5. Can you migrate your Bot to another Azure AD tenant?

## Learning Resources

1. [Build an enterprise-grade conversational bot](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/conversational-bot)
2. [Manage your apps with the Developer Portal for Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/teams-developer-portal)
3. [Register a bot with Azure](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-quickstart-registration?view=azure-bot-service-4.0&tabs=userassigned)
4. [Bots in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots)
5. [Bots and SDKs](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-features?tabs=dotnet#bots-with-the-microsoft-bot-framework)
