# Welcome to the AI Airlift: Intelligent Apps+Agents

Welcome to this three-day AI Airlift focused on Intelligent Apps/Agents and Knowledge Mining. In these three days, we will focus on hands-on activities that develop proficiency in AI-oriented services such as Azure Bot Services, Azure Search (including Cognitive Search), and Cognitive Services. Additionally, we will provide various design and architecture guidance/activities so you are not only able to build POC/solutions, but so you are also able to architect and design them.  

# Goals

Most challenges observed by customers in these realms are in stitching multiple services together. As such, where possible, we have tried to place key concepts in the context of broader examples. 

At the end of this 300-level workshop, you should be able to:

- Build an application that calls various Cognitive Services APIs (specifically Computer Vision)
- For Cognitive Services, determine what to use when and how to combine multiple to increase the intelligence and capabilities of bots/apps 
- Understand how to implement Azure Search features to provide a positive search experience inside applications
- Configure an Azure Search service to extend your data to enable full-text, language-aware search
- Design and build a Cognitive Search solution
- Build, train, and publish a LUIS model to help your bot communicate effectively
- Be able to efficiently and effectively design LUIS schema
- Build an intelligent bot using Microsoft Bot Framework that leverages LUIS and Azure Search
- Be able to decide the most appropriate architectural components common bot use-cases
- Effectively log chat conversations in your bot
- Perform rapid development/testing with Ngrok and test your bots with unit tests and direct bot communication
- Effectively leverage the custom vision service to create image classification services that can then be leveraged by an application

# Azure Access
We will not be providing Azure passes for this workshop. If you do not have the ability to create resources and spend money on Azure, you will not be able to participate.

# Breaks

This is an airlift where we are trying to cover as much material as possible. As such, we will not be providing scheduled breaks (apart from lunch). Feel free to step out to take a break as needed (preferably if you finish a lab early), but the airlift will continue.  


# Agenda

Please note: This is a rough agenda, and the schedule is subject to change pending class activities and interaction. Also note that the numbering here will not always be the same as the numbering in the references. This airlift is a combination of several courses.

- Day 1: Cognitive Services
  - 8:30-9:15: [Setup](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.1-computer_vision/1_Setup.md)
  - 9:15-10: [Cognitive Services](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/05-cognitive_services/1_session.ipynb) and [PictureBot Introduction](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.1-computer_vision/0_README.md)
  - 10-12: [Lab 1: Computer Vision](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.1-computer_vision/0_README.md)
  - 12-1: Lunch
  - 1-1:30: Custom Vision Service Introduction
  - 1:30-2: [Lab 2: Custom Vision Service I: Image Classification](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.2_customvision01/0_README.md)
  - 2-2:30: [Lab 3: Custom Vision Service II: Object Detection](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.3_customvision02/0_README.md)
    - Have extra time? Check out the [Challenge](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.4_customvision03/0_README.md)
  - 2:30-3:30: [Lab 4: Azure Search](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.1-azure_search/0_README.md)
  - 3:30-4: [Bot Design](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/02-bot_design/1_session.ipynb) and [LUIS Design](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/03-luis/1_session.ipynb)
  - 4-5: Day 1 Case: [Part 1: Bots](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/02-bot_design/2_activity.md) and [Part 2: LUIS](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/03-luis/2_activity.md)
- Day 2: Bots
  - 8:30-9:45: [Lab 5: Language Understanding Intelligent Service (LUIS)](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab01.5-luis/0_README.md)
  - 9:45-10:15: [Bot Architectures](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/04-architectures/1_session.ipynb)
  - 10:15-12: [Lab 6: Building Intelligent Bots](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.2-building_bots/0_README.md)
  - 12-1: Lunch
  - 1-2:  [Lab 7: Bot Logging](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.3-logging_chat_conversations/0_README.md)
  - 2-3: [Lab 8: Bot Testing](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.4-testing_bots/0_README.md)
  - 3-4: Day 2 Case: [Bot Architectures](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/04-architectures/2_activity.md)
  - 4-5: Discussion/Presentations: Days 1+2 Cases
- Day 3: Knowledge Mining and Final Case
  - 8:30-9: Bootcamp Recap and What's Next
  - 9-9:30: Cognitive Search [Introduction](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/01-Introduction.md) and [Lab Architecture](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/02-Solution-Architecture.md)
  - 9:30-9:45: [Setup](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/03-Environment-Creation.md)
  - 9:45-10:30: [Lab 9: Cognitive Search I: Text Skills](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/04-Lab-1-Text-Skills.md)
  - 10:30-11:30: [Lab 10: Cognitive Search II: Image Skills](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/05-Lab-2-Image-Skills.md)
    - Have extra time? Check out the [Challenge: Custom Skills](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/06-Lab-3-Custom-Skills.md)
  - 11:30-12: Final Case: [Introduction](./final_case.md)
  - 12-1:
  - 1-3: Final Case: Working time
  - 3-4: Final Case: Presentations
  - 4-5: Airlift Q&A and Feedback

# Further Learning
Check out the all of our [LearnAI courses](https://aka.ms/lap) and [our team's site](https://learnanalytics.microsoft.com/home/index) to find upcoming trainings, Training Partners and more.


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.