# Artificial Intelligence: Learning Resources & Tools

> A curated collection of resources for learning AI, machine learning, large language models, generative AI, agents, automation, and practical applications.

**Audience:** Beginners, marketers, developers, researchers, and AI enthusiasts.  
**Last organized:** October 2026  
**Note:** Tools, model versions, pricing, and URLs change. Links are provided for exploration and are not all independently verified.

## Contents

- [How to Use This Guide](#how-to-use-this-guide)
- [Start Here](#start-here)
- [AI Foundations & Visual Explainers](#ai-foundations--visual-explainers)
- [Machine Learning & Deep Learning](#machine-learning--deep-learning)
- [LLMs & Model Ecosystem](#llms--model-ecosystem)
- [Prompt Engineering](#prompt-engineering)
- [LLM Playgrounds & Evaluation](#llm-playgrounds--evaluation)
- [Retrieval-Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
- [AI Agents & Orchestration](#ai-agents--orchestration)
- [MCP, A2A & Agent Protocols](#mcp-a2a--agent-protocols)
- [AI Automation & RPA](#ai-automation--rpa)
- [AI Coding & App Building](#ai-coding--app-building)
- [Multimodal AI: Images, Video & Audio](#multimodal-ai-images-video--audio)
- [Voice AI & Speech](#voice-ai--speech)
- [AI Safety, Security & Responsible AI](#ai-safety-security--responsible-ai)
- [Research Papers](#research-papers)
- [Courses, Tutorials & YouTube](#courses-tutorials--youtube)
- [AI for SEO, AEO & GEO](#ai-for-seo-aeo--geo)
- [Case Studies & Industry Applications](#case-studies--industry-applications)
- [Communities, News & Open-Source Collections](#communities-news--open-source-collections)
- [Contributing](#contributing)

---

## How to Use This Guide

This repository is a **learning guide and resource directory**. Each topic begins with a plain-English explanation, a practical example and links for deeper study. You do not need to open every link.

| Goal | Read first | Practical exercise |
|---|---|---|
| Learn AI basics | [Foundations](#ai-foundations--visual-explainers) | Explain AI, ML and LLMs in your own words |
| Improve prompts | [Prompt Engineering](#prompt-engineering) | Test the same prompt across two models |
| Answer from documents | [RAG](#retrieval-augmented-generation-rag) | Build a document Q&A prototype |
| Automate tasks | [Automation](#ai-automation--rpa) | Create a weekly report workflow |
| Build AI assistants | [Agents](#ai-agents--orchestration) | Connect an agent to one safe tool |
| Improve AI search visibility | [AI for SEO](#ai-for-seo-aeo--geo) | Audit a page and track AI mentions |

### Essential Terms

| Term | Meaning | Example |
|---|---|---|
| Token | Piece of text processed by a model | A word may use several tokens |
| Embedding | Numeric representation of meaning | Find similar documents |
| Transformer | Neural-network architecture using attention | Many modern LLMs |
| Context window | Information a model can process in one request | Document plus question |
| Inference | Running a trained model | Generating a chatbot reply |
| Fine-tuning | Additional training for a task | Adapt model behavior |
| RAG | Retrieve source material before answering | Ask questions about PDFs |
| Vector database | Searchable storage for embeddings | Find relevant passages |
| Tool calling | Requesting an external function | Query a database |
| MCP | Standard connection to tools and data | Assistant reads files |
| A2A | Communication between agents | Specialist agents coordinate |
| Hallucination | Plausible but unsupported output | Invented citation |
| Evaluation | Systematic testing of outputs | Score 50 answers |

---

## Start Here

**Purpose:** Follow a beginner-to-advanced path instead of opening every link at once.

**Learning path:** Understand AI and ML → learn how LLMs process tokens → practice prompting → build a document Q&A app → test quality → explore agents and automation.

**Practice:** Compare two models on the same five questions. Note accuracy, speed, evidence and mistakes.


A suggested learning path: understand the basics, explore models, learn prompting, build RAG applications, then move into agents, evaluation, and deployment.

- **[Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)** — Resource related to start here; review its documentation and suitability.
- **[Elements of AI](https://www.elementsofai.com/)** — Resource related to start here; review its documentation and suitability.
- **[Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)** — Code repository; inspect its README, license and recent activity.
- **[Google AI Essentials](https://grow.google/ai-essentials/)** — Resource related to start here; review its documentation and suitability.
- **[Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)** — Model, tutorial or project page on Hugging Face.
- **[DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/)** — Resource related to start here; review its documentation and suitability.

## AI Foundations & Visual Explainers

**AI** is software performing tasks associated with human intelligence. **Machine learning** learns patterns from examples. **Deep learning** uses multilayer neural networks. **Generative AI** creates text, images, audio or other content.

**How an LLM works:** It splits text into tokens, processes their relationships through a neural network and predicts output tokens. A fluent answer can still be wrong.

**Try:** Explore a tokenizer and a transformer visualizer, then explain attention in your own words. This section also includes some advanced tools and industry resources.


- **[ig.ft.com](https://ig.ft.com/generative-ai/)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[informationisbeautiful.net](https://informationisbeautiful.net/visualizations/the-rise-of-generative-ai-large-language-models-llms-like-chatgpt/)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[platform.openai.com](https://platform.openai.com/tokenizer)** — OpenAI API documentation or interactive tool.
- **[semianalysis.com](https://semianalysis.com/)** — Technical analysis of AI infrastructure and industry.
- **[poloclub.github.io](https://poloclub.github.io/transformer-explainer/)** — Interactive transformer explainer.
- **[bbycroft.net](https://bbycroft.net/llm)** — Interactive visualization of LLM architecture.
- **[playground.tensorflow.org](https://playground.tensorflow.org/)** — Interactive neural network visualizer.
- **[arena.ai](https://arena.ai/text/side-by-side)** — Compare model outputs and evaluations.
- **[llm-stats.com](https://llm-stats.com/models/compare)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[platform.claude.com](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)** — Official Claude developer documentation.
- **[platform.claude.com](https://platform.claude.com/docs/en/models/overview)** — Official Claude developer documentation.
- **[openai.com](https://openai.com/index/introducing-gpt-5-5/)** — OpenAI research or product information; check the publication date.
- **[developers.openai.com](https://developers.openai.com/api/docs/guides/prompt-engineering?api-mode=responses)** — OpenAI developer documentation.
- **[blog.google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[notebook.google.com](https://notebook.google.com/)** — Explore and summarize provided source material.
- **[ollama.com](https://ollama.com/)** — Run supported AI models locally.
- **[lmstudio.ai](https://lmstudio.ai/)** — Run and test language models on your computer.
- **[artificialanalysis.ai](https://artificialanalysis.ai/)** — Model benchmark and performance comparisons.
- **[huggingface.co](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro)** — Model, tutorial or project page on Hugging Face.
- **[code.claude.com](https://code.claude.com/docs/en/workflows)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[anthropic.com](https://www.anthropic.com/research/building-effective-agents)** — Anthropic research or product documentation.
- **[ibm.com](https://www.ibm.com/think/topics/multiagent-system)** — Introductory explanation of the linked AI concept.
- **[ibm.com](https://www.ibm.com/think/topics/ai-agent-orchestration)** — Introductory explanation of the linked AI concept.
- **[docs.langchain.com](https://docs.langchain.com/)** — Documentation for LLM applications and agents.
- **[academy.langchain.com](https://academy.langchain.com/)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[github.com](https://github.com/crewAIInc/crewAI)** — Code repository; inspect its README, license and recent activity.
- **[freecodecamp.org](https://www.freecodecamp.org/news/a-beginners-guide-to-automation-with-n8n)** — Resource related to ai foundations & visual explainers; review its documentation and suitability.
- **[ibm.com](https://www.ibm.com/think/topics/rpa)** — Introductory explanation of the linked AI concept.
- **[github.com](https://github.com/Hannibal046/Awesome-LLM)** — Code repository; inspect its README, license and recent activity.
- **[youtu.be](https://youtu.be/mEsleV16qdo?si=VWkhDS5Ak5Srqeis)** — YouTube video; topic and title not independently verified.

## Machine Learning & Deep Learning

**Key ideas:** Datasets contain examples; features are inputs; labels are expected outputs; training adjusts a model; inference uses it; overfitting means poor performance on new examples.

**Example:** Predict customer churn using past customer data. Test on held-out customers, not only the examples used for training.

**Learn:** Classification, regression, train/test splits, loss, gradient descent, precision, recall and neural networks.


- **[TensorFlow](https://www.tensorflow.org/)** — Deep-learning framework for training and deploying models.
- **[PyTorch](https://pytorch.org/)** — Popular deep-learning framework.
- **[Scikit-learn](https://scikit-learn.org/stable/)** — Python library for classical machine learning.
- **[Google ML Glossary](https://developers.google.com/machine-learning/glossary)** — Definitions of common machine-learning concepts.
- **[Distill](https://distill.pub/)** — Visual explanations of machine-learning research.
- **[3Blue1Brown Neural Networks](https://www.3blue1brown.com/topics/neural-networks)** — Visual lessons on neural networks.
- **[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)** — Resource related to machine learning & deep learning; review its documentation and suitability.

## LLMs & Model Ecosystem

**LLM:** A large language model that processes and generates language. Models differ in quality, speed, price, context length, supported tools and privacy terms.

**Hosted vs local:** Hosted models run through a provider; supported open-weight models can run on your own machine under their license.

**Compare:** Use your own test questions and check factual accuracy, latency, cost, output format and tool support.


- **[Hugging Face Models](https://huggingface.co/models)** — Explore model cards and licenses.
- **[OpenAI Models](https://platform.openai.com/docs/models)** — Official model documentation.
- **[Anthropic Models](https://docs.anthropic.com/en/docs/about-claude/models/overview)** — Official Anthropic documentation.
- **[Google Gemini Models](https://ai.google.dev/gemini-api/docs/models)** — Resource related to llms & model ecosystem; review its documentation and suitability.
- **[Meta Llama](https://www.llama.com/)** — Resource related to llms & model ecosystem; review its documentation and suitability.
- **[Mistral AI](https://docs.mistral.ai/)** — Resource related to llms & model ecosystem; review its documentation and suitability.
- **[DeepSeek](https://github.com/deepseek-ai)** — Code repository; inspect its README, license and recent activity.
- **[Qwen](https://github.com/QwenLM)** — Code repository; inspect its README, license and recent activity.
- **[Ollama](https://ollama.com/)** — Run supported models locally.
- **[LM Studio](https://lmstudio.ai/)** — Desktop tool for local language models.
- **[vLLM](https://docs.vllm.ai/)** — Efficient LLM serving engine.
- **[llama.cpp](https://github.com/ggml-org/llama.cpp)** — Code repository; inspect its README, license and recent activity.
- **[Artificial Analysis](https://artificialanalysis.ai/)** — Model benchmark and performance comparisons.

## Prompt Engineering

**Prompt engineering** is writing instructions that clearly specify a task, context, constraints and output format.

**Example:** Instead of “summarize this,” say “Summarize these support tickets in five bullets, group repeated issues, show counts and say unknown where evidence is missing.”

**Test:** Missing information, ambiguous requests, conflicting source text and long inputs. A good prompt reduces errors but cannot guarantee correctness.


- **[OpenAI Prompting Guide](https://platform.openai.com/docs/guides/prompt-engineering)** — OpenAI API documentation or interactive tool.
- **[Anthropic Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)** — Official Anthropic documentation.
- **[Google Prompt Design](https://ai.google.dev/gemini-api/docs/prompting-strategies)** — Resource related to prompt engineering; review its documentation and suitability.
- **[Prompt Engineering Guide](https://www.promptingguide.ai/)** — Community prompt-design tutorials.
- **[Learn Prompting](https://learnprompting.org/)** — Resource related to prompt engineering; review its documentation and suitability.
- **[OpenAI Cookbook](https://cookbook.openai.com/)** — Practical API examples.
- **[Anthropic Interactive Prompt Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)** — Code repository; inspect its README, license and recent activity.

## LLM Playgrounds & Evaluation

**Playgrounds** let you try models and prompts. **Evaluation** tests whether outputs meet your requirements.

**Metrics:** Task success, factual accuracy, citation correctness, structured-output validity, latency, cost and safety.

**Example:** Test 50 support questions against a known answer key and compare model versions using the same questions.


- **[docs.litellm.ai](https://docs.litellm.ai/docs/tutorials/first_playground)** — Resource related to llm playgrounds & evaluation; review its documentation and suitability.
- **[huggingface.co](https://huggingface.co/playground)** — Model, tutorial or project page on Hugging Face.
- **[github.com](https://github.com/nat/openplayground)** — Code repository; inspect its README, license and recent activity.
- **[retool.com](https://retool.com/utilities/largelanguagemodel-playground)** — Resource related to llm playgrounds & evaluation; review its documentation and suitability.
- **[freellmplayground.com](https://freellmplayground.com/)** — Resource related to llm playgrounds & evaluation; review its documentation and suitability.
- **[langfuse.com](https://langfuse.com/docs/prompt-management/features/playground)** — Resource related to llm playgrounds & evaluation; review its documentation and suitability.
- **[promptfoundry.ai](https://www.promptfoundry.ai/llm-playground)** — Resource related to llm playgrounds & evaluation; review its documentation and suitability.

- **[Google AI Studio](https://aistudio.google.com/)** — Try Gemini models and prototype prompts.
- **[OpenAI Playground](https://platform.openai.com/playground)** — OpenAI API documentation or interactive tool.
- **[Hugging Face Chat](https://huggingface.co/chat/)** — Model, tutorial or project page on Hugging Face.
- **[Chatbot Arena](https://arena.ai/)** — Compare model outputs and evaluations.
- **[LangSmith Evaluation](https://docs.langchain.com/langsmith/evaluation)** — Documentation for LLM applications and agents.
- **[Langfuse](https://langfuse.com/)** — Monitor and evaluate LLM applications.
- **[Ragas](https://docs.ragas.io/)** — Evaluate RAG retrieval and answers.
- **[DeepEval](https://github.com/confident-ai/deepeval)** — Framework for testing LLM applications.
- **[Promptfoo](https://www.promptfoo.dev/)** — Prompt and model testing, including security checks.
- **[HELM](https://crfm.stanford.edu/helm/)** — Resource related to llm playgrounds & evaluation; review its documentation and suitability.
- **[EleutherAI LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)** — Code repository; inspect its README, license and recent activity.

## Retrieval-Augmented Generation (RAG)

**RAG** retrieves relevant information from documents or databases and provides it to a model before answering.

**Typical process:** Load documents → split into chunks → create embeddings → index → retrieve relevant passages → generate an answer → verify citations.

**Example:** A helpdesk assistant answers from current product manuals. Common failures include missing source material, weak retrieval and unsupported answers. RAG does not retrain the underlying model.


- **[pinecone.io](https://www.pinecone.io/)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[llamaindex.ai](https://www.llamaindex.ai/)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[langchain.com](https://www.langchain.com/)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[promptingguide.ai](https://www.promptingguide.ai/agents/function-calling)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[ibm.com](https://www.ibm.com/think/topics/retrieval-augmented-generation)** — Introductory explanation of the linked AI concept.

- **[Google Cloud RAG Overview](https://cloud.google.com/use-cases/retrieval-augmented-generation)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[LlamaIndex Docs](https://docs.llamaindex.ai/)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[LangChain RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.
- **[Chroma](https://docs.trychroma.com/)** — Vector database for embeddings.
- **[Weaviate](https://weaviate.io/developers/weaviate)** — Vector database and hybrid search.
- **[Qdrant](https://qdrant.tech/documentation/)** — Vector search database.
- **[Milvus](https://milvus.io/docs)** — Open-source vector database.
- **[FAISS](https://github.com/facebookresearch/faiss)** — Library for vector similarity search.
- **[Sentence Transformers](https://sbert.net/)** — Create text embeddings for semantic search.
- **[RAGAS Evaluation](https://docs.ragas.io/)** — Resource related to retrieval-augmented generation (rag); review its documentation and suitability.

## AI Agents & Orchestration

**Agent:** A system that can decide which tools to call and what step to take next. **Workflow:** A more predictable sequence of predefined steps.

**Example:** A research assistant searches approved sources, compares findings and drafts a report. Require human approval before publishing or sending anything.

**Check:** Completion rate, unnecessary tool calls, loops, security, cost and recovery from failures.


- **[claude.com](https://claude.com/product/cowork)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[claude.com](https://claude.com/claude-in-chrome)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[platform.claude.com](https://platform.claude.com/docs/en/agents-and-tools/tool-use/computer-use-tool)** — Official Claude developer documentation.
- **[n8n.io](https://n8n.io/)** — Workflow automation tool or tutorial.
- **[AI Workflow Automation Software & Tools | Make](http://make.com/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[zapier.com](https://zapier.com/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[crewai.com](https://crewai.com/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[lindy.ai](https://www.lindy.ai/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[relevanceai.com](https://relevanceai.com/)** — Resource related to ai agents & orchestration; review its documentation and suitability.

- **[Anthropic Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)** — Anthropic research or product documentation.
- **[OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[LangGraph](https://docs.langchain.com/oss/python/langgraph/overview)** — Documentation for LLM applications and agents.
- **[CrewAI](https://docs.crewai.com/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[AutoGen](https://github.com/microsoft/autogen)** — Code repository; inspect its README, license and recent activity.
- **[Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[Google Agent Development Kit](https://google.github.io/adk-docs/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[Agno](https://docs.agno.com/)** — Resource related to ai agents & orchestration; review its documentation and suitability.
- **[Kaggle Agents Whitepaper](https://www.kaggle.com/whitepaper-agents)** — Resource related to ai agents & orchestration; review its documentation and suitability.

## MCP, A2A & Agent Protocols

**MCP (Model Context Protocol)** standardizes connections between AI applications and tools or data. **A2A (Agent2Agent)** supports communication between separate agents.

**Example:** An assistant reads calendar events through an MCP connection; a travel agent coordinates with another specialist agent through an agent-to-agent protocol.

**Security:** Verify connectors, limit permissions and treat retrieved content as untrusted data.


- **[modelcontextprotocol.io](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.
- **[platform.claude.com](https://platform.claude.com/docs/en/agents-and-tools/mcp-connector)** — Official Claude developer documentation.
- **[github.com](https://github.com/modelcontextprotocol)** — Code repository; inspect its README, license and recent activity.
- **[aaif.io](https://aaif.io/)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.
- **[anthropic.com](https://www.anthropic.com/news/model-context-protocol)** — Anthropic research or product documentation.
- **[ibm.com](https://www.ibm.com/think/topics/model-context-protocol)** — Introductory explanation of the linked AI concept.
- **[anthropic.com](https://www.anthropic.com/research/code-execution-with-mcp)** — Anthropic research or product documentation.
- **[dev.to](https://dev.to/pockit_tools/mcp-vs-a2a-the-complete-guide-to-ai-agent-protocols-in-2026-30li)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.

- **[MCP Documentation](https://modelcontextprotocol.io/)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.
- **[MCP Specification](https://modelcontextprotocol.io/specification)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.
- **[MCP Servers](https://github.com/modelcontextprotocol/servers)** — Code repository; inspect its README, license and recent activity.
- **[Google A2A Protocol](https://a2a-protocol.org/)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.
- **[A2A GitHub](https://github.com/a2aproject/A2A)** — Code repository; inspect its README, license and recent activity.
- **[Agentic AI Foundation](https://aaif.io/)** — Resource related to mcp, a2a & agent protocols; review its documentation and suitability.

## AI Automation & RPA

**Automation** runs tasks based on triggers and rules. **RPA** often interacts with user interfaces; API automation communicates directly with services.

**Example:** Every Monday, collect analytics metrics, calculate weekly changes, draft a summary and send it for approval.

**Build reliably:** Add retries, logging, error alerts, access controls and human review for important decisions.


- **[n8n](https://n8n.io/)** — Build automation workflows with integrations.
- **[n8n Templates](https://n8n.io/workflows/)** — Workflow automation tool or tutorial.
- **[Make](https://www.make.com/)** — Visual automation platform.
- **[Zapier](https://zapier.com/)** — Automate actions across connected apps.
- **[Pipedream](https://pipedream.com/)** — API and event-driven automation.
- **[Activepieces](https://www.activepieces.com/)** — Resource related to ai automation & rpa; review its documentation and suitability.
- **[Node-RED](https://nodered.org/)** — Resource related to ai automation & rpa; review its documentation and suitability.
- **[IBM Introduction to RPA](https://www.ibm.com/think/topics/rpa)** — Introductory explanation of the linked AI concept.

## AI Coding & App Building

**AI-assisted coding** uses a model to write, explain, test or refactor code. **Vibe coding** describes building by iterating on natural-language instructions.

**Beginner project:** Build a small question-answer app with input validation, loading state and error handling.

**Important:** Review generated code, protect API keys, inspect dependencies and test before deployment.


- **[cursor.com](https://cursor.com/)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[bolt.new](https://bolt.new/)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[lovable.dev](https://lovable.dev/)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[replit.com](https://replit.com/)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[v0.app](https://v0.app/)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[devin.ai](https://devin.ai/desktop)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[code.claude.com](https://code.claude.com/docs/en/overview)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[github.com](https://github.com/features/copilot)** — Code repository; inspect its README, license and recent activity.
- **[x.ai](https://x.ai/)** — Resource related to ai coding & app building; review its documentation and suitability.
- **[openai.com](https://openai.com/codex/)** — OpenAI research or product information; check the publication date.

- **[Aider](https://aider.chat/)** — AI pair-programming from the terminal.
- **[Continue](https://www.continue.dev/)** — Open-source coding assistant.
- **[Cline](https://github.com/cline/cline)** — AI coding agent extension.
- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)** — Code repository; inspect its README, license and recent activity.
- **[Streamlit](https://streamlit.io/)** — Build Python web apps.
- **[Gradio](https://www.gradio.app/)** — Build simple interfaces for AI demos.
- **[Hugging Face Spaces](https://huggingface.co/spaces)** — Host and share interactive ML demos.

## Multimodal AI: Images, Video & Audio

**Multimodal AI** can process or generate more than one media type, including images, video, audio and text.

**Example workflow:** Storyboard → generate visuals → edit → narrate → caption → review.

**Before publishing:** Check licensing, consent, accuracy and applicable disclosure requirements.


- **[docs.midjourney.com](https://docs.midjourney.com/hc/en-us)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[kling.ai](https://kling.ai/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[jimeng.com](https://jimeng.com/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[deepmind.google](https://deepmind.google/models/veo/)** — Google DeepMind model or research information.
- **[runway.com](https://runway.com/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[deepmind.google](https://deepmind.google/models/gemini-image/)** — Google DeepMind model or research information.
- **[bfl.ai](https://bfl.ai/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[ideogram.ai](https://ideogram.ai/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[elevenlabs.io](https://elevenlabs.io/)** — AI voice and audio tools.
- **[suno.com](https://suno.com/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[udio.com](https://www.udio.com/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.

- **[Hugging Face Diffusers](https://huggingface.co/docs/diffusers/)** — Model, tutorial or project page on Hugging Face.
- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI)** — Visual workflows for image generation.
- **[Stable Diffusion](https://stability.ai/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.
- **[Google DeepMind Models](https://deepmind.google/models/)** — Google DeepMind model or research information.
- **[Adobe Firefly](https://firefly.adobe.com/)** — Resource related to multimodal ai: images, video & audio; review its documentation and suitability.

## Voice AI & Speech

**STT** converts speech to text. **TTS** converts text to speech. A **voice agent** combines listening, reasoning and spoken responses.

**Example:** A booking assistant transcribes a request, checks approved availability, asks for confirmation and speaks the result.

**Evaluate:** Latency, transcription errors, interruptions, accents, privacy and handoff to a person.


- **[elevenlabs.io](https://elevenlabs.io/conversational-ai)** — AI voice and audio tools.
- **[deepgram.com](https://deepgram.com/learn/voice-ai-explained)** — Resource related to voice ai & speech; review its documentation and suitability.
- **[github.com](https://github.com/openai/whisper)** — Code repository; inspect its README, license and recent activity.
- **[hume.ai](https://www.hume.ai/)** — Resource related to voice ai & speech; review its documentation and suitability.
- **[sesame.com](https://www.sesame.com/)** — Resource related to voice ai & speech; review its documentation and suitability.
- **[developers.openai.com](https://developers.openai.com/api/docs/guides/conversation-state?api-mode=responses)** — OpenAI developer documentation.

- **[OpenAI Speech to Text](https://platform.openai.com/docs/guides/speech-to-text)** — OpenAI API documentation or interactive tool.
- **[OpenAI Text to Speech](https://platform.openai.com/docs/guides/text-to-speech)** — OpenAI API documentation or interactive tool.
- **[Whisper GitHub](https://github.com/openai/whisper)** — Speech-to-text model repository.
- **[Coqui TTS](https://github.com/coqui-ai/TTS)** — Code repository; inspect its README, license and recent activity.
- **[Pipecat](https://github.com/pipecat-ai/pipecat)** — Framework for real-time voice agents.
- **[LiveKit Agents](https://docs.livekit.io/agents/)** — Real-time voice agent infrastructure.

## AI Safety, Security & Responsible AI

**Risks:** Hallucinations, prompt injection, sensitive-data leaks, bias, unsafe tool actions and misleading confidence.

**Example:** A webpage tells an assistant to ignore its instructions. That webpage is untrusted content, not an authorized command.

**Controls:** Least-privilege permissions, output checks, redaction, audit logs, evaluations and human approval for consequential actions.


- **[OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)** — Common security risks for LLM applications.
- **[NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)** — Framework for managing AI risk.
- **[MITRE ATLAS](https://atlas.mitre.org/)** — Knowledge base of attacks against AI systems.
- **[Google Secure AI Framework](https://saif.google/)** — Resource related to ai safety, security & responsible ai; review its documentation and suitability.
- **[AI Incident Database](https://incidentdatabase.ai/)** — Resource related to ai safety, security & responsible ai; review its documentation and suitability.
- **[Stanford AI Index](https://hai.stanford.edu/ai-index)** — Resource related to ai safety, security & responsible ai; review its documentation and suitability.
- **[Anthropic Responsible Scaling Policy](https://www.anthropic.com/responsible-scaling-policy)** — Anthropic research or product documentation.
- **[Hugging Face Model Cards](https://huggingface.co/docs/hub/model-cards)** — Model, tutorial or project page on Hugging Face.

## Research Papers

**Why read papers:** They explain how methods work, what was tested and where results may fail. A preprint is not necessarily peer-reviewed.

**How to read:** Abstract → problem → method → experiments → limitations → replication or code.

**Suggested order:** Transformers, pretraining, instruction tuning, retrieval, tool use, fine-tuning and efficiency.


- **[arxiv.org](https://arxiv.org/abs/1706.03762)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2201.11903)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2005.14165)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2402.07927)** — Research paper or preprint; check abstract and limitations.
- **[LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2401.01313)** — Research paper or preprint; check abstract and limitations.
- **[genai.owasp.org](https://genai.owasp.org/llm-top-10-2025/llm01-prompt-injection)** — Resource related to research papers; review its documentation and suitability.
- **[sbert.net](https://sbert.net/)** — Resource related to research papers; review its documentation and suitability.
- **[arxiv.org](https://arxiv.org/abs/2006.11239)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2112.10752)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2303.07909)** — Research paper or preprint; check abstract and limitations.
- **[arxiv.org](https://arxiv.org/abs/2302.05543)** — Research paper or preprint; check abstract and limitations.
- **[huggingface.co](https://huggingface.co/docs/diffusers/stable_diffusion)** — Model, tutorial or project page on Hugging Face.

- **[BERT](https://arxiv.org/abs/1810.04805)** — Research paper on bidirectional language pretraining.
- **[Retrieval-Augmented Generation](https://arxiv.org/abs/2005.11401)** — Original paper on retrieval-backed text generation.
- **[InstructGPT](https://arxiv.org/abs/2203.02155)** — Research on instruction following and human feedback.
- **[Direct Preference Optimization](https://arxiv.org/abs/2305.18290)** — Research on preference-based alignment.
- **[ReAct](https://arxiv.org/abs/2210.03629)** — Research on reasoning with tool actions.
- **[Toolformer](https://arxiv.org/abs/2302.04761)** — Research on learning to use tools.
- **[Lost in the Middle](https://arxiv.org/abs/2307.03172)** — Study of long-context retrieval weaknesses.
- **[QLoRA](https://arxiv.org/abs/2305.14314)** — Memory-efficient fine-tuning method.
- **[FlashAttention](https://arxiv.org/abs/2205.14135)** — Efficient attention computation.
- **[Papers with Code](https://paperswithcode.com/)** — Resource related to research papers; review its documentation and suitability.
- **[arXiv AI](https://arxiv.org/list/cs.AI/recent)** — Research paper or preprint; check abstract and limitations.

## Courses, Tutorials & YouTube

**Choose your track:** Beginners can start with visual explanations; developers can learn Python, APIs, embeddings and evaluation; advanced learners can read research papers.

**Practice:** After each course, write a short explanation and build a working example.

**Note:** Several original YouTube URLs have generic labels because their titles have not been independently verified.


- **[youtu.be](https://youtu.be/O5xeyoRL95U?si=flJMP1XSZq1lvwTD)** — YouTube video; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&si=lsH9rZprZv6Uj8n6)** — Video or playlist; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&si=mHvo7680O9Tt4fB2)** — Video or playlist; topic and title not independently verified.
- **[youtu.be](https://youtu.be/V_xro1bcAuA?si=Kf062cUdYx1bZ3Jg)** — YouTube video; topic and title not independently verified.
- **[youtu.be](https://youtu.be/bNb2fEVKeEo?si=cRr6wU1_-PFaWaxV)** — YouTube video; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLoROMvodv4rOaMFbaqxPDoLWjDaRAdP9D&si=yGg1kXHnTjBwZsBW)** — Video or playlist; topic and title not independently verified.
- **[youtu.be](https://youtu.be/AsNTP8Kwu80?si=3uKI1gliLEJeN0ge)** — YouTube video; topic and title not independently verified.
- **[youtu.be](https://youtu.be/YCzL96nL7j0?si=aK6zr8hc8yaCFtvu)** — YouTube video; topic and title not independently verified.
- **[youtu.be](https://youtu.be/5NgNicANyqM?si=naKRSgSH2M-uJBkG)** — YouTube video; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI&si=B9h1WV-qcjWT7byY)** — Video or playlist; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0&si=gY7XMYxyEZLow3YZ)** — Video or playlist; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLkDaE6sCZn6Hn0vK8co82zjQtt3T2Nkqc&si=-180Wjv2a6wNxADV)** — Video or playlist; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b&si=fnDnAHmGIydVktx7)** — Video or playlist; topic and title not independently verified.
- **[youtube.com](https://youtube.com/playlist?list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF&si=8yxrGkMS5wT4R15c)** — Video or playlist; topic and title not independently verified.
- **[youtube.com](https://www.youtube.com/watch?v=iDulhoQ2pro)** — Video or playlist; topic and title not independently verified.

- **[Andrej Karpathy YouTube](https://www.youtube.com/@AndrejKarpathy)** — Video or playlist; topic and title not independently verified.
- **[3Blue1Brown YouTube](https://www.youtube.com/@3blue1brown)** — Video or playlist; topic and title not independently verified.
- **[StatQuest](https://www.youtube.com/@statquest)** — Video or playlist; topic and title not independently verified.
- **[fast.ai](https://course.fast.ai/)** — Resource related to courses, tutorials & youtube; review its documentation and suitability.
- **[CS50 AI](https://cs50.harvard.edu/ai/)** — Resource related to courses, tutorials & youtube; review its documentation and suitability.
- **[Hugging Face Learn](https://huggingface.co/learn)** — Model, tutorial or project page on Hugging Face.
- **[Full Stack Deep Learning](https://fullstackdeeplearning.com/)** — Resource related to courses, tutorials & youtube; review its documentation and suitability.
- **[Made With ML](https://madewithml.com/)** — Resource related to courses, tutorials & youtube; review its documentation and suitability.
- **[Kaggle Learn](https://www.kaggle.com/learn)** — Resource related to courses, tutorials & youtube; review its documentation and suitability.

## AI for SEO, AEO & GEO

**SEO** improves search-engine discoverability. **AEO** emphasizes content that directly answers questions. **GEO** is commonly used for visibility in AI-generated answers; exact definitions and metrics vary.

**Practical audit:** Check crawl access, rendered content, headings, canonicals, structured data, clear answers and reliable sources.

**Measure:** Search performance, identifiable AI referrals, citations and mentions on a defined prompt set, and conversions. AI citations cannot be guaranteed.


Resources for understanding search systems, AI-powered discovery, and how to evaluate visibility in generated answers. Vendor claims should be independently tested.

- **[Google Search Central](https://developers.google.com/search/docs)** — Official Google crawling, indexing and search guidance.
- **[Google AI Features and Your Website](https://developers.google.com/search/docs/appearance/ai-features)** — Google documentation for AI search features.
- **[Google Search Quality Rater Guidelines](https://guidelines.raterhub.com/searchqualityevaluatorguidelines.pdf)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Bing Webmaster Tools](https://www.bing.com/webmasters/)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Google Search Console](https://search.google.com/search-console/)** — Monitor Google Search clicks, impressions and indexing.
- **[Google Analytics](https://analytics.google.com/)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Google Search Status Dashboard](https://status.search.google.com/)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Schema.org](https://schema.org/)** — Vocabulary for structured data.
- **[Google Rich Results Test](https://search.google.com/test/rich-results)** — Test supported structured data.
- **[OpenAI Crawlers](https://platform.openai.com/docs/bots)** — Documentation on OpenAI web crawlers.
- **[Common Crawl](https://commoncrawl.org/)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Google Research](https://research.google/)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[Microsoft Research](https://www.microsoft.com/en-us/research/)** — Resource related to ai for seo, aeo & geo; review its documentation and suitability.
- **[GEO Research Paper](https://arxiv.org/abs/2311.09735)** — Research on generative engine optimization.
- **[Information Retrieval (Stanford)](https://nlp.stanford.edu/IR-book/)** — Free textbook on search and retrieval.

## Case Studies & Industry Applications

**What to look for:** The business problem, model and data, implementation, evaluation method, cost, limitations and measurable outcome.

**Example questions:** Was the AI solution compared with a simpler baseline? Were errors measured? Did it improve a real workflow?

**Note:** Some links below are engineering blogs rather than specific AI case studies.


- **[Google DeepMind Blog](https://deepmind.google/discover/blog/)** — Google DeepMind model or research information.
- **[OpenAI Research](https://openai.com/research/)** — OpenAI research or product information; check the publication date.
- **[Anthropic Research](https://www.anthropic.com/research)** — Anthropic research or product documentation.
- **[Netflix Tech Blog](https://netflixtechblog.com/)** — Resource related to case studies & industry applications; review its documentation and suitability.
- **[Uber Engineering](https://www.uber.com/blog/engineering/)** — Resource related to case studies & industry applications; review its documentation and suitability.
- **[Spotify Engineering](https://engineering.atspotify.com/)** — Resource related to case studies & industry applications; review its documentation and suitability.
- **[Airbnb Engineering](https://medium.com/airbnb-engineering)** — Resource related to case studies & industry applications; review its documentation and suitability.

## Communities, News & Open-Source Collections

**Use these for discovery**, not as final proof. Verify claims against original research, official documentation and project releases.

**Before adopting a tool:** Check the license, maintenance activity, security, compatibility and pricing.


- **[Hugging Face Community](https://huggingface.co/)** — Model, tutorial or project page on Hugging Face.
- **[Hugging Face Papers](https://huggingface.co/papers)** — Discover and discuss research papers.
- **[Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)** — Community-curated LLM resource collection.
- **[Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai)** — Code repository; inspect its README, license and recent activity.
- **[r/MachineLearning](https://www.reddit.com/r/MachineLearning/)** — Resource related to communities, news & open-source collections; review its documentation and suitability.
- **[The Batch](https://www.deeplearning.ai/the-batch/)** — Resource related to communities, news & open-source collections; review its documentation and suitability.
- **[Import AI](https://importai.substack.com/)** — Resource related to communities, news & open-source collections; review its documentation and suitability.
- **[Latent Space](https://www.latent.space/)** — Resource related to communities, news & open-source collections; review its documentation and suitability.
- **[SemiAnalysis](https://semianalysis.com/)** — Technical analysis of AI infrastructure and industry.

## Contributing

**For each suggestion:** Include its title, URL, topic, one-sentence explanation and whether it is free, paid or open source if known.


Suggestions, corrections, and additional learning resources are welcome. Open an issue or pull request with the resource name, URL, category, and a short description. Avoid affiliate links, duplicates, and unverified model-version claims.


### Maintenance

- Review external links regularly.
- Prefer official documentation and original research over secondary summaries.
- Keep model-specific release links up to date.
- Check licenses before redistributing third-party material.

---

If this collection helps you, consider starring the repository.