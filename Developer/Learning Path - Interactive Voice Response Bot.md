# Learning Path - Creating an Interactive Voice Response Bot

## Audience: Developer

## Type: Information

### Summary
Automated customer interaction is essential to a business of any size. In fact, [61%](https://www.talkdesk.com/blog/10-customer-services-statistics-for-call-center-supervisors/) of consumers prefer to communicate via speech, and most of them prefer self-service. Because customer satisfaction is a priority for all businesses, self-service is a critical facet of any customer-facing communications strategy.

In an era when mobile phones are dominant and keypads are not always readily accessible, interactive voice response (IVR) systems provide an intuitive, simple, and convenient method for customers to convey their requests.


### Lesson Path

| Objective | Concept | Resource| Technologies	| Level | Prerequisites
| --- | --- | --- | --- | --- | ---
|Be able to create effective bots with Microsoft Bot Framework | Applications for bots | This video about real world [scenarios for bots](https://channel9.msdn.com/Series/Explain/Bots-101-Scenarios-for-bots) | Bot Framework | Overview | None
| | How the Bot Framework works|This web page about [how the bot framework works](https://docs.microsoft.com/en-us/bot-framework/overview-how-bot-framework-works) | Bot Framework | Overview | None
| | Create bots, debug bots, and manage state|These tutorials about creating a bot [with Node.js](https://www.youtube.com/playlist?list=PLgF-CyaX1p3Exrp9F80bSIdNdnw2iTAZp),[C#](https://mva.microsoft.com/en-US/training-courses/creating-bots-in-the-microsoft-bot-framework-using-c-17590)/[Visual Studio](https://www.youtube.com/playlist?list=PLgF-CyaX1p3FE55OTRNH-kOb16zqeBZCo), [Documentation](https://docs.microsoft.com/en-us/bot-framework/dotnet/bot-builder-dotnet-overview) | Bot Framework, Node.js, Visual Studio, .NET, C#	| Beginner | Programming background
| | |These self-study courses: [Half-day Bot Bootcamp](https://github.com/michhar/bot-masterclass) and [2-day Bot Course](https://github.com/Azure/bot-education) | Bot Framework, Channels, Cognitive Services, ngrok, DirectLine, Application Insights, LUIS, Bot Emulator | Beginner | Programming background
| | |This article about [using FormFlow to build and deploy a bot with ease](https://blogs.msdn.microsoft.com/jamiedalton/2016/07/11/ms-bot-framework-formflow-build-and-deploy-a-bot-with-ease/) | Bot Framework, FormFlow | Intermediate | Experience/exposure to bots
| | |This article about [.NET state management](https://docs.microsoft.com/en-us/bot-framework/dotnet/bot-builder-dotnet-state) | Bot Framework, FormFlow, .NET | Intermediate | Experience/exposure to bots
| | |This video series [playlist of Bot Framework supporting tools and services](https://www.youtube.com/playlist?list=PLgF-CyaX1p3F2c11NVJDIg7TwCpCSaeYm) | Bot Framework, LUIS, ngrok, Azure Bot Service, Azure Functions, NuGet, QnA Maker, Azure Search, Facebook Messenger | Intermediate | General understanding of how the Bot Framework works
| | |These references to [up-to-date bot resources](https://blogs.msdn.microsoft.com/smich/2016/09/30/microsoft-bot-framework-resources/), [samples](https://github.com/Microsoft/BotBuilder-Samples/tree/master/CSharp), and [more samples](https://github.com/search?utf8=%E2%9C%93&q=botbuilder&type=) | Bot Builder SDK, Bot Builder Samples, Samples for Cognitive Services, Samples for Location, Samples for wechat, Samples for wit | Intermediate | Understand the bot framework, programming background
| | | These web pages about debugging bots with [Bot emulator](https://docs.microsoft.com/en-us/bot-framework/debug-bots-emulator), [Visual Studio](https://docs.microsoft.com/en-us/bot-framework/debug-bots-locally-vscode), [Bot Builder](https://blog.botframework.com/2017/07/03/Debug-Bot-Builder-Source/), [ngrok](https://www.youtube.com/watch?v=TiOGGUgN5_c) | Bot Framework, Bot Emulator, Visual Studio, Bot Builder | Intermediate | Programming background
| | |This in-depth [blog post](https://ankitbko.github.io/2016/09/ChatBot-using-Microsoft-Bot-Framework-Part-4) about FormFlow| Bot Framework, LUIS, FormFlow | Advanced | Bot development experience
| | Handing off a bot to a human|This article about creating [bot to human handover in Node.js](https://www.microsoft.com/reallifecode/2017/06/30/bot-to-human-handover-in-node-js/) | Bot Framework, Node.js, Application Insights | Advanced | Bot development experience
|Understand the value of intelligent bots|Microsoft Cognitive Services | This video about [getting started with Cognitive Services](https://channel9.msdn.com//events/Connect/2016/102/) | Cognitive Services |Overview | None
| | |This web page about [Bot intelligence](https://docs.microsoft.com/en-us/bot-framework/cognitive-services-bot-intelligence-overview) | Cognitive Services, Bot Framework | Overview | None
|Be able to add language understanding to bots|What is LUIS|These videos containing an [overview of LUIS](https://www.youtube.com/watch?v=jWeLajon9M8) and [how to get started](https://www.youtube.com/watch?v=q3WRi47Grgs)|	LUIS|Beginner | None
| | Integrate LUIS into bots |This [tutorial](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-nodejs-tutorial-build-bot-framework-sample) about integrating LUIS and bots | LUIS, Bot Framework | Beginner | General LUIS understanding
| | |These [blog posts](https://ankitbko.github.io/2016/08/ChatBot-using-Microsoft-Bot-Framework-Part-2/) [(part two)](https://ankitbko.github.io/2016/08/ChatBot-using-Microsoft-Bot-Framework-Part-3/) about developing bots with LUIS| LUIS, Bot Framework | Intermediate | General understanding of LUIS
| | |This video about [Bots and LUIS: AI for Bot Developers](https://channel9.msdn.com/Blogs/MVP-Office-Dev/Introduction-to-Artificial-Intelligence-for-Bot-Developers-with-LUIS?ocid=player) |LUIS, Bot Framework, Artificial Intelligence | Intermediate | General understanding of LUIS
|Be able to integrate speech into bots|Speech-related Cognitive Services|These web pages about Bing Speech API [capabilities](https://azure.microsoft.com/en-us/services/cognitive-services/speech/) and [documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/Speech/home) | Cognitive Services, Bing Speech API | Overview | None
| | |These web pages about Custom Speech Service [capabilities](https://azure.microsoft.com/en-us/services/cognitive-services/custom-speech-service/) and [documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-speech-service/cognitive-services-custom-speech-home) | Cognitive Services, Custom Speech Service | Overview | None
| |Configure a bot for speech|These Text-to-speech resources contain [sample code](https://code.msdn.microsoft.com/bing/Speech-To-Text-Bot-using-db55e1d0), [documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/Speech/api-reference-rest/bingvoicerecognition), [blog](https://blog.botframework.com/2017/06/26/Speech-To-Text/) | Bot Framework, Cognitive Services, C#, Bing Speech API |Intermediate | Programming background
| | |This tutorial about [teaching a bot to speak](https://docs.microsoft.com/en-us/cortana/tutorials/bot-skills/teach-your-bot-to-speak) | Bot Framework, Cortana, LUIS, SSML | Advanced | Bot development experience
| | | This blog post about [building a Skype calling bot](https://blogs.msdn.microsoft.com/tsmatsuz/2016/10/22/build-skype-calling-bot-with-microsoft-bot-framework/) | Bot Framework, Skype | Advanced | Bot development experience
| | | This web page about how to [build IVR bot for WebChat](https://github.com/Microsoft/BotFramework-WebChat) | Bot Framework, DirectLine, Bot Emulator, WebChat | Advanced | Bot development experience
| | Voice design best practies |This Cortana web page about [voice design best practices](https://docs.microsoft.com/en-us/cortana/design-guides/voice-design-best-practices) | Cortana, LUIS, Bot Framework | Intermediate | Bot development experience
| | | This Cortana video about [voice skill design](https://channel9.msdn.com/Events/Build/2017/B8029) | UX, LUIS, SSML, Cortana | Intermediate | Bot development experience
| | End-to-end implementation of an Interactive Voice Response bot | This solution from the [Cortana Intelligence gallery](https://gallery.cortanaintelligence.com/Solution/Interactive-Voice-Response-Bot)/[GitHub](https://github.com/Azure/cortana-intelligence-interactive-voice-response-bot) that deploys a basic Interactive Voice Response bot  | Bot Connector, Skype Calling Channel, Azure App Services, Cosmos DB, Bing Speech Service, LUIS, Azure Search, Azure SQL, Azure Storage | Intermediate | None


You can also click one of the Links below to see other Lesson Paths.

- [Executive Sponsor](https://github.com/BuckWoody/LearningPaths/tree/master/Executive%20Sponsor)
- [IT Director](https://github.com/BuckWoody/LearningPaths/tree/master/IT%20Director)
- [IT Architect](https://github.com/BuckWoody/LearningPaths/tree/master/IT%20Architect)
- [Data Scientist](https://github.com/BuckWoody/LearningPaths/tree/master/Data%20Scientist)
- [Developer](https://github.com/BuckWoody/LearningPaths/tree/master/Developer)

Enjoy the journey. If you find something we're missing or a Resource doesn't work, please let us know.
