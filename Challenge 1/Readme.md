# Challenge 1: Create a personal (1-1) Bot within Teams

## Prerequisites

Complete Challenge #0, for setting up a Teams app.

## Description

Your mission for this challenge is to **create** and **deploy** a Bot that can operate within Teams, and can have an 1-1 interaction with a Teams user. The Bot should only work on a "personal" context.
The Bot should have two commands:

1. Create Support Ticket.
    1. The user should be able to write as free text his/hers support ticket request, the Bot should reply back that it received the ticket and also write back to original text. At this stage the Bot does **not** need to "persist" the new ticket request.
2. Help command.
    1. The Bot should reply back with all available commands, in this case just Create Support Ticket.

## Success Criteria

1. Demonstrate to your coach a Bot that can have an 1-1 conversation with a user, with the above 2 commands; and also that the Bot cannot be added on a Teams or Group chat.
2. Demonstrate to your coach that the Bot is deployed on an Azure Service.

## Learning Resources

1. [Bots in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots)
2. [Bots and SDKs](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-features?tabs=dotnet#bots-with-the-microsoft-bot-framework)
3. [Bot activity handlers](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/bot-basics?tabs=csharp)
4. [Deploy your bot in Azure](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-deploy-az-cli?view=azure-bot-service-4.0&tabs=csharp%2Cuserassigned)
5. Code Samples 
    1. [Echo Bot in C#](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/csharp_dotnetcore/02.echo-bot),
    2. [Echo Bot in JavaScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/javascript_nodejs/02.echo-bot),
    3. [Echo Bot in TypeScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/typescript_nodejs/02.echo-bot),
    4. [Echo Bot in Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/02.echo-bot),
    5. [Echo Bot in Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/02.echo-bot)
