# Azure AI Foundry

## The JS AI Build-a-thon Study Guide

![banner](/jsai-buildathon-assets/build-a-thon-banner.png)

## Objectives 

- Understanding how to intergrate AI capabilities in your web applications using JavaScript/ TypeScript
- Explore various technologies and frameworks including Azure AI Foundry, Azure Developer CLI (azd), LangChain.js, AI Toolkit and other additional Azure tools.
- Complete hands-on quests that take you from local prototypes to building complete applications

## Recommendations & Best Practices for Success

- Complete all activities provided under each quest. This will help you successfully intergrate all the AI features into your application
- Ensure you join our [dedicated channel on Discord](https://aka.ms/JSAIonDiscord) to interact with other participants and ask questions when stuck. Channel name is _js-ai-build-a-thon_
- Complete all quests to claim your participation badge and celebrate your success

    ‼️ **IMPORTANT NOTE: Update Alert: Quest 6 got an Upgrade** 🎁
    - Quest 6 got a facelift—with new & clearer instructions and a streamlined workflow update.  To sync these updates into your workspace without disrupting your progress tracking, follow the instructions below to fetch and replace the two key files:
    
    - **Step 1: Run this command in your repo root:**

        _If on Windows:_
        ```shell
        curl.exe -LfO https://raw.githubusercontent.com/Azure-Samples/JS-AI-Build-a-thon/main/.github/steps/6-build-agent.md
        curl.exe -LfO https://raw.githubusercontent.com/Azure-Samples/JS-AI-Build-a-thon/main/.github/workflows/6-build-agent.yml
        ```

        Then run:
        ```shell
        mv -Force 6-build-agent.md .github/steps/
        mv -Force 6-build-agent.yml .github/workflows/
        ```

        _If on MacOS:_
        ```shell
        curl -LfO https://raw.githubusercontent.com/Azure-Samples/JS-AI-Build-a-thon/main/.github/steps/6-build-agent.md
        curl -LfO https://raw.githubusercontent.com/Azure-Samples/JS-AI-Build-a-thon/main/.github/workflows/6-build-agent.yml
        ```
        Then:
        ```shell
        mv -f 6-build-agent.md .github/steps/
        mv -f 6-build-agent.yml .github/workflows/
        ```

    - **Step 2: Push the 2 updated files on GitHub**

        ```bash
        git add .github/steps/6-build-agent.md .github/workflows/6-build-agent.yml
        git commit -m "Updated Quest 6 instructions"
        git push
        ```
    - **Step 3: If your progress is already on Quest 6 _(You have Quest 6 on your README)_, reset your progress by clicking on the `Reset progres` button at the top of your file. Once on the welcome page, select the `I want to build an AI Agent` Quest**

    Done! The new files are in place
        
    📌 Reminder: Do this before starting Quest 6. You’ll be working with the latest version. Got questions? Drop them in our Discord! 


## Quests

To get sailing on the quest, go to the [JS AI Build-a-thon](http://aka.ms/JSAIBuildathon) repository
![timeline](/jsai-buildathon-assets/jsaibuildathon-timeline.png)

|**Quest**|**Date**|**Video Guide & Blog**|**Tools & Technologies**|
|----|----|----|----|
|[JS AI Build-a-thon Launch](https://developer.microsoft.com/en-us/reactor/events/25957/) |Pre - Build-a-thon|[Announcement Blog](https://techcommunity.microsoft.com/blog/AzureDevCommunityBlog/%F0%9F%9A%A8introducing-the-js-ai-build-a-thon-%F0%9F%9A%A8/4420474)||
|Setup for the Build-a-thon |June 09 |[JS AI Build-a-thon Setup in 5 Easy Steps](https://techcommunity.microsoft.com/blog/azuredevcommunityblog/js-ai-build-a-thon-setup-in-5-easy-steps/4421787)|GitHub|
|I Want to Build a Local Gen AI Prototype |June 09 |[Guide](https://aka.ms/JSAIBuildathonQuest1)|GitHub Models (free), AI Toolkit in VS Code|
|I want to move my prototype to Azure |June 11 |[Guide](https://aka.ms/JSAIBuildathonQuest2)|Azure AI Foundry extension in VS Code|
|I want to add a simple chat interface to my app |June 13 |[Guide](https://aka.ms/JSAIBuildathonQuest3)|Azure Developer CLI _(Infrastructure as Code)_|
|I want to integrate external data using RAG |June 16 |[Guide](https://aka.ms/JSAIBuildathonQuest4)|RAG|
|I want to explore AI frameworks and add chat memory |June 18 |Coming soon|LangChain.js|
|I want to build an AI Agent |June 20 |Coming soon|Azure AI Foundry extension in VS Code|
|I want to extend an agent with MCP tools |June 23 |Coming soon|AI Toolkit in VS Code|
|I want to use AI to automate PR code reviews |June 25 |Coming soon|GenAIScript|
|I want to customize a production ready template |June 27 |Coming soon|Azure Developer CLI _(Infrastructure as Code)_|
|[JS AI Build-a-thon Closing Ceremony](https://developer.microsoft.com/en-us/reactor/events/25958/) |June 30|Coming soon||

## Get help
- You can join a group of other learners by registering for one of our community led study jams found on the [repo](https://github.com/Azure-Samples/JS-AI-Build-a-thon?tab=readme-ov-file#-get-help).
- To interact with other participants and get assistance and answers when needed, join [our Discord channel](https://aka.ms/JSAIonDiscord)

## Claim Participation Badge
Once you have completed all quests, you will be issued an AI Build-a-thon participant badge to mark your milestone. 
