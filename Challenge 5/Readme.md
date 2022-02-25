# Challenge 5: Create Messaging extension.

## Prerequisites

Complete Challenge #1, you should have an 1-1 Bot already setup. Bot

## Description

Your mission for this challenge is to **create** the messaging extension.
Messaging extension should have the following functionality:

1. Suport engineer should be able to send an Adaptive card with detailed information about the incident to 1:1 chat/team's channel.
![Messaging extension: search action](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/img/me1.png)
2. (optional) Support engineer should be able to create a new incident from the user message.
3. The Bot should have the below commands:
    1. **Support Tickets List**, that will return a "static list" of open support tickets as plain text. There is a predefined list of tickets that you can use [here](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Challenge%202/Resources/SupportTickets.csv).
    2. **Support Tickets Card**, that will return the same list but using a ["Card Type"](https://docs.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/cards-reference) that is supported by Teams.

## Success Criteria

1. Demonstrate to your coach that when you add a new user to the Teams Channel the Bot sends a "Welcome Message".
2. Demonstrate to your coach that the Bot has 2 commands on the "Team Channel" context as listed above.

## Learning Resources

1. [Types of Cards](https://docs.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/cards-reference)
1. Code Samples
    1. [Welcome user in C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/03.welcome-user),
    2. [Welcome user in JavaScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/03.welcome-users),
    3. [Welcome user in TypeScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/typescript_nodejs/03.welcome-users),
    4. [Welcome user in Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/03.welcome-user),
    5. [Welcome user in Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/03.welcome-user)
    6. [Using cards in C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/06.using-cards),
    7. [Using cards in JavaScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/05.multi-turn-prompt),
    8. [Using cards in TypeScript / Node.js](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/typescript_nodejs/06.using-cards),
    9. [Using cards in Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/06.using-cards),
    10. [Using cards in Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/06.using-cardshttps://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/06.using-cardshttps://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/06.using-cards)
