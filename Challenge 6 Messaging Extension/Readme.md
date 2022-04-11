# Challenge 6: Create a Messaging extension.

Messaging extensions allow the users to interact with your web service through buttons and forms in the Microsoft Teams client. They can search or initiate actions in an external system from the compose message area, the command box, or directly from a message. You can send back the results of that interaction to the Microsoft Teams client in the form of a richly formatted card. This document gives an overview of the messaging extension, tasks performed under different scenarios, working of messaging extension, action and search commands, and link unfurling.
There are two types of messaging extension commands, action command and search command.
<br/><br/>
**Search commands** allow the users to search an external system for information either manually through a search box, or by pasting a link to a monitored domain into the compose message area, and insert the results of the search into a message. In the most basic search command flow, the initial invoke message includes the search string that the user submitted. 
![Messaging extension: search commands](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/me1.png)
![Messaging extension: search commands](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/me2.png)

<br/><br/>
**Action commands** are used to present the users with a modal popup to collect or display information. When the user submits the form, your web service responds by inserting a message into the conversation directly or by inserting a message into the compose message area. After that the user can submit the message. You can chain multiple forms together for more complex workflows.
![Messaging extension: action commands](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/me3.png)

## Prerequisites

You should have an 1-1 Bot already setup. 

## Description

Your mission for this challenge is to **deploy** the messaging extension from GitHub Repository
1. Download samples app from GitHub: 
<br/> 1) Messaging extensions - Search command ([C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/50.teams-messaging-extensions-search),	[JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/50.teams-messaging-extensions-search),	[Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/50.teams-messaging-extensions-search),	[Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/50.teams-messaging-extensions-search).) 
<br/> 2) Messaging extensions - Action command ([C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/51.teams-messaging-extensions-action),	[JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/51.teams-messaging-extensions-action),	[Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/51.teams-messaging-extensions-action),	[Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/51.teams-messaging-extensions-action).)
2. Publish your application to Azure App Service or run it locally using the [tutorial](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/debug).
3. Open "Developer Portal" (app or website) and open your application.
4. Add messaging extention to your application and change the app version.
5. Press "Submit new version".
6. Go to Admin Center to approve published application.
7. Go to Teams Store (bottom of your Teams) and install the updated version of the app.


## Success Criteria

1. Demonstrate to your coach that you successfully deployed messaging extentions. You can deploy both messaging extentions separatelly or add the code from one sample to another and deploy one app with both messaging extentions.

## Learning Resources

1. [Messaging extensions](https://docs.microsoft.com/en-us/microsoftteams/platform/messaging-extensions/what-are-messaging-extensions)
2. [Search commands](https://docs.microsoft.com/en-us/microsoftteams/platform/messaging-extensions/how-to/search-commands/define-search-command)
3. [Action commands](https://docs.microsoft.com/en-us/microsoftteams/platform/messaging-extensions/how-to/action-commands/define-action-command)
4. Code Samples
    1. Messaging extensions - search command: in [C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/50.teams-messaging-extensions-search),	[JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/50.teams-messaging-extensions-search),	[Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/50.teams-messaging-extensions-search),	[Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/50.teams-messaging-extensions-search).
    2. Messaging extensions - action command: in [C#](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/csharp_dotnetcore/51.teams-messaging-extensions-action),	[JavaScript](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/javascript_nodejs/51.teams-messaging-extensions-action),	[Python](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/python/51.teams-messaging-extensions-action),	[Java](https://github.com/microsoft/BotBuilder-Samples/blob/main/samples/java_springboot/51.teams-messaging-extensions-action).
