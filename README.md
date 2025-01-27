# Getting Started with AI Agents
[![Azure AI Community Discord](
https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.com/invite/ByRwuEEgH4?WT.mc_id=academic-105485-koreyst)

This repo is a companion to this session at Microsoft AI Tour, a worldwide tour of events.

> Learn more about Microsoft AI Tour on the official website.

## Session Desciption

Explore the fascinating world of AI agents with Azure! Dive into the innovative Azure AI Agent Service, where you’ll discover how these intelligent agents can transform processes and products. Learn about the diverse use cases, from automating customer support to enhancing decision-making processes. Understand why AI agents are essential for modern businesses, offering efficiency, scalability, and advanced problem-solving capabilities. 


## Learning Outcomes
1. Gain a fundamental understanding of what AI agents are and how they function.

2. Discover various use cases for AI agents across different industries.

3. Learn about the features and capabilities of the Azure AI Agent Service.

4. Understand how to implement AI agents using the Azure AI Agent Service in your projects.​

## Technology Used
1. Azure OpenAI Service 

2. Azure AI Foundry 

3. Azure AI Agent Service

## Additional Resources and Continued Learning

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| AI Foundry	  | [AI Foundry](https://ai.azure.com/) | Azure AI Foundry is a platform for building, evaluating, and deploying generative AI solutions and custom copilots. |
| AI Agent Service  | [AI Agent Service](https://learn.microsoft.com/en-us/azure/ai-services/agents/) | Azure AI Agent Service is a fully managed service designed to empower developers to securely build, deploy, and scale high-quality, and extensible AI agents without needing to manage the underlying compute and storage resources |
| Semantic Kernel Agent Framework  | [Semantic Kernel Agent Framework](https://learn.microsoft.com/en-us/semantic-kernel/frameworks/agent/?pivots=programming-language-csharp) | The Semantic Kernel Agent Framework provides a platform within the Semantic Kernel eco-system that allow for the creation of AI agents and the ability to incorporate agentic patterns into any application based on the same patterns and features that exist in the core Semantic Kernel framework. |
| AutoGen Agent Framework  | [AutoGen Agent Framework](https://microsoft.github.io/autogen/stable/) | AutoGen core offers an easy way to quickly build event-driven, distributed, scalable, resilient AI agent systems. Agents are developed by using the Actor model.  |

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="https://github.com/koreyspace">
        <img src="https://github.com/koreyspace.png" width="100px;" alt="Korey Stegared-Pace"/><br />
        <sub><b>Korey Stegared-Pace</b></sub>
    </a><br />
    </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. Within Azure AI Foundry, the Content Safety service allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in). You also have the ability to create and evaluate with [custom evaluators](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators).

You can evaluate your AI application in your development environment using the Azure AI Evaluation SDK. Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the azure ai evaluation sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Foundry](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).


