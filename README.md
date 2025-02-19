# Build your first Agent with Azure AI Agent Service

<!-- [![Azure AI Community Discord](
https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.com/invite/ByRwuEEgH4?WT.mc_id=aiml-00001-leestott) -->

This repo is a companion to this workshop at Microsoft AI Tour, a worldwide tour of events.

<!-- > Learn more about Microsoft AI Tour on the official website. -->

<!-- ![Session cover image with a bright "AI" text in 3D over a blue and purple abstract background.](img/mulit-task-assistant-cover.png) -->

## Session Description

Dive into the world of intelligent conversational agents with Azure AI Agent Service, a seamless blend of service and SDK that simplifies the development of robust AI-driven solutions. In this hands-on workshop, you’ll learn to create a powerful agent capable of answering sales-related queries, performing data analysis, generating visualizations, and integrating external data sources to deliver enhanced business insights.

## Learning Outcomes

This workshop demonstrates how to leverage the Azure AI Agent Service to create a robust conversational agent capable of answering sales-related questions, performing data analysis, generating visualizations, and integrating external data sources for enhanced insights. Here are the key takeaways:

1. Function Calling and Dynamic SQL Queries

   - The agent uses the Azure AI Agent Service to dynamically generate and execute SQL queries against a read-only SQLite database, enabling it to respond to user questions with accurate data retrieval.

2. Context Management

   - The agent efficiently manages conversation context using the Azure AI Agent Service, ensuring interactions remain relevant and coherent.

3. Data Visualization

   - With the Code Interpreter, the agent can generate visualizations such as pie charts and tables based on user queries, making data more accessible and actionable.

4. File Generation

   - The agent can create downloadable files, including Excel, CSV, JSON, and image formats, providing users with flexible options to analyze and share data.

5. Grounding with Bing

   - By integrating Bing search, the agent can perform grounded searches for competitive product analysis, expanding its insights beyond internal data sources.

6. Security Best Practices

   - Security risks, such as SQL injection, are mitigated by enforcing read-only database access and running the application within a secure environment.

7. Multi-Language Support

   - The agent and LLM support multiple languages, offering an inclusive experience for users from diverse linguistic backgrounds.

8. Adaptability and Customization

   - The workshop emphasizes the flexibility of the Azure AI Agent Service, allowing you to adapt the agent for various use cases, such as customer support or competitive analysis, by modifying instructions and integrating additional tools.

This workshop equips you with the knowledge and tools to build and extend conversational agents tailored to your business needs, leveraging the full capabilities of the Azure AI Agent Service.

## Additional Resources and Continued Learning

If you want to deliver this talk yourself, you can find the [presenter and proctor resources here](./session-delivery-resources/README.md).

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Azure AI Agent Service  | [Documentation](https://learn.microsoft.com/azure/ai-services/agents/) | Azure AI Agent Service documentation |
| Fundamentals of AI agents on Azure | [Learn module](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/) | Tutorial |
| Introducing Azure AI Agent Service | [Blog post](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/introducing-azure-ai-agent-service/4298357) | Azure AI Agent Service announcement |
| Python library | [Learn more](https://pypi.org/project/azure-ai-projects) | Learn about the Python AI Agents Library |

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/gloveboxes.png" width="100px;" alt="Dave Glover"/><br />
        <sub><b>Dave Glover
</b></sub></a><br />
            <a href="https://github.com/gloveboxes" title="talk">📢</a>
    </td>
</tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. Within Azure AI Studio, the Content Safety service allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in). You also have the ability to create and evaluate with [custom evaluators](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators).

You can evaluate your AI application in your development environment using the [Azure AI Evaluation SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the azure ai evaluation sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).
