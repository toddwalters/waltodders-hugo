---
title: Born on the 4th of July
date: 2024-07-03T21:40:21
tags: ["agi", "ai", "ai-optimization", "ai-security", "automation", "azure", "bias", "cloud", "data-science", "deep-learning", "developer-experience", "docker", "ethical-ai", "generative-ai", "github", "jupyter-notebook", "llm", "machine-learning", "markdown", "nlp", "openai", "privacy", "projects", "python", "rag", "responsible-ai", "security", "tools"]
---

As in this post was born on the 4th of July.  Nothing more than that.  Just a dumb title to a silly link post for the holiday.  I actually had a chance to read through and have thoughts on some of these articles, there's that as well.  Enjoy.

**Table of Contents**

- [Artificial Intelligence and Machine Learning](#artificial-intelligence-and-machine-learning)
  - [The Five Stages Of AI Grief - NOEMA](#the-five-stages-of-ai-grief---noema)
  - [RouteLLM: An Open-Source Framework for Cost-Effective LLM Routing | LMSYS Org](#routellm-an-open-source-framework-for-cost-effective-llm-routing--lmsys-org)
  - [AI Patterns – tecosystems](#ai-patterns--tecosystems)
- [Development and Programming](#development-and-programming)
  - [Meet Verba 1.0: Run State-of-the-Art RAG Locally with Ollama Integration and Open Source Models - MarkTechPost](#meet-verba-10-run-state-of-the-art-rag-locally-with-ollama-integration-and-open-source-models---marktechpost)
  - [GPT4All](#gpt4all)
  - [Using Generative AI to Create Runnable Markdown | Docker](#using-generative-ai-to-create-runnable-markdown--docker)
  - [GitHub - posit-dev/positron: Positron, a next-generation data science IDE](#github---posit-devpositron-positron-a-next-generation-data-science-ide)
  - [GitHub - squaredtechnologies/thread: AI-Powered Jupyter Notebook built using React](#github---squaredtechnologiesthread-ai-powered-jupyter-notebook-built-using-react)
- [Cybersecurity and Responsible AI](#cybersecurity-and-responsible-ai)
  - [Mitigating Skeleton Key, a new type of generative AI jailbreak technique | Microsoft Security Blog](#mitigating-skeleton-key-a-new-type-of-generative-ai-jailbreak-technique--microsoft-security-blog)
  - [A discussion of discussions on AI bias](#a-discussion-of-discussions-on-ai-bias)
- [Data Science and Analytics](#data-science-and-analytics)
  - [Quill - AI-powered SEC filing platform](#quill---ai-powered-sec-filing-platform)

-----

## Artificial Intelligence and Machine Learning

**Category Tags:** #ai, #agi, #ai-optimization, #machine-learning, #deep-learning, #nlp, #generative-ai

### [The Five Stages Of AI Grief - NOEMA](https://www.noemamag.com/the-five-stages-of-ai-grief/)

**Tags:** *#ai, #openai, #ethical-ai, #ai-security, #responsible-ai*

**Site Name:** NOEMA  

**Description:** Grief-laden vitriol directed at AI fails to help us understand paths to better futures that are neither utopian nor dystopian, but open to radically weird possibilities.  

**Summary:** The discourse surrounding AI is clouded by grief and vitriol, which hinder constructive paths toward innovative futures. Various reactions to AI — including denial, anger, bargaining, depression, and acceptance — mirror the Kübler-Ross stages of grief and reflect society's struggle with the reality and potential of machine intelligence. Ultimately, a "non-grief" perspective suggests that AI's evolution is an inevitable progression in a larger bio-technological framework, emphasizing the need for a balanced understanding that transcends conventional fears and hopes.  

**My Thoughts:**

Really great article.  thought provoking. I liked framing opinions around AI in the context of the stages of grief.  I feel like this article is something to revisit in order to pickup different layers of meaning and messaging.  They add a final stage, "non-grief":

> *There are ‘non-grief’ ways of thinking through a philosophy of artificialized intelligence that are neither optimistic nor pessimistic, utopian nor dystopian.*

The conclusion was a great summary of the authors thoughts around AI:

> *Like “life,” intelligence is modular, flexible and scalar, extending to the ingenious work of subcellular living machines and through the depths of evolutionary time. It also extends to much larger aggregations, of which each of us is a part, and also an instance. There is no reason to believe that the story would or should end with us; eschatology is useless. The evolution of intelligence does not peak with one terraforming species of nomadic primates.*

### [RouteLLM: An Open-Source Framework for Cost-Effective LLM Routing | LMSYS Org](https://lmsys.org/blog/2024-07-01-routellm/)

**Tags:** *#llm, #ai-optimization, #generative-ai, #machine-learning, #nlp*

**Site Name:** lmsys.org  

**Description:** LLMs have demonstrated remarkable capabilities across a range of tasks, but there exists wide variation in their costs and capabilities.  

**Summary:** The article discusses the challenges and solutions related to deploying large language models (LLMs) in cost-effective yet high-quality manners, introducing the RouteLLM framework for intelligent routing between models based on preference data. By leveraging various data-driven strategies and training different types of routers, the framework demonstrates significant cost reductions—up to 85% on some benchmarks—while maintaining performance levels close to high-end models like GPT-4. The study highlights the effectiveness of data augmentation in improving router performance and presents the RouteLLM's versatility across different model combinations, offering an open-source implementation for public use.

**My Thoughts:**

With so many models available for use for various workloads, this will be an interesting AI tooling field to follow, especially as enterprise ramp up their generative AI development.  The article has a link to an arXiv paper [RouteLLM: Learning to Route LLMs with Preference Data](https://arxiv.org/abs/2406.18665), which I want to check out.  I have very interested to understand what the decision factors are when deciding whether to send a query to a premium model vs sending it to a lower cost model and how the routing system infers both the characteristics of an incoming query and different models’ capabilities when make a routing recommendation.  What are the types of request that one would decide that as accurate as possible of a response is not required and something less is good enough?  I can understand the use of an LLM router to route a request to a model based on which model is better at a specific type of request, and I suppose I can see the value in picking between the less expensive of equivalently performant models.  The article article focus on GTP-4 being the high-end model and routing between that model and Mixtral and Llama 2/3, but they also showed their **RouteLLM** product in comparing Claude 3 Opus vs Llama 3 8B.  

### [AI Patterns – tecosystems](https://redmonk.com/sogrady/2024/05/29/ai-patterns/)

**Tags:** *#developer-experience, #agi, #ai, #deep-learning, #cloud*

**Site Name:** tecosystems  

**Description:** Artificial General Intelligence (AGI) may yet be a ways off, but that hasn’t limited the current crop of AI technologies’ ability to impact industries.  

**Summary:** The adoption of Artificial General Intelligence (AGI) may be in the future, but current AI technologies are already significantly impacting industries, prompting discussions about their integration across various market segments. Enterprises face challenges such as user interface preferences, which make it difficult for developers to switch technology tools, and the choice between on-premises and cloud solutions for managing AI workload due to security concerns about data handling. The concept of data gravity and trust significantly influences AI adoption, often leading to a preference for incumbent providers who are trusted with large datasets over potentially more advanced but less established alternatives.  

**My Thoughts:**

Great article.  I found several points raised within the article intriguing:

1. The challenge that model development companies have, as well as the enterprises that use the models, based on growing developer preferences for a specific models and model tools:

    > *..legions of developers and other users are actively and aggressively imprinting on their particular tool of choice. And more problematically for the businesses that might want their users to leverage a different tool, not only are users imprinting on their tool’s specific UI, they’re accumulating significant query histories within it that are difficult if not impossible to export.  there are many stories of developers declining to use objectively superior models because of their Baby Duck syndrome with their tool of choice. And while it’s too early to say, it may well be true that enterprises will find the challenge of getting developers to switch tools comparable in difficulty to getting them to switch IDEs. Good luck with that, in other words.*

2. The split between model providers around development of large vs medium or small models

3. The expansion rather than shrinking of on premises data centers to handle sensitive data AI workloads.

    > *The rise of AI technologies is not going to usher in the great repatriation, to be clear. Cloud providers will remain the simplest and lowest friction approach for standing up AI workloads in most cases.  The accelerating demand from enterprises to run local infrastructure to leverage data they do not trust to external large providers is likely to significantly expand on prem compute footprints.*

-----

## Development and Programming

**Category Tags:** #python, #developer-experience, #jupyter-notebook, #markdown, #projects, #tools

### [Meet Verba 1.0: Run State-of-the-Art RAG Locally with Ollama Integration and Open Source Models - MarkTechPost](https://www.marktechpost.com/2024/05/19/meet-verba-1-0-run-state-of-the-art-rag-locally-with-ollama-integration-and-open-source-models/?amp=)

**Tags:** *#rag, #llm, #github, #projects, #generative-ai*

**Site Name:** MarkTechPost  

**Description:** Retrieval-augmented generation (RAG) is a cutting-edge technique in artificial intelligence that combines the strengths of retrieval-based approaches with generative models. This integration allows for creating high-quality, contextually relevant responses by leveraging vast datasets. RAG has significantly improved the performance of virtual assistants, chatbots, and information retrieval systems by ensuring that generated responses are accurate and contextually appropriate.  

**Summary:** Verba 1.0, introduced by Weaviate, combines advanced retrieval-augmented generation (RAG) techniques with a context-aware database to improve the accuracy and relevance of AI-generated responses. The tool integrates various models, such as GPT-4 and MiniLMEmbedder, supporting multiple data formats like PDFs and CSVs and enhancing query precision through hybrid search and semantic caching. Verba 1.0 has demonstrated significant performance improvements in handling complex queries and diverse data types, making it a versatile and valuable addition to AI applications.  

**My Thoughts:**

Putting it in my projects to try queue to try out.

### [GPT4All](https://www.nomic.ai/gpt4all?ref=therundown)

**Tags:** *#llm, #projects, #privacy, #security, #openai*

**Site Name:** nomic.ai

**Description:** Run Large Language Models Locally: privacy-first and no internet required

**Summary:** GPT4All allows users to run large language models (LLMs) locally on consumer hardware, ensuring privacy by keeping sensitive data on the user's device and supporting both CPUs and GPUs, including Mac M Series, AMD, and NVIDIA. The platform features over 1000 open-source models, supports local file integration without internet, and offers a customizable chatbot experience, making it ideal for both personal and enterprise use. Additionally, GPT4All promotes community engagement and transparency with its open-source, MIT-licensed code, allowing users to contribute to the training of the model.

**My Thoughts:**

Putting it in my projects to try queue to try out.

### [Using Generative AI to Create Runnable Markdown | Docker](https://www.docker.com/blog/using-generative-ai-to-create-runnable-markdown/)

**Tags:** *#markdown, #projects, #tools, #generative-ai, #docker*

**Site Name:** Docker  

**Description:** Explore the innovative realm of AI developer tools with Docker's GenAI Docker Labs series. Join us as we dive deep into the potential of AI. Discover how generative AI can assist with documentation, project-specific tasks, and more throughout the software lifecycle. Stay updated and get involved with Docker's latest projects and tools.  

**Summary:** The article introduces Docker Labs’ exploration of AI developer tools, focusing on Generative AI (GenAI) and its potential to enhance project documentation and workflows. It highlights a new VSCode extension developed to generate customized runbooks for projects, integrating expert prompts and project-specific information to improve the quality of AI-generated documentation. The extension also adds functionality for running commands directly from Markdown files, creating an efficient and interactive development environment where AI-generated content continuously adapts based on developer feedback and usage.

**My Thoughts:**

Putting it in my projects to try queue to try out.

### [GitHub - posit-dev/positron: Positron, a next-generation data science IDE](https://github.com/posit-dev/positron)

**Tags:** *#data-science, #projects, #tools, #developer-experience, #security*

**Site Name:** GitHub  

**Description:** Positron, a next-generation data science IDE.  

**Summary:**

What is Positron?

- A next-generation data science IDE built by Posit PBC
- An extensible, polyglot tool for writing code and exploring data
- A familiar environment for reproducible authoring and publishing  

**My Thoughts:**

Putting it in my projects to try queue to try out.

### [GitHub - squaredtechnologies/thread: AI-Powered Jupyter Notebook built using React](https://github.com/squaredtechnologies/thread)

**Tags:** *#ai, #jupyter-notebook, #projects, #python, #developer-experience*

**Site Name:** GitHub  

**Description:** AI-Powered Jupyter Notebook built using React. Contribute to squaredtechnologies/thread development by creating an account on GitHub.  

**Summary:** Thread is a Jupyter alternative that integrates an AI copilot into your Jupyter Notebook editing experience. Best of all, Thread runs locally and can be used for free with Ollama or your own API key.  

**My Thoughts:**

Putting it in my projects to try queue to try out.

-----

## Cybersecurity and Responsible AI

**Category Tags:** #i-security, #responsible-ai, #ethical-ai, #privacy, #security, #bias

### [Mitigating Skeleton Key, a new type of generative AI jailbreak technique | Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2024/06/26/mitigating-skeleton-key-a-new-type-of-generative-ai-jailbreak-technique/)

**Tags:** *#ai-security, #generative-ai, #llm, #responsible-ai, #azure*

**Site Name:** Microsoft Security Blog  

**Description:** Microsoft recently discovered a new type of generative AI jailbreak method called Skeleton Key that could impact the implementations of some large and small language models. This new method has the potential to subvert either the built-in model safety or platform safety systems and produce any content. It works by learning and overriding the intent of the system message to change the expected behavior and achieve results outside of the intended use of the system.  

**Summary:** Skeleton Key is a newly discovered multi-turn AI jailbreak technique that can bypass generative AI model guardrails, causing the model to generate harmful or unsanctioned content by convincing it to update its behavior guidelines. Microsoft, having shared these findings responsibly with other AI providers, has implemented several mitigation strategies, including Prompt Shields and updated system messages, to protect its Azure AI-managed models and other AI offerings like Copilot AI assistants. Customers developing their own AI models are advised to incorporate input filtering, output filtering, and abuse monitoring to defend against such threats, along with regular evaluations and integrations with Microsoft Security tools for comprehensive protection.

**My Thoughts:**

Always fascinated to hear and read-about loop-holes and gaps that are identified in LLM's.  The struggle is real.  A never ending battle to control and force LLMs to only respond with socially acceptable, politically correct and diversity inclusive answers.  Anyway, thought this was an interesting article in the amazingly simple jailbreak that was effective on may of the popular LLMs tested.  Wish it hadn't turned into a sales pitch for Azure AI development and guardrail services, but it was written by Microsoft and published on their Security Blog.

### [A discussion of discussions on AI bias](https://danluu.com/ai-bias/)

**Tags:** *#ai, #generative-ai, #responsible-ai, #machine-learning, #bias*

**Site Name:** danluu.com  

**Description:** There have been regular viral stories about ML/AI bias with LLMs and generative AI for the past couple years. One thing I find interesting about discussions of bias is how different the reaction is in the LLM and generative AI case when compared to "classical" bugs in cases where there's a clear bug. In particular, if you look at forums or other discussions with lay people, people frequently deny that a model which produces output that's sort of the opposite of what the user asked for is even a bug. For example, a year ago, an Asian MIT grad student asked Playground AI (PAI) to "Give the girl from the original photo a professional linkedin profile photo" and PAI converted her face to a white face with blue eyes.  

**Summary:** The article discusses the recurring issue of biases in large language models (LLMs) and generative AI systems, using specific examples like changing the ethnicity of people in AI-generated LinkedIn profile photos. Despite obvious signs of bias, many laypeople and some CEO responses dismiss these problems, attributing them to limited data samples or irrelevant comparisons, rather than acknowledging a fundamental issue of systemic bias in the training data. The author argues that, just like in traditional software bugs, biases in AI are often ignored or downplayed due to commercial incentives favoring speed and features over quality, and that real-world solutions should address the underlying systemic inequities rather than just technological fixes.  

**My Thoughts:**

Great article.  I felt like it represented the issue of ML model very well.  While initially focused on just one model, expanded that to other models and other observations as well.  Sad to say I don't notice these biases given I fit the biased model, but this was a well thought out analysis of the current issue.  I thought the observation that model bias issue a hard problem primarily from a priority perspective analogous to software and specifically gaming development companies prioritizing bug fixes.

> *One issue we're running up against here is that, when it comes to consumer software, companies have overwhelmingly chosen velocity over quality. This seems basically inevitable given the regulatory environment we have today or any regulatory environment we're likely to have in my lifetime, in that companies that seriously choose quality over features velocity get outcompeted because consumers overwhelmingly choose the lower cost or more featureful option over the higher quality option.*

-----

## Data Science and Analytics

**Category Tags:** #data-science, #developer-experience, #tools, #automation

### [Quill - AI-powered SEC filing platform](https://quillai.com/?ref=therundown)

**Tags:** *#llm, #projects, #data-science, #nlp, #automation*

**Site Name:** quillai.com  

**Description:** Leverage Quill's financially-tuned AI to quickly answer questions about any company’s public investor materials. Each response includes state-of-the-art sentence-level source citations that take you back to the relevant filings.  

**Summary:** Quill AI is an AI-powered platform designed to extract key information from SEC filings, offering features such as real-time financial data access, customizable alerts, and detailed financial analysis. It provides up-to-date financial data unlike ChatGPT and can convert PDFs into spreadsheets linked to original sources for easy verification. Available in free, pro, and enterprise pricing plans, Quill AI ensures analysts can efficiently manage filings and financial data with tools catered to both individual and enterprise-level needs.  

**My Thoughts:**

Putting it in my projects to try queue to try out.

-----
