---
title: Lucky To Make It Once A Month
date: 2024-07-02T13:23:05-0400
tags: ["advanced-ai", "ai", "ai-governance", "ai-optimization", "ai-reliability", "ai-security", "anthropic", "automation", "azure", "claude", "cloud-computing", "cyber-security", "data-science", "developer-experience", "ethical-ai", "enterprise-architecture", "fin-ops", "generative-ai", "github-repo", "gtp-4", "juypter-notebooks", "langchain", "llm", "machine-learning", "nlp", "openai", "personal-development", "projects", "python", "rag", "responsible-ai", "security"]
---

Wow.  So it's be another long while, since I got around to creating another post. This one is another link list, based what has caught my eye over the last month.  Can't say I have read them all, but good list to come back to as time permits.  

Something I did decide to do based on having all of these articles, was to create a python script that would interact with the [Omnivore API](https://docs.omnivore.app/integrations/api.html) (the application I use to grab links and content I want to read later) to grab all the articles I have saved and send all of those to openAI to create a summary and suggest some tags.  I will eventually create a write-up for that project, but wanted to get this link list out first. Seems to have turned out ok, but many improvements to make.

-----

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Artificial Intelligence and Machine Learning](#artificial-intelligence-and-machine-learning)
  - [Networking capabilities optimize traffic for generative AI apps](#networking-capabilities-optimize-traffic-for-generative-ai-apps)
  - [Introducing Apple’s On-Device and Server Foundation Models](#introducing-apples-on-device-and-server-foundation-models)
  - [Understanding the Cost of Generative AI Models in Production](#understanding-the-cost-of-generative-ai-models-in-production)
  - [What We Learned from a Year of Building with LLMs (Part I)](#what-we-learned-from-a-year-of-building-with-llms-part-i)
  - [situationalawareness](#situationalawareness)
  - [Deploying A GPT-4o Model to Azure OpenAI Service](#deploying-a-gpt-4o-model-to-azure-openai-service)
  - [Why are most LLMs decoder-only?.](#why-are-most-llms-decoder-only)
  - [\[2406.11903\] A Survey of Large Language Models for Financial Applications: Progress, Prospects and Challenges](#240611903-a-survey-of-large-language-models-for-financial-applications-progress-prospects-and-challenges)
  - [\[2405.00332\] A Careful Examination of Large Language Model Performance on Grade School Arithmetic](#240500332-a-careful-examination-of-large-language-model-performance-on-grade-school-arithmetic)
  - [Researchers upend AI status quo by eliminating matrix multiplication in LLMs](#researchers-upend-ai-status-quo-by-eliminating-matrix-multiplication-in-llms)
  - [Machine Learning Mastery](#machine-learning-mastery)
  - [Open challenges for AI engineering](#open-challenges-for-ai-engineering)
  - [Build Rag With Llamaindex To Make LLM Answer About Yourself, Like in an Interview or About General InformationI](#build-rag-with-llamaindex-to-make-llm-answer-about-yourself-like-in-an-interview-or-about-general-informationi)
  - [Build your own Large Language Model (LLM) From Scratch Using PyTorch](#build-your-own-large-language-model-llm-from-scratch-using-pytorch)
  - [Meet Verba 1.0: Run State-of-the-Art RAG Locally with Ollama Integration and Open Source Models](#meet-verba-10-run-state-of-the-art-rag-locally-with-ollama-integration-and-open-source-models)
  - [What Is ChatGPT Doing … and Why Does It Work?](#what-is-chatgpt-doing--and-why-does-it-work)
  - [Detecting hallucinations in large language models using semantic entropy](#detecting-hallucinations-in-large-language-models-using-semantic-entropy)
  - [I Will Fucking Piledrive You If You Mention AI Again](#i-will-fucking-piledrive-you-if-you-mention-ai-again)
- [Cloud Computing and Infrastructure](#cloud-computing-and-infrastructure)
  - [The Modern Architect Playlist](#the-modern-architect-playlist)
  - [Blog - Private Cloud Compute: A new frontier for AI privacy in the cloud](#blog---private-cloud-compute-a-new-frontier-for-ai-privacy-in-the-cloud)
  - [Platform as a Runtime - The Next Step in Platform Engineering](#platform-as-a-runtime---the-next-step-in-platform-engineering)
  - [Data store decision tree - Azure Application Architecture Guide](#data-store-decision-tree---azure-application-architecture-guide)
  - [Polyfill.io, BootCDN, Bootcss, Staticfile attack traced to 1 operator](#polyfillio-bootcdn-bootcss-staticfile-attack-traced-to-1-operator)
  - [Building a Platform Team at a 153-Year-Old Company](#building-a-platform-team-at-a-153-year-old-company)
- [Cybersecurity](#cybersecurity)
  - [Uncensor any LLM with abliteration](#uncensor-any-llm-with-abliteration)
  - [Is your AI workload secure?](#is-your-ai-workload-secure)
  - [Web Check](#web-check)
- [Development and Programming](#development-and-programming)
  - [GitHub - mshumer/ai-researcher](#github---mshumerai-researcher)
  - [Platform as a Runtime - The Next Step in Platform Engineering](#platform-as-a-runtime---the-next-step-in-platform-engineering-1)
  - [Developer Experience Is Still Developing](#developer-experience-is-still-developing)
  - [GitHub - dotenvx/dotenvx: a better dotenv–from the creator of `dotenv`](#github---dotenvxdotenvx-a-better-dotenvfrom-the-creator-of-dotenv)
  - [4 keys to writing modern Python](#4-keys-to-writing-modern-python)
  - [GitHub - Doriandarko/claude-engineer](#github---doriandarkoclaude-engineer)
  - [Why we no longer use LangChain for building our AI agents](#why-we-no-longer-use-langchain-for-building-our-ai-agents)
  - [GitHub - squaredtechnologies/thread: AI-Powered Jupyter Notebook built using React](#github---squaredtechnologiesthread-ai-powered-jupyter-notebook-built-using-react)
  - [Every Way To Get Structured Output From LLMs](#every-way-to-get-structured-output-from-llms)
  - [My 5 favorite ways of keeping the technical axe sharp - same stuff, different day](#my-5-favorite-ways-of-keeping-the-technical-axe-sharp---same-stuff-different-day)

-----

## Artificial Intelligence and Machine Learning

**Category Tags:** *#ai, #advanced-ai, #ai-applications, #ai-governance, #ai-optimization, #ai-reliability, #ai-security, #ai-trust, #responsible-ai, #ethical-ai, #generative-ai, #llm, #machine-learning, #nlp, #transformer, #neural-network, #langchain, #chatgpt, #gpt-4, #data-science, #data-protection, #data-security, #dataset-contamination, #model-overfitting, #learning, #visualization*

-----

### [Networking capabilities optimize traffic for generative AI apps](https://cloud.google.com/blog/products/networking/networking-capabilities-optimize-traffic-for-generative-ai-apps)

**Site Name:** Google Cloud Blog

**Summary:** The article discusses the networking challenges faced by enterprises looking to deploy large language models for generative AI applications, which exhibit unique traffic patterns and computing behaviors compared to traditional web applications. To optimize traffic for AI applications and efficiently use GPU and TPU resources, Google Cloud announced new networking capabilities, such as the Cross-Cloud Network for data transfer and the Model as a Service Endpoint for AI inference applications. Additionally, Cloud Load Balancing now offers custom AI-aware load balancing to minimize inference latency and distribute traffic based on LLM-specific metrics, resulting in improved performance and reliability for AI applications.

**Tags:** *\#ai-applications,  \#generative-ai, \#cloud-networking*

### [Introducing Apple’s On-Device and Server Foundation Models](https://machinelearning.apple.com/research/introducing-apple-foundation-models)

**Site Name:** Apple Machine Learning Research

**Summary:** Apple introduced Apple Intelligence, a personal intelligence system integrated into iOS 18, iPadOS 18, and macOS Sequoia at the 2024 Worldwide Developers Conference. Apple Intelligence comprises multiple specialized generative models built for tasks like writing, prioritizing notifications, creating images, and simplifying interactions across apps. The on-device and server foundation models, part of a larger family of generative models by Apple, have been designed using responsible AI principles and trained with a focus on user privacy while optimizing for speed and efficiency. The models are fine-tuned for specific tasks through adapters, undergo thorough performance evaluations against open-source and commercial models, and are found to excel in instruction-following, safety, and helpfulness metrics.

**Tags:** *\#machine-learning, \#generative-ai, \#apple-intelligence, \#responsible-ai*

### [Understanding the Cost of Generative AI Models in Production](https://www.philschmid.de/cost-generative-ai)

**Site Name:** Philipp Schmid

**Summary:** The article discusses the total cost of ownership (TCO) for deploying Generative AI models in production, emphasizing that costs go beyond just raw compute pricing and also includes factors such as container services, networking, load balancing, autoscaling, and more. Hidden costs can impact TCO, with self-built solutions potentially being initially cheaper but requiring additional expenses for development time and maintenance, especially when hiring skilled professionals. The article suggests that opting for managed services with integrated support may be more cost-effective in the long run, as understanding the full cost of deploying Generative AI models is crucial for making informed decisions.

**Tags:** *\#generative-ai, \#tco, \#infra-costs", \#deployment-strategies, \#operational-efficiency*

### [What We Learned from a Year of Building with LLMs (Part I)](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/)

**Site Name:** O’Reilly Media

**Summary:** The article discusses key learnings from a year of building with Large Language Models (LLMs), focusing on their application in real-world scenarios and the growing investment in AI. The authors share crucial lessons on prompting techniques, structured input and output, retrieval-augmented generation, and the importance of workflows optimization. They emphasize the need for efficient evaluation and monitoring strategies, including simplifying annotation tasks and utilizing LLM-as-Judge for quality assessments. The authors also address challenges such as hallucinations, the effectiveness of reference-free evaluations, and the importance of guardrails for filtering undesirable outputs.

**Tags:** *\#ai, \#machine-learning, \#ai-engineering, \#llm*

### [situationalawareness](https://situational-awareness.ai/)

**Site Name:** Situational-Awareness

**Description:** None

**Summary:** The Decade Ahead” explores the rapid advancements in artificial intelligence, predicting that AGI (Artificial General Intelligence) could be achieved by 2027. It highlights the significant investments in computing power, security challenges, and the potential for superintelligence to surpass human capabilities. The discussion emphasizes the critical importance of managing these developments responsibly to avoid catastrophic outcomes and maintain global stability.

**Tags:** *\#agi, \#ai, \#ai-security*

### [Deploying A GPT-4o Model to Azure OpenAI Service](https://trailheadtechnology.com/deploying-a-gpt-4o-model-to-azure-openai-service/)

**Site Name:** Trailhead Technology Partners

**Description:** Azure OpenAI Service enables easy deployment of powerful language models like GPT-4o. This guide walks you through the process, from securing access and creating resources in the Azure portal to navigating the updated Azure AI Studio for model selection and configuration. The interactive playground allows for testing and fine-tuning, while secure API access ensures robust integration into your applications.

**Summary:** Azure OpenAI Service provides API access to powerful OpenAI language models like GPT-4o for tasks such as content generation, summarization, and code translation. The process of deploying a language model to an Azure OpenAI resource involves creating the necessary resource in the Azure portal and selecting and configuring models like GPT-4o via Azure AI Studio. Testing and fine-tuning the model's responses can be done in the interactive playground provided, and securing access to AI services is essential through the "

**Tags:** *\#azure, \#openai, \#llm, \#api, \#ai*

### [Why are most LLMs decoder-only?.](https://medium.com/@yumo-bai/why-are-most-llms-decoder-only-590c903e4789)

**Site Name:** Medium - Yumo Bai

**Description:** I came across this question during mentoring for DeltaHacks and could not come up with an answer that was persuasive enough for myself. So I did some digging and it turned out to be a fascinating…

**Summary:** The article delves deep into recent advancements in Large Language Models, exploring various model architectures such as Encoder-Only, Decoder-Only, and Encoder-Decoder models. It discusses the performance comparison between Causal Decoder (CD) and Encoder-Decoder (ED) models, highlighting key findings from a study on language model architecture and pre-training objectives. Additionally, the article touches on important factors like training cost, emergent abilities in LLMs, in-context learning from prompts, efficiency optimization, and the

**Tags:** *\#llm, \#encoder-decoder-models, \#ai-optimization", \#ai*

### [[2406.11903] A Survey of Large Language Models for Financial Applications: Progress, Prospects and Challenges](https://arxiv.org/abs/2406.11903)

**Site Name:** arXiv

**Description:** Recent advances in large language models (LLMs) have unlocked novel opportunities for machine learning applications in the financial domain. These models have demonstrated remarkable capabilities...

**Summary:** The article explores the use of large language models (LLMs) in the financial domain, highlighting their potential to revolutionize traditional practices and drive innovation by leveraging advanced technologies like contextual understanding, transfer learning flexibility, and emotion detection. It categorizes existing literature into key application areas such as linguistic tasks, sentiment analysis, financial time series, reasoning, and agent-based modeling, discussing specific methodologies like textual analysis and forecasting. The study also provides a collection of datasets, model assets, and codes for researchers and outlines

**Tags:** *\#llm, \#machine-learning, \#fin-ops, \#use-cases*

### [[2405.00332] A Careful Examination of Large Language Model Performance on Grade School Arithmetic](https://arxiv.org/abs/2405.00332)

**Site Name:** arXiv

**Summary:** The article investigates the performance of large language models (LLMs) on grade school arithmetic tasks, specifically examining dataset contamination and true reasoning ability. A new benchmark called Grade School Math 1000 (GSM1k) is introduced to compare LLM performance with an established benchmark (GSM8k), revealing accuracy drops and evidence of overfitting in certain model families. Analysis suggests that some models may have partially memorized the GSM8k dataset, impacting their performance on the GSM1k benchmark.

**Tags:** *\#llm, \#dataset-contamination, \#model-overfitting*

### [Researchers upend AI status quo by eliminating matrix multiplication in LLMs](https://arstechnica.com/information-technology/2024/06/researchers-upend-ai-status-quo-by-eliminating-matrix-multiplication-in-llms/)

**Site Name:** Ars Technica

**Description:** Researchers claim to have developed a new way to run AI language models more efficiently by eliminating matrix multiplication from the process. This fundamentally redesigns neural network operations that are currently accelerated by GPU chips. The findings, detailed in a recent preprint paper from researchers at the University of California Santa Cruz, UC Davis, LuxiTech, and Soochow University, could have deep implications for the environmental impact and operational costs of AI systems.

**Summary:** Researchers have developed a new approach to run AI models more efficiently by eliminating matrix multiplication, potentially reducing power consumption. This redesign in neural network operations challenges the current reliance on GPUs for high-speed matrix math, offering implications for lower environmental impact and operational costs. By utilizing ternary values and a MatMul-free architecture, the researchers achieved comparable performance to conventional models while reducing energy usage and memory consumption.

**Tags:** *\#ai, \#llm*

### [Machine Learning Mastery](https://machinelearningmastery.com)

**Site Name:** MachineLearningMastery.com

**Description:** Making Developers Awesome at Machine Learning

**Summary:** The site provides, blog articles, guides, and eBooks focused on learning about machine learning.

**Tags:** *\#data-science, \#machine-learning, \#ai*

### [Open challenges for AI engineering](https://simonwillison.net/2024/Jun/27/ai-worlds-fair/)

**Site Name:** Simon Willison

**Description:** I gave the opening keynote at the AI Engineer World’s Fair yesterday. I was a late addition to the schedule: OpenAI pulled out of their slot at the last minute, …

**Summary:** The article discusses the author's keynote at the AI Engineer World's Fair, where they highlighted advancements in the LLM space since the previous AI Engineer Summit 8 months ago. The author focused on breaking the GPT-4 barrier and discussed various models available in the space, emphasizing the need for responsible use and open challenges in AI engineering. They also touched on the AI trust crisis, prompt injection issues, and the concept of "slop" - unrequested and unreviewed AI-generated content.

**Tags:** *\#ai-engineering, \#llm, \#ai-trust, \#gtp4, #ai-responsible-use*

### [Build Rag With Llamaindex To Make LLM Answer About Yourself, Like in an Interview or About General InformationI](https://pub.towardsai.net/build-rag-with-llamaindex-to-make-llm-answer-about-yourself-like-in-interview-or-about-general-68bb2037f8b6?gi=d379a686b47c)

**Site Name:** Towards AI - Lakshmi Narayana Santha

**Description:** From the day ChatGPT was introduced, the whole NLP/AI ecosystem was changed and came up with numerous new techniques to integrate the LLMs into various fields and use-cases. One of those gems that…

**Summary:** The article discusses the implementation of a RAG (Retrieved Augmentation Generation) pipeline using Llamaindex for building chat applications with LLMs like Cohere. It explains the process of setting up the pipeline, loading documents, parsing text into nodes, obtaining vector embeddings, and using a chat engine with a retrieval strategy. The pipeline leverages Cohere for LLM and Qdrant for storing vector embeddings, allowing for personalized responses based on user queries. The article also provides code examples for

**Tags:** *\#nlp, \#ai, \#rag, \#chatbot

### [Build your own Large Language Model (LLM) From Scratch Using PyTorch](https://pub.towardsai.net/build-your-own-large-language-model-llm-from-scratch-using-pytorch-9e9945c24858?gi=a3b1cede2202)

**Site Name:** Towards AI - Milan Taman

**Description:** What will you achieve by the end of this post? You will be able to build and train a Large Language Model (LLM) by yourself while coding along with me. Although we’re building an LLM that translates…

**Summary:** The article provides a step-by-step guide to build and train an LLM named MalayGPT for text translation from English to Malay language. Starting with loading the dataset and creating a tokenizer, the article covers building the encoder, decoder, attention mechanisms, feedforward networks, and other components of the transformer model. Training and validation processes are demonstrated, highlighting the training loop and the translation function for new tasks. Finally, the article emphasizes the capability to create language models from scratch and mentions possibilities for further applications

**Tags:** *\#transformer, \#llm, \#translation, \#neural-network*

### [Meet Verba 1.0: Run State-of-the-Art RAG Locally with Ollama Integration and Open Source Models](https://www.marktechpost.com/2024/05/19/meet-verba-1-0-run-state-of-the-art-rag-locally-with-ollama-integration-and-open-source-models/?amp=)

**Site Name:** MarkTechPost

**Description:** Retrieval-augmented generation (RAG) is a cutting-edge technique in artificial intelligence that combines the strengths of retrieval-based approaches with generative models. This integration allows for creating high-quality, contextually relevant responses by leveraging vast datasets. RAG has significantly improved the performance of virtual assistants, chatbots, and information retrieval systems by ensuring that generated responses are accurate and contextually appropriate. The synergy of retrieval and generation enhances the user experience by providing detailed and specific information. One of the primary challenges in AI is delivering precise and contextually relevant information from extensive datasets. Traditional methods often need help maintaining the necessary context, leading

**Summary:** The article discusses the concept of Retrieval-Augmented Generation (RAG) in AI, which combines retrieval-based approaches with generative models to provide high-quality, contextually relevant responses leveraging vast datasets. Traditional AI methods often struggle to deliver precise and contextually appropriate information, leading to generic or inaccurate responses, highlighting the need for technologies like RAG. Weaviate has introduced Verba 1.0, a tool that bridges retrieval and generation processes using advanced techniques and models to enhance the accuracy and

**Tags:** *\#ai, \#rag*

### [What Is ChatGPT Doing … and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)

**Site Name:** writings Stephen Wolfram

**Description:** Stephen Wolfram explores the broader picture of what's going on inside ChatGPT and why it produces meaningful text. Discusses models, training neural nets, embeddings, tokens, transformers, language syntax.

**Summary:** The article delves into the intricate workings of ChatGPT, explaining how it uses neural networks and the transformer architecture to generate human-like text by predicting and adding one token at a time based on vast amounts of training data. It highlights the underlying process of embedding words into numerical vectors and employing attention mechanisms to manage sequences, ultimately leading to the model's ability to produce coherent and contextually appropriate continuations. Furthermore, it discusses the scientific and engineering principles that enable this, touching on the broader implications for understanding

**Tags:** *\#ai, \#chatgpt, \#machine-learning, \#neural-networks, \#llm*

### [Detecting hallucinations in large language models using semantic entropy](https://www.nature.com/articles/s41586-024-07421-0)

**Site Name:** Nature

**Description:** Large language model (LLM) systems, such as ChatGPT1 or Gemini2, can show impressive reasoning and question-answering capabilities but often ‘hallucinate’ false outputs and unsubstantiated answers.

**Summary:** Hallucinations in large language models (LLMs) pose significant problems due to generating content that is nonsensical or unfaithful to the source. Researchers propose using semantic entropy, which quantifies semantic uncertainties, to detect these hallucinations, commonly referred to as "confabulations" when models produce arbitrary and incorrect results. The proposed method outperforms current baseline techniques in detecting such confabulations, significantly improving answer accuracy by filtering out questions causing high semantic entropy, thereby revealing the crucial role

**Tags:** *\#llm, \#ai-reliability*

### [I Will Fucking Piledrive You If You Mention AI Again](https://ludic.mataroa.blog/blog/i-will-fucking-piledrive-you-if-you-mention-ai-again/?ck_subscriber_id=512830397)

**Site Name:** ludic mataroa blog

**Description:** The recent innovations in the AI space, most notably those such as GPT-4, obviously have far-reaching implications for society, ranging from the utopian eliminating of drudgery, to the dystopian damage to the livelihood of artists in a capitalist society, to existential threats to humanity itself.

**Summary:** The author, a data scientist, laments the current hype surrounding AI technologies like GPT-4, pointing out that many companies are focusing on AI initiatives without proper understanding or genuine need, often resulting in failed projects. They describe the industry as filled with incompetence and grift, where executives prioritize trendy AI implementations over foundational technological competencies, which ultimately hampers real innovation and problem-solving. The author warns that only those at the cutting edge or with clear, specific AI use cases should pursue these technologies,

**Tags:** *\#ai, \#gpt-4, \#data-science, \#machine-learning*

-----

## Cloud Computing and Infrastructure

**Categorical Tags:** *#cloud-computing, #cloud, #azure, #openai, #cloud-migration, #platform-engineering, #platform-strategies, #platform-integration, #internal-developer-platforms*

-----

### [The Modern Architect Playlist](https://www.youtube.com/playlist?list=PLsuboX68NN3DL-sYP16NRyaLFRvSexa_s)

**Site Name:** YouTube - Gregor Hohpe

**Summary:** The article titled "The Modern Architect - Gregor Hohpe's Videos"  a series of videos on YouTube created by architect Gregor Hohpe. It appears to focus on modern architectural design and related topics, showcasing Hohpe's expertise and perspective in the field. Viewers can access these videos on YouTube to learn more about contemporary architecture and design concepts.

**Tags:** *\#enterprise-architecture, \#enterprise-integration, \#platform-engineering, \#platform-strategies, \#software-architecture*

### [Blog - Private Cloud Compute: A new frontier for AI privacy in the cloud](https://security.apple.com/blog/private-cloud-compute/)

**Site Name:** Apple Security Research Blog

**Summary:** Apple introduces Private Cloud Compute (PCC) to enhance AI privacy in the cloud by extending the security and privacy of Apple devices into cloud processing, ensuring personal user data remains inaccessible to anyone other than the user. PCC is designed with stateless computation, enforceable guarantees, no privileged access, non-targetability, and verifiable transparency to safeguard user data during processing in the cloud, effectively challenging traditional cloud security models. To promote independent research and verification, Apple plans to make the software images of every production build of PCC publicly available, along with launching tools such as a PCC Virtual Research Environment and offering rewards through the Apple Security Bounty program for important research findings.

**Tags:** *\#private-cloud, \#ai-privacy, \#apple, \#data-protection, \#cloud-computing*

### [Platform as a Runtime - The Next Step in Platform Engineering](https://www.infoq.com/articles/platform-runtime-engineering/)

**Site Name:** InfoQ

**Description:** We need to take the concepts of platform engineering to the code level, reduce cognitive load, help simplify and accelerate software development, and allow for easy maintenance and platform upgrades.

**Summary:** The article discusses the importance of platform engineering beyond the traditional CI/CD pipeline, emphasizing the need to simplify code and automate integrations for faster development cycles. It explores how large and complex software systems can hinder innovation and offers insights into the challenges of maintaining standard practices across development teams. The concept of a Platform as a Runtime is introduced, aiming to reduce microservices footprint and manage a single platform version separate from business microservice lifecycle, promoting productivity and scalability.

**Tags:** *\#platform-engineering, \#devx, \#developer-productivity*

### [Data store decision tree - Azure Application Architecture Guide](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-decision-tree)

**Site Name:** Learn Microsoft

**Description:** Select an Azure data store for your application. View a graphical representation of choosing your data store.

**Summary:** The article discusses selecting an Azure data store for applications, with Azure offering various managed data storage solutions with different features and capabilities. It recommends evaluating each workload separately if the application consists of multiple workloads, as a complete solution may involve multiple data stores. The article provides guidance on choosing specialized storage based on vendor requirements and offers next steps for exploring Azure cloud storage solutions and services, storage options, and various data storage technologies.

**Tags:** *\#azure, \#azure-data-store, \#cloud*

### [Polyfill.io, BootCDN, Bootcss, Staticfile attack traced to 1 operator](https://www.bleepingcomputer.com/news/security/polyfillio-bootcdn-bootcss-staticfile-attack-traced-to-1-operator/)

**Site Name:** BleepingComputer

**Description:** The recent large scale supply chain attack conducted via multiple CDNs, namely Polyfill.io, BootCDN, Bootcss, and Staticfile that affected up to tens of millions of websites has been traced to a common operator.  Researchers discovered a public GitHub repository with leaked API keys helping them draw a conclusion.

**Summary:** Security researchers traced a large scale supply chain attack affecting tens of millions of websites to a common operator behind four CDNs: Polyfill.io, BootCDN, Bootcss, and Staticfile, by discovering exposed Cloudflare secret keys in a public GitHub repository.

The accidental exposure of Cloudflare keys enabled researchers to connect the supply chain attack involving all four CDNs to a single entity, indicating a wider ongoing attack since June 2023 according to MalwareHunterTeam.

The impact of the attack is

**Tags:** *\#cyber-security, \#cloud*

### [Building a Platform Team at a 153-Year-Old Company](https://thenewstack.io/building-a-platform-team-at-a-153-year-old-company/)

**Site Name:** The New Stack

**Description:** The digital transformation of Hellmann Worldwide Logistics, as described at PlatformCon 2024, carries lessons other organizations can adapt.

**Summary:** The article discussed the importance of taking a bespoke approach to platform engineering and how companies are investing time and money into customized open source software. The digital transformation journey of Hellmann Worldwide Logistics was highlighted, emphasizing the need for a unified platform team approach amidst technology stack challenges. The article also provided insights into building an effective internal developer platform by focusing on key values like transparency, trust, automation, and innovation, while also emphasizing the importance of incremental improvements and customer feedback in platform development.

**Tags:** *\#platform-engineering, \#internal-developer-platforms, \#digital-transformation, \#cloud-migration*

-----

## Cybersecurity

**Categorical Tags:**  *#cyber-security, #ai-security, #data-security*

-----

### [Uncensor any LLM with abliteration](https://huggingface.co/blog/mlabonne/abliteration)

**Site Name:** HuggingFace

**Summary:** The article discusses a technique called "abliteration" that can uncensor any third generation Llama-like models without retraining, by removing the built-in refusal mechanism. It explains the process of identifying and ablating the "refusal direction" within the model through data collection, mean difference calculation, and selection. The article provides code implementation details using Google Colab and TransformerLens library, along with the possibility of using weight orthogonalization for permanent uncensoring.

**Tags:** *\#llm, \#ai-security*

### [Is your AI workload secure?](https://medium.com/google-cloud/is-your-ai-workload-secure-c57189b4e6d1)

**Site Name:** Medium - Sita Lakshmi Sangameswaran - Google Cloud - Community

**Description:** In the stone-age of ML, we named our models like caveman counting rocks “model-001.ckpt,” “model-009.ckpt,” and so on, relying on rudimentary version control. Then with the advent of MLOps tools…

**Summary:** In the past, AI workflows were simpler with basic version control, but advancements like MLOps tools have improved organization and management of models. With the explosion of GenAI, the complexity and scale of AI deployments have increased, leading to new vulnerabilities and threats that exploit AI models.  Threats in the GenAI era range from jailbreaking to data poisoning, impacting confidentiality, integrity, and availability of AI assets. To address these concerns, a robust AI framework should incorporate secure-by

**Tags:** *\#ai-security, \#ai-model-development, \#ai-governance*

### [Web Check](https://web-check.xyz/check/about)

**Site Name:** Web Check

**Description:** Web Check is the all-in-one OSINT and security tool, for revealing the inner workings of any website

**Summary:** Web-Check is a versatile tool created by Alicia Sykes designed to gather extensive data on websites, aiding developers, system administrators, security researchers, and penetration testers. It provides detailed insights into various aspects of a site, such as security measures, server information, IP addresses, DNS records, SSL certificates, and more through numerous OSINT (Open-Source Intelligence) tasks. The tool is free and open-source, licensed under the MIT license, and can be self-hosted using platforms like Netlify

**Tags:** *\#tools, \#cyber-security, \#projects*

-----

## Development and Programming

**Categorical Tags:** *#programming, #python, #github-repo, #developer-productivity, #juypter-notebooks, #tools, #devx, #projects, #api, #learning, #skills-development, #personal-growth, #professional-development*

-----

### [GitHub - mshumer/ai-researcher](https://github.com/mshumer/ai-researcher)

**Site Name:** GitHub

**Summary:** The AI Researcher project on GitHub utilizes Claude 3 and SERPAPI to conduct detailed research on a topic by breaking it down into subtopics, generating individual reports for each subtopic, and combining them into a final comprehensive report. A new version named Gemini 1.5 Pro | YouTube Researcher has been added to analyze YouTube videos related to a specific topic to create a report based on their contents. Users can customize the behavior of the AI Research Assistant by modifying parameters such as the AI model, maximum tokens, and temperature value, but the accuracy of the generated reports depends on the AI performance and search results relevance.

**Tags:** *\#projects, \#claude, \#llm, \#serpapi, \#github-repo*

### [Platform as a Runtime - The Next Step in Platform Engineering](https://www.infoq.com/articles/platform-runtime-engineering/)

**Site Name:** InfoQ

**Description:** We need to take the concepts of platform engineering to the code level, reduce cognitive load, help simplify and accelerate software development, and allow for easy maintenance and platform upgrades.

**Summary:** The article discusses the importance of platform engineering beyond the traditional CI/CD pipeline, emphasizing the need to simplify code and automate integrations for faster development cycles. It explores how large and complex software systems can hinder innovation and offers insights into the challenges of maintaining standard practices across development teams. The concept of a Platform as a Runtime is introduced, aiming to reduce microservices footprint and manage a single platform version separate from business microservice lifecycle, promoting productivity and scalability.

**Tags:** *\#platform-engineering, \#devx, \#developer-productivity*

### [Developer Experience Is Still Developing](https://www.forrester.com/blogs/developer-experience-is-still-developing/)

**Site Name:** Forrester

**Description:** Forrester’s Q1 2024 Developer Experience Survey asks what would improve developer experience most. Get a preview of their responses here.

**Summary:** The article discusses the results of Forrester’s Q1 2024 Developer Experience Survey, highlighting a lack of strategy in many organizations to improve developer experience and a disconnect between leaders and developers on priorities for team improvements. It also explores the potential of generative AI tools like TuringBots in enhancing developer productivity, and addresses the communication gap between business leaders and developers, emphasizing the importance of explaining the "why" behind tasks and aligning with business outcomes to improve developer experience. Additionally, the article

**Tags:** *\#devx*

### [GitHub - dotenvx/dotenvx: a better dotenv–from the creator of `dotenv`](https://github.com/dotenvx/dotenvx)

**Site Name:** GitHub

**Description:** a better dotenv–from the creator of `dotenv`. Contribute to dotenvx/dotenvx development by creating an account on GitHub.

**Summary:** The article introduces various features and services offered by GitHub, such as automating workflows, managing packages, finding and fixing vulnerabilities, accessing instant development environments, writing better code with AI, managing code changes, planning and tracking work, and collaborating outside of code through discussions. It also highlights GitHub's initiatives like GitHub Sponsors for funding open source developers and The ReadME Project for community articles. Moreover, GitHub offers an enterprise platform that is AI-powered, and users can sign up to access these features and services

**Tags:** *\#tools, \#developer-productivity, \#devx, \#github-repo, \#projects*

### [4 keys to writing modern Python](https://www.infoworld.com/article/3648061/4-keys-to-writing-modern-python.html)

**Site Name:** InfoWorld

**Description:** If you want to write Python code that takes advantage of the language's newest and most powerful features, here are four areas to explore.

**Summary:** This article discusses four key areas for writing modern Python code: leveraging type hinting for better code analysis, exploring virtual environments and package management tools like Pyenv and Poetry, understanding new Python syntax additions like pattern matching and the walrus operator, and the importance of testing using the Pytest framework and code coverage tools to ensure better code quality in modern Python projects. These innovations and practices aim to help developers make the most of Python's latest features and capabilities for more efficient and maintainable coding practices in

**Tags:** *\#python*

### [GitHub - Doriandarko/claude-engineer](https://github.com/Doriandarko/claude-engineer)

**Site Name:** GitHub

**Description:** Claude Engineer is an interactive command-line interface (CLI) that leverages the power of Anthropic's Claude-3.5-Sonnet model to assist with software development tasks. This tool combines the capabilities of a large language model with practical file system operations and web search functionality.

**Summary:** Claude Engineer is a CLI tool that utilizes Anthropic's Claude-3.5-Sonnet model to aid in software development tasks by combining a large language model with file system operations and web search capabilities. Its features include interactive chat interface, file system operations, web search using Tavily API, syntax highlighting, project structure management, and code analysis. To install Claude Engineer, clone the repository, install dependencies, and set up your Anthropic and Tavily API keys within the script.

**Tags:** *\#tools, \#claude, \#anthropic, \#api, \#github-repo, \#projects*

### [Why we no longer use LangChain for building our AI agents](https://www.octomind.dev/blog/why-we-no-longer-use-langchain-for-building-our-ai-agents)

**Site Name:** octomind.dev

**Description:** When abstractions do more harm than good - lessons learned using LangChain in production and what we should’ve done instead

**Summary:** The article discusses Octomind's transition from using the LangChain framework for AI agents with multiple LLMs to a new approach utilizing modular building blocks for end-to-end tests in Playwright. Issues with LangChain's high-level abstractions led to code complexity, difficulty understanding, and decreased productivity for the team. The decision to move away from frameworks like LangChain to a more flexible and simplified approach using building blocks has allowed the team to develop faster and with less friction, ultimately improving their workflow and

**Tags:** *\#ai, \#langchain, \#tools*

### [GitHub - squaredtechnologies/thread: AI-Powered Jupyter Notebook built using React](https://github.com/squaredtechnologies/thread)

**Site Name:** GitHub

**Description:** AI-Powered Jupyter Notebook built using React. Contribute to squaredtechnologies/thread development by creating an account on GitHub.

**Summary:** Thread is a Jupyter alternative that integrates an AI copilot into your Jupyter Notebook editing experience.  Best of all, Thread runs locally and can be used for free with Ollama or your own API key.

**Tags:** *\#github-repo, \#tools, \#juypter-notebooks, \#projects*

### [Every Way To Get Structured Output From LLMs](https://www.boundaryml.com/blog/structured-output-from-llms)

**Site Name:** boundaryml.com

**Description:** A survey of every framework for extracting structured output from LLMs, and how they compare.

**Summary:** The article discusses the challenges and solutions related to obtaining structured output, specifically JSON, from Large Language Models (LLMs). It provides a comparative analysis of various frameworks such as BAML, Instructor, and TypeChat, each offering different methods to handle or prevent malformed JSON and allow prompt customization. A preference is shown for frameworks that parse malformed JSON swiftly and accurately, ensuring both speed and flexibility, while others apply constraints to token generation, which is reliable but limited to self-hosted models.

**Tags:** *\#llm, \#tools, \#json*

### [My 5 favorite ways of keeping the technical axe sharp - same stuff, different day](https://samestuffdifferentday.net/2024/06/27/learning-part2/)

**Site Name:** same stuff, different day

**Description:** The one where I talk about keeping my tech skills sharp.

**Summary:** The article discusses five favorite ways to keep technical skills sharp, including working on side projects to experiment with new language features, practicing with Koans to find enlightenment in programming, engaging in coding Katas like Gilded Rose and Vending Machine, researching for weekly interesting links posts, and consuming video content from sources like Pluralsight and Udemy to stay updated with new technologies. The author emphasizes the importance of continuously updating technical skills due to the rapid pace of change in technology, advocating for proactive learning

**Tags:** *\#learning", \#skills-development", \#personal-growth, \#professional-development*
