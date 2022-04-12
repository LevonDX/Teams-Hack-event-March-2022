# Challenge 4: Create a Personal and Channel Bot

A bot is an app that runs simple and repetitive tasks by users such as customer service or support staff. Everyday use of bots include, bots that provide information about the weather, make dinner reservations, or provide travel information. Interactions with bots can be quick questions and answers or complex conversations.

## Description
Your mission for this challenge is to **deploy** a Bot that can operate within Teams, and can have an interaction with a Teams users. The Bot should work in a "personal" and "channel" context.

![Bot](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/img/bot.png)
![Commands Popup](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/HelpPopUp.jpg)

## Getting Started

1. Use the Teams Conversation bot code sample: [C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/57.teams-conversation-bot), [JavaScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/57.teams-conversation-bot), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/57.teams-conversation-bot), [Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/57.teams-conversation-bot).
2. Make sure that the sample builds and runs locally.
3. Expose your local environment publicly by using ngrok. Please use the [tutorial](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/debug)
4. Configure your Azure Bot Service to consume your local exposed endpoint.
5. Add your Bot to Teams and start an 1-1 dialog.
6. Deploy your Bot to Azure, on an App Service, and re-configure the Azure Bot Service accordingly.
7. Based on dialog with bot create [bot commands](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/how-to/create-a-bot-commands-menu?tabs=desktop%2Cdotnet) (You can do this as minimum for command "help". For defining other commands you can chek the code of the sample).
8. Add bot to current app package of create a new one. Make it work for 1-1 and in channel.
9. If you use existing app package, update the app version and perform steps to deploy the updated app package.

## Success Criteria

1. Demonstrate to your coach a Bot that can have an 1-1 conversation with a user and works in channel as well, with the above 2 commands with suggestion functionality (see the screenshot above).
2. Demonstrate to your coach that the Bot is deployed on an Azure Service or you run in locally.
3. Demonstrate to your coach that when you add a new user to the Teams Channel the Bot sends a "Welcome Message".

## Learning Resources

1. [Bots in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots) 
2. [Bots and SDKs](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-features?tabs=dotnet#bots-with-the-microsoft-bot-framework)
3. [Bot activity handlers](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-basics?tabs=csharp)
4. [How Microsoft Teams bots work](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-basics-teams?view=azure-bot-service-4.0&tabs=csharp)
5. [Have a conversation with a Microsoft Teams bot](https://docs.microsoft.com/en-us/microsoftteams/platform/resources/bot-v3/bot-conversations/bots-conversations)
6. Deploy to Azure App Service
    1. [Publish an ASP.NET Core app to Azure with Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs?view=aspnetcore-6.0)
    2. [Deploy to Azure App Service using Visual Studio Code](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/deploy-to-azure-vscode?view=azure-devops)
    3. [Deploy your bot in Azure](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-deploy-az-cli?view=azure-bot-service-4.0&tabs=csharp%2Cuserassigned)
7. Code Samples:
    1. Teams Conversation bot: [C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/57.teams-conversation-bot), [JavaScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/57.teams-conversation-bot), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/57.teams-conversation-bot), [Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/57.teams-conversation-bot)
    2. Start new thread in a channel in [C#](https://github.com/microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/58.teams-start-new-thread-in-channel), [JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/master/samples/javascript_nodejs/58.teams-start-new-thread-in-channel), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/master/samples/python/58.teams-start-thread-in-channel).
    3. Welcome user in [C#](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/csharp_dotnetcore/03.welcome-user), [JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/03.welcome-users), [TypeScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/typescript_nodejs/03.welcome-users), [Python](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/python/03.welcome-user), [Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/03.welcome-user).
