# Challenge 5: Create a Teams Channel Bot

## Prerequisites

You should have an 1-1 Bot already setup.

## Description

Your mission for this challenge is to **extend** the Bot you created in the previous challenge, in order to have the following features:

1. The Bot should now have the functionality to be added on a Teams Channel.
2. The Bot should send a "Welcome message" when a user is added to the Teams Channel.
3. The Bot should have the below commands:
    1. **Support Tickets List**, that will return a "static list" as plain text. There is a predefined list that you can use [here](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Challenge%202/Resources/SupportTickets.csv).
    2. **Support Tickets Card**, that will return the same list but using a ["Card Type"](https://docs.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/cards-reference) that is supported by Teams.

## Success Criteria

1. Demonstrate to your coach that when you add a new user to the Teams Channel the Bot sends a "Welcome Message".
2. Demonstrate to your coach that the Bot has 2 commands on the "Team Channel" context as listed above.

## Learning Resources

1. [Types of Cards](https://docs.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/cards-reference)
2. [Send proactive messages](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/how-to/conversations/send-proactive-messages)
3. [Notifications to your message](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/how-to/conversations/conversation-messages?tabs=dotnet#notifications-to-your-message)
4. Code Samples
    1. Start new thread in a channel in [C#](https://github.com/microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/58.teams-start-new-thread-in-channel), [JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/master/samples/javascript_nodejs/58.teams-start-new-thread-in-channel), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/master/samples/python/58.teams-start-thread-in-channel).
    2. Welcome user in [C#](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/csharp_dotnetcore/03.welcome-user), [JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/03.welcome-users), [TypeScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/typescript_nodejs/03.welcome-users), [Python](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/python/03.welcome-user), [Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/03.welcome-user).
    3. Using Adaptive cards in [C#](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/csharp_dotnetcore/07.using-adaptive-cards), [JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/07.using-adaptive-cards), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/07.using-adaptive-cards),	[Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/07.using-adaptive-cards).
    4. Using cards in [C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/06.using-cards), [JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/06.using-cards), [TypeScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/typescript_nodejs/06.using-cards), [Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/06.using-cards), [Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/06.using-cards).
