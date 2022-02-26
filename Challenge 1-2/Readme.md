# Challenge 1: Create a personal (1-1) Bot within Teams

## Prerequisites

Complete Challenge #1-1, for setting up a Teams app.

## Description

Your mission for this challenge is to **create** and **deploy** a Bot that can operate within Teams, and can have an 1-1 interaction with a Teams user. The Bot should only work on a "personal" context.
The Bot should have two commands:

1. Create Support Ticket.
    1. The user should be able to write as free text his/hers support ticket request, the Bot should reply back that it received the ticket and also write back to original text. At this stage the Bot does **not** need to "persist" the new ticket request.
2. Help command.
    1. The Bot should reply back with all available commands, in this case just Create Support Ticket.
3. The Bot should show the above commands as ***suggestions*** before the user actually types anything.
![Commands Popup](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/HelpPopUp.jpg)

## Getting Started

1. Use the ***Conversation bot*** sample on **Learning Resources** in order to start with the coding part of your bot.
    1. Make sure that the sample builds and runs locally
    2. Expose your local environment publicly by using ngrok
    3. Configure your Azure Bot Service to consume your local exposed end point.
2. Add your Bot to Teams and start an 1-1 dialog.
3. Tweak the code as needed in order to implement the required features.
4. Deploy your Bot to Azure, on an App Service, and re-configure the Azure Bot Service accordingly.

## Success Criteria

1. Demonstrate to your coach a Bot that can have an 1-1 conversation with a user, with the above 2 commands and the ***suggestions*** functionality; and also that the Bot cannot be added on a Teams or Group chat.
2. Demonstrate to your coach that the Bot is deployed on an Azure Service.

## Learning Resources

1. [Bots in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots)
2. [Bots and SDKs](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-features?tabs=dotnet#bots-with-the-microsoft-bot-framework)
3. [Bot activity handlers](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-basics?tabs=csharp)
4. [How Microsoft Teams bots work](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-basics-teams?view=azure-bot-service-4.0&tabs=csharp)
5. Deploy to Azure App Service
    1. [Publish an ASP.NET Core app to Azure with Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs?view=aspnetcore-6.0)
    2. [Deploy to Azure App Service using Visual Studio Code](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/deploy-to-azure-vscode?view=azure-devops)
    3. [Deploy your bot in Azure](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-deploy-az-cli?view=azure-bot-service-4.0&tabs=csharp%2Cuserassigned)
6. Code Samples:
    1. Teams Conversation bot: [C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/57.teams-conversation-bot), [JavaScript / Node.js] (https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/57.teams-conversation-bot), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/57.teams-conversation-bot), [Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/57.teams-conversation-bot)
