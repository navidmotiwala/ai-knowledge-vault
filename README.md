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
- [Courses and Tutorials](#courses-and-tutorials)
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

- **[Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)**: Free, practical lessons on machine learning concepts, models and evaluation.
- **[Elements of AI](https://www.elementsofai.com/)**: Beginner-friendly introduction to AI without requiring programming.
- **[Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)**: Code repository; inspect its README, license and recent activity.
- **[Google AI Essentials](https://grow.google/ai-essentials/)**: Introductory course focused on practical AI use at work.
- **[Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)**: Model, tutorial or project page on Hugging Face.
- **[DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/)**: Short courses on LLMs, agents, RAG and AI development.

## AI Foundations & Visual Explainers

**AI** is software performing tasks associated with human intelligence. **Machine learning** learns patterns from examples. **Deep learning** uses multilayer neural networks. **Generative AI** creates text, images, audio or other content.

**How an LLM works:** It splits text into tokens, processes their relationships through a neural network and predicts output tokens. A fluent answer can still be wrong.

**Try:** Explore a tokenizer and a transformer visualizer, then explain attention in your own words. This section also includes some advanced tools and industry resources.


- **[Financial Times: Generative AI Explainer](https://ig.ft.com/generative-ai/)**: Illustrated explanation of generative AI and its development.
- **[The Rise of Generative AI](https://informationisbeautiful.net/visualizations/the-rise-of-generative-ai-large-language-models-llms-like-chatgpt/)**: Visual timeline of generative AI and large language models.
- **[OpenAI Tokenizer](https://platform.openai.com/tokenizer)**: Explore how text is divided into tokens.
- **[Transformer Explainer](https://poloclub.github.io/transformer-explainer/)**: Interactive walkthrough of the Transformer architecture.
- **[LLM Visualization](https://bbycroft.net/llm)**: Interactive visualization of language-model components.
- **[TensorFlow Playground](https://playground.tensorflow.org/)**: Experiment with a small neural network in your browser.

## Machine Learning & Deep Learning

**Key ideas:** Datasets contain examples; features are inputs; labels are expected outputs; training adjusts a model; inference uses it; overfitting means poor performance on new examples.

**Example:** Predict customer churn using past customer data. Test on held-out customers, not only the examples used for training.

**Learn:** Classification, regression, train/test splits, loss, gradient descent, precision, recall and neural networks.


- **[TensorFlow](https://www.tensorflow.org/)**: Deep-learning framework for training and deploying models.
- **[PyTorch](https://pytorch.org/)**: Popular deep-learning framework.
- **[Scikit-learn](https://scikit-learn.org/stable/)**: Python library for classical machine learning.
- **[Google ML Glossary](https://developers.google.com/machine-learning/glossary)**: Definitions of common machine-learning concepts.
- **[Distill](https://distill.pub/)**: Visual explanations of machine-learning research.
- **[3Blue1Brown Neural Networks](https://www.3blue1brown.com/topics/neural-networks)**: Visual lessons on neural networks.
- **[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)**: Free online textbook explaining neural networks and backpropagation.

## LLMs & Model Ecosystem


- **[Claude Models Overview](https://platform.claude.com/docs/en/models/overview)**: Official reference for Claude model capabilities.
- **[OpenAI Model Announcement](https://openai.com/index/introducing-gpt-5-5/)**: Official model release information; check the date and availability.
- **[Google Gemini Model Announcement](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/)**: Google's model announcement; confirm version and date on the page.
- **[Ollama](https://ollama.com/)**: Run supported language models on your own computer.
- **[LM Studio](https://lmstudio.ai/)**: Run and test local language models in a desktop app.
- **[DeepSeek Model Page](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro)**: Model information and availability on Hugging Face; check model card.
- **[xAI](https://x.ai/)**: AI model developer and product information.


**LLM:** A large language model that processes and generates language. Models differ in quality, speed, price, context length, supported tools and privacy terms.

**Hosted vs local:** Hosted models run through a provider; supported open-weight models can run on your own machine under their license.

**Compare:** Use your own test questions and check factual accuracy, latency, cost, output format and tool support.


- **[Hugging Face Models](https://huggingface.co/models)**: Explore model cards and licenses.
- **[OpenAI Models](https://platform.openai.com/docs/models)**: Official model documentation.
- **[Anthropic Models](https://docs.anthropic.com/en/docs/about-claude/models/overview)**: Official Anthropic documentation.
- **[Google Gemini Models](https://ai.google.dev/gemini-api/docs/models)**: Official Gemini model capabilities and API reference.
- **[Meta Llama](https://www.llama.com/)**: Official Llama model family and resources.
- **[Mistral AI](https://docs.mistral.ai/)**: Official model, API and deployment documentation.
- **[DeepSeek](https://github.com/deepseek-ai)**: Code repository; inspect its README, license and recent activity.
- **[Qwen](https://github.com/QwenLM)**: Code repository; inspect its README, license and recent activity.
- **[vLLM](https://docs.vllm.ai/)**: Efficient LLM serving engine.
- **[llama.cpp](https://github.com/ggml-org/llama.cpp)**: Code repository; inspect its README, license and recent activity.

## Prompt Engineering


- **[Claude Prompt Engineering Guide](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)**: Official guidance for designing prompts for Claude.
- **[OpenAI Prompt Engineering Guide](https://developers.openai.com/api/docs/guides/prompt-engineering?api-mode=responses)**: Official prompt design guidance for developers.


**Prompt engineering** is writing instructions that clearly specify a task, context, constraints and output format.

**Example:** Instead of “summarize this,” say “Summarize these support tickets in five bullets, group repeated issues, show counts and say unknown where evidence is missing.”

**Test:** Missing information, ambiguous requests, conflicting source text and long inputs. A good prompt reduces errors but cannot guarantee correctness.


- **[OpenAI Prompting Guide](https://platform.openai.com/docs/guides/prompt-engineering)**: OpenAI API documentation or interactive tool.
- **[Anthropic Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)**: Official Anthropic documentation.
- **[Google Prompt Design](https://ai.google.dev/gemini-api/docs/prompting-strategies)**: Official Gemini prompting strategies and examples.
- **[Prompt Engineering Guide](https://www.promptingguide.ai/)**: Community guide to prompting concepts and techniques.
- **[Learn Prompting](https://learnprompting.org/)**: Structured lessons on writing and evaluating prompts.
- **[OpenAI Cookbook](https://cookbook.openai.com/)**: Practical API examples.
- **[Anthropic Interactive Prompt Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)**: Code repository; inspect its README, license and recent activity.

## LLM Playgrounds & Evaluation


- **[Arena Side-by-Side](https://arena.ai/text/side-by-side)**: Compare responses from different language models.
- **[LLM Stats: Compare Models](https://llm-stats.com/models/compare)**: Compare published specifications of language models.
- **[Google NotebookLM](https://notebook.google.com/)**: Ask questions about and summarize uploaded source material.
- **[Artificial Analysis](https://artificialanalysis.ai/)**: Compare model performance, cost and speed.


**Playgrounds** let you try models and prompts. **Evaluation** tests whether outputs meet your requirements.

**Metrics:** Task success, factual accuracy, citation correctness, structured-output validity, latency, cost and safety.

**Example:** Test 50 support questions against a known answer key and compare model versions using the same questions.


- **[LiteLLM Playground Tutorial](https://docs.litellm.ai/docs/tutorials/first_playground)**: Set up a playground to test models through LiteLLM.
- **[huggingface.co](https://huggingface.co/playground)**: Model, tutorial or project page on Hugging Face.
- **[OpenPlayground](https://github.com/nat/openplayground)**: Open-source interface for experimenting with language models.
- **[Retool LLM Playground](https://retool.com/utilities/largelanguagemodel-playground)**: Interactive interface for experimenting with language models.
- **[Free LLM Playground](https://freellmplayground.com/)**: Third-party model playground; check privacy and access terms.
- **[Langfuse Prompt Playground](https://langfuse.com/docs/prompt-management/features/playground)**: Test and iterate on prompts with tracing and evaluation tools.
- **[PromptFoundry LLM Playground](https://www.promptfoundry.ai/llm-playground)**: Third-party interface for comparing prompts and outputs.

- **[Google AI Studio](https://aistudio.google.com/)**: Try Gemini models and prototype prompts.
- **[OpenAI Playground](https://platform.openai.com/playground)**: OpenAI API documentation or interactive tool.
- **[Hugging Face Chat](https://huggingface.co/chat/)**: Model, tutorial or project page on Hugging Face.
- **[Chatbot Arena](https://arena.ai/)**: Compare model outputs and evaluations.
- **[LangSmith Evaluation](https://docs.langchain.com/langsmith/evaluation)**: Documentation for LLM applications and agents.
- **[Langfuse](https://langfuse.com/)**: Monitor and evaluate LLM applications.
- **[Ragas](https://docs.ragas.io/)**: Evaluate RAG retrieval and answers.
- **[DeepEval](https://github.com/confident-ai/deepeval)**: Framework for testing LLM applications.
- **[Promptfoo](https://www.promptfoo.dev/)**: Prompt and model testing, including security checks.
- **[HELM](https://crfm.stanford.edu/helm/)**: Stanford framework for evaluating language models.
- **[EleutherAI LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)**: Code repository; inspect its README, license and recent activity.

## Retrieval-Augmented Generation (RAG)


- **[Sentence Transformers](https://sbert.net/)**: Documentation for sentence embeddings and semantic similarity.


**RAG** retrieves relevant information from documents or databases and provides it to a model before answering.

**Typical process:** Load documents → split into chunks → create embeddings → index → retrieve relevant passages → generate an answer → verify citations.

**Example:** A helpdesk assistant answers from current product manuals. Common failures include missing source material, weak retrieval and unsupported answers. RAG does not retrain the underlying model.


- **[Pinecone](https://www.pinecone.io/)**: Managed vector database for semantic retrieval.
- **[LlamaIndex](https://www.llamaindex.ai/)**: Tools for connecting external data to LLM applications.
- **[LangChain](https://www.langchain.com/)**: Framework and tooling for LLM application development.
- **[Function Calling Guide](https://www.promptingguide.ai/agents/function-calling)**: Explains how models request structured external tool calls.
- **[IBM: RAG Explained](https://www.ibm.com/think/topics/retrieval-augmented-generation)**: Introduction to retrieval-augmented generation.

- **[Google Cloud RAG Overview](https://cloud.google.com/use-cases/retrieval-augmented-generation)**: Introduction to retrieving external knowledge for model responses.
- **[LlamaIndex Docs](https://docs.llamaindex.ai/)**: Guides for ingesting, indexing and querying documents.
- **[LangChain RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/)**: Tutorial for implementing document retrieval and question answering.
- **[Chroma](https://docs.trychroma.com/)**: Vector database for embeddings.
- **[Weaviate](https://weaviate.io/developers/weaviate)**: Vector database and hybrid search.
- **[Qdrant](https://qdrant.tech/documentation/)**: Vector search database.
- **[Milvus](https://milvus.io/docs)**: Open-source vector database.
- **[FAISS](https://github.com/facebookresearch/faiss)**: Library for vector similarity search.

## AI Agents & Orchestration


- **[Anthropic: Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)**: Explains agent and workflow design patterns.
- **[IBM: Multi-Agent Systems](https://www.ibm.com/think/topics/multiagent-system)**: Explains how multiple AI agents coordinate on tasks.
- **[IBM: AI Agent Orchestration](https://www.ibm.com/think/topics/ai-agent-orchestration)**: Explains how AI agents and tools are coordinated.
- **[LangChain Documentation](https://docs.langchain.com/)**: Developer documentation for LLM apps and agents.
- **[CrewAI GitHub Repository](https://github.com/crewAIInc/crewAI)**: Source code and examples for CrewAI agent workflows.


**Agent:** A system that can decide which tools to call and what step to take next. **Workflow:** A more predictable sequence of predefined steps.

**Example:** A research assistant searches approved sources, compares findings and drafts a report. Require human approval before publishing or sending anything.

**Check:** Completion rate, unnecessary tool calls, loops, security, cost and recovery from failures.


- **[Claude Cowork](https://claude.com/product/cowork)**: Claude product for working on tasks across files and tools.
- **[Claude in Chrome](https://claude.com/claude-in-chrome)**: Browser integration for Claude.
- **[platform.claude.com](https://platform.claude.com/docs/en/agents-and-tools/tool-use/computer-use-tool)**: Official Claude developer documentation.
- **[n8n.io](https://n8n.io/)**: Workflow automation tool or tutorial.
- **[Make](http://make.com/)**: Visual automation platform connecting apps and workflows.
- **[Zapier](https://zapier.com/)**: Connect services through event-triggered automations.
- **[CrewAI](https://crewai.com/)**: Platform for building and running AI agent workflows.
- **[Lindy](https://www.lindy.ai/)**: AI assistant and automation platform.
- **[Relevance AI](https://relevanceai.com/)**: Platform for building AI agents and workflows.

- **[OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)**: Python framework for building agents with tools, handoffs and tracing.
- **[LangGraph](https://docs.langchain.com/oss/python/langgraph/overview)**: Documentation for LLM applications and agents.
- **[CrewAI](https://docs.crewai.com/)**: Documentation for coordinating multiple AI agents.
- **[AutoGen](https://github.com/microsoft/autogen)**: Code repository; inspect its README, license and recent activity.
- **[Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/)**: Documentation for building and orchestrating agents.
- **[Google Agent Development Kit](https://google.github.io/adk-docs/)**: Agent development toolkit and examples.
- **[Agno](https://docs.agno.com/)**: Framework for developing agents and workflows.
- **[Kaggle Agents Whitepaper](https://www.kaggle.com/whitepaper-agents)**: Introductory material about agent architecture and evaluation.

## MCP, A2A & Agent Protocols

**MCP (Model Context Protocol)** standardizes connections between AI applications and tools or data. **A2A (Agent2Agent)** supports communication between separate agents.

**Example:** An assistant reads calendar events through an MCP connection; a travel agent coordinates with another specialist agent through an agent-to-agent protocol.

**Security:** Verify connectors, limit permissions and treat retrieved content as untrusted data.


- **[MCP Getting Started](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro)**: Introduction to connecting AI apps with tools and data.
- **[platform.claude.com](https://platform.claude.com/docs/en/agents-and-tools/mcp-connector)**: Official Claude developer documentation.
- **[Model Context Protocol GitHub](https://github.com/modelcontextprotocol)**: Official MCP organization and related repositories.
- **[Agentic AI Foundation](https://aaif.io/)**: Organization supporting open agent interoperability.
- **[anthropic.com](https://www.anthropic.com/news/model-context-protocol)**: Anthropic research or product documentation.
- **[IBM: Model Context Protocol](https://www.ibm.com/think/topics/model-context-protocol)**: Explains MCP and its role in connecting AI tools.
- **[anthropic.com](https://www.anthropic.com/research/code-execution-with-mcp)**: Anthropic research or product documentation.
- **[MCP vs A2A Comparison](https://dev.to/pockit_tools/mcp-vs-a2a-the-complete-guide-to-ai-agent-protocols-in-2026-30li)**: Community article comparing two agent integration protocols.

- **[MCP Documentation](https://modelcontextprotocol.io/)**: Official introduction to the Model Context Protocol.
- **[MCP Specification](https://modelcontextprotocol.io/specification)**: Technical definition of MCP messages and behavior.
- **[MCP Servers](https://github.com/modelcontextprotocol/servers)**: Code repository; inspect its README, license and recent activity.
- **[Google A2A Protocol](https://a2a-protocol.org/)**: Specification for communication between independent AI agents.
- **[A2A GitHub](https://github.com/a2aproject/A2A)**: Code repository; inspect its README, license and recent activity.

## AI Automation & RPA


- **[freeCodeCamp: n8n Automation Guide](https://www.freecodecamp.org/news/a-beginners-guide-to-automation-with-n8n)**: Beginner tutorial for creating automation workflows.
- **[IBM: Robotic Process Automation](https://www.ibm.com/think/topics/rpa)**: Explains software bots that automate repetitive tasks.


**Automation** runs tasks based on triggers and rules. **RPA** often interacts with user interfaces; API automation communicates directly with services.

**Example:** Every Monday, collect analytics metrics, calculate weekly changes, draft a summary and send it for approval.

**Build reliably:** Add retries, logging, error alerts, access controls and human review for important decisions.


- **[n8n Templates](https://n8n.io/workflows/)**: Workflow automation tool or tutorial.
- **[Make](https://www.make.com/)**: Visual automation platform.
- **[Pipedream](https://pipedream.com/)**: API and event-driven automation.
- **[Activepieces](https://www.activepieces.com/)**: Open-source workflow automation platform.
- **[Node-RED](https://nodered.org/)**: Flow-based programming tool for event-driven automation.

## AI Coding & App Building


- **[Claude Code Workflows](https://code.claude.com/docs/en/workflows)**: Documentation for common Claude Code workflows.


**AI-assisted coding** uses a model to write, explain, test or refactor code. **Vibe coding** describes building by iterating on natural-language instructions.

**Beginner project:** Build a small question-answer app with input validation, loading state and error handling.

**Important:** Review generated code, protect API keys, inspect dependencies and test before deployment.


- **[Cursor](https://cursor.com/)**: AI-assisted code editor.
- **[Bolt](https://bolt.new/)**: Build and prototype web applications using prompts.
- **[Lovable](https://lovable.dev/)**: Create web applications from natural-language instructions.
- **[Replit](https://replit.com/)**: Cloud development environment with AI coding tools.
- **[v0](https://v0.app/)**: Generate web interfaces and components from prompts.
- **[Devin Desktop](https://devin.ai/desktop)**: AI software development product.
- **[Claude Code Documentation](https://code.claude.com/docs/en/overview)**: Getting started with Claude Code.
- **[GitHub Copilot](https://github.com/features/copilot)**: AI coding assistant for suggesting, explaining and editing code.
- **[OpenAI Codex](https://openai.com/codex/)**: AI coding assistant for software development tasks.

- **[Aider](https://aider.chat/)**: AI pair-programming from the terminal.
- **[Continue](https://www.continue.dev/)**: Open-source coding assistant.
- **[Cline](https://github.com/cline/cline)**: AI coding agent extension.
- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)**: Open-source AI software development agents.
- **[Streamlit](https://streamlit.io/)**: Build Python web apps.
- **[Gradio](https://www.gradio.app/)**: Build simple interfaces for AI demos.
- **[Hugging Face Spaces](https://huggingface.co/spaces)**: Host and share interactive ML demos.

## Multimodal AI: Images, Video & Audio


- **[Stable Diffusion with Diffusers](https://huggingface.co/docs/diffusers/stable_diffusion)**: Documentation for generating images with Stable Diffusion.


**Multimodal AI** can process or generate more than one media type, including images, video, audio and text.

**Example workflow:** Storyboard → generate visuals → edit → narrate → caption → review.

**Before publishing:** Check licensing, consent, accuracy and applicable disclosure requirements.


- **[Midjourney Documentation](https://docs.midjourney.com/hc/en-us)**: Official instructions for image generation.
- **[Kling AI](https://kling.ai/)**: AI video generation platform.
- **[Jimeng](https://jimeng.com/)**: AI creative media generation platform.
- **[deepmind.google](https://deepmind.google/models/veo/)**: Google DeepMind model or research information.
- **[Runway](https://runway.com/)**: AI video creation and editing tools.
- **[deepmind.google](https://deepmind.google/models/gemini-image/)**: Google DeepMind model or research information.
- **[Black Forest Labs](https://bfl.ai/)**: Image generation models and tools.
- **[Ideogram](https://ideogram.ai/)**: AI image generation with text rendering capabilities.
- **[elevenlabs.io](https://elevenlabs.io/)**: AI voice and audio tools.
- **[Suno](https://suno.com/)**: AI music generation service; review licensing.
- **[Udio](https://www.udio.com/)**: AI music generation service; review licensing.

- **[Hugging Face Diffusers](https://huggingface.co/docs/diffusers/)**: Model, tutorial or project page on Hugging Face.
- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI)**: Visual workflows for image generation.
- **[Stable Diffusion](https://stability.ai/)**: Image-generation model family and ecosystem.
- **[Google DeepMind Models](https://deepmind.google/models/)**: Google DeepMind model or research information.
- **[Adobe Firefly](https://firefly.adobe.com/)**: Adobe's generative AI creative tools.

## Voice AI & Speech

**STT** converts speech to text. **TTS** converts text to speech. A **voice agent** combines listening, reasoning and spoken responses.

**Example:** A booking assistant transcribes a request, checks approved availability, asks for confirmation and speaks the result.

**Evaluate:** Latency, transcription errors, interruptions, accents, privacy and handoff to a person.


- **[elevenlabs.io](https://elevenlabs.io/conversational-ai)**: AI voice and audio tools.
- **[Deepgram: Voice AI Explained](https://deepgram.com/learn/voice-ai-explained)**: Introduction to speech-based AI systems.
- **[OpenAI Whisper](https://github.com/openai/whisper)**: Open-source speech recognition model and implementation.
- **[Hume AI](https://www.hume.ai/)**: Voice and conversational AI products.
- **[Sesame](https://www.sesame.com/)**: Conversational voice AI products.
- **[developers.openai.com](https://developers.openai.com/api/docs/guides/conversation-state?api-mode=responses)**: OpenAI developer documentation.

- **[OpenAI Speech to Text](https://platform.openai.com/docs/guides/speech-to-text)**: OpenAI API documentation or interactive tool.
- **[OpenAI Text to Speech](https://platform.openai.com/docs/guides/text-to-speech)**: OpenAI API documentation or interactive tool.
- **[Coqui TTS](https://github.com/coqui-ai/TTS)**: Code repository; inspect its README, license and recent activity.
- **[Pipecat](https://github.com/pipecat-ai/pipecat)**: Framework for real-time voice agents.
- **[LiveKit Agents](https://docs.livekit.io/agents/)**: Real-time voice agent infrastructure.

## AI Safety, Security & Responsible AI


- **[OWASP: Prompt Injection](https://genai.owasp.org/llm-top-10-2025/llm01-prompt-injection)**: Security guidance on malicious instructions targeting LLM systems.


**Risks:** Hallucinations, prompt injection, sensitive-data leaks, bias, unsafe tool actions and misleading confidence.

**Example:** A webpage tells an assistant to ignore its instructions. That webpage is untrusted content, not an authorized command.

**Controls:** Least-privilege permissions, output checks, redaction, audit logs, evaluations and human approval for consequential actions.


- **[OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)**: Common security risks for LLM applications.
- **[NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)**: Framework for managing AI risk.
- **[MITRE ATLAS](https://atlas.mitre.org/)**: Knowledge base of attacks against AI systems.
- **[Google Secure AI Framework](https://saif.google/)**: Google's framework for securing AI systems.
- **[AI Incident Database](https://incidentdatabase.ai/)**: Database of reported incidents involving AI.
- **[Stanford AI Index](https://hai.stanford.edu/ai-index)**: Research-based reports on AI development and adoption.
- **[Anthropic Responsible Scaling Policy](https://www.anthropic.com/responsible-scaling-policy)**: Anthropic research or product documentation.
- **[Hugging Face Model Cards](https://huggingface.co/docs/hub/model-cards)**: Model, tutorial or project page on Hugging Face.

## Research Papers

**Why read papers:** They explain how methods work, what was tested and where results may fail. A preprint is not necessarily peer-reviewed.

**How to read:** Abstract → problem → method → experiments → limitations → replication or code.

**Suggested order:** Transformers, pretraining, instruction tuning, retrieval, tool use, fine-tuning and efficiency.


- **[Attention Is All You Need](https://arxiv.org/abs/1706.03762)**: Introduces the Transformer architecture and attention mechanism.
- **[Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)**: Studies step-by-step reasoning demonstrations in prompts.
- **[Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)**: Introduces GPT-3 and few-shot learning experiments.
- **[Research paper 2402.07927](https://arxiv.org/abs/2402.07927)**: Read the paper's abstract and methods to identify its subject.
- **[LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)**: Research paper or preprint; check abstract and limitations.
- **[Research paper 2401.01313](https://arxiv.org/abs/2401.01313)**: Read the paper's abstract and methods to identify its subject.
- **[Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)**: Foundational research on diffusion-based generation.
- **[High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)**: Introduces latent diffusion for image generation.
- **[Research paper 2303.07909](https://arxiv.org/abs/2303.07909)**: Read the paper's abstract and methods to identify its subject.
- **[Research paper 2302.05543](https://arxiv.org/abs/2302.05543)**: Read the paper's abstract and methods to identify its subject.

- **[BERT](https://arxiv.org/abs/1810.04805)**: Research paper on bidirectional language pretraining.
- **[Retrieval-Augmented Generation](https://arxiv.org/abs/2005.11401)**: Original paper on retrieval-backed text generation.
- **[InstructGPT](https://arxiv.org/abs/2203.02155)**: Research on instruction following and human feedback.
- **[Direct Preference Optimization](https://arxiv.org/abs/2305.18290)**: Research on preference-based alignment.
- **[ReAct](https://arxiv.org/abs/2210.03629)**: Research on reasoning with tool actions.
- **[Toolformer](https://arxiv.org/abs/2302.04761)**: Research on learning to use tools.
- **[Lost in the Middle](https://arxiv.org/abs/2307.03172)**: Study of long-context retrieval weaknesses.
- **[QLoRA](https://arxiv.org/abs/2305.14314)**: Memory-efficient fine-tuning method.
- **[FlashAttention](https://arxiv.org/abs/2205.14135)**: Efficient attention computation.
- **[Papers with Code](https://paperswithcode.com/)**: Find research papers and related code implementations.
- **[arXiv AI](https://arxiv.org/list/cs.AI/recent)**: Browse recent AI research preprints; check peer-review status.

## Courses and Tutorials


- **[LangChain Academy](https://academy.langchain.com/)**: Courses on building LLM applications and agents.


## YouTube Videos and Playlists

Video thumbnails are clickable and open YouTube. Playlists are linked directly because YouTube does not provide a reliable playlist thumbnail URL through standard GitHub Markdown.

### Artificial intelligence fundamentals

**Harvard CS50: Artificial Intelligence with Python, Full Course**

[![Harvard CS50: Artificial Intelligence with Python, Full Course video thumbnail](https://img.youtube.com/vi/5NgNicANyqM/hqdefault.jpg)](https://youtu.be/5NgNicANyqM)

University course on search, knowledge, probability, learning and language, with Python examples.

[Watch on YouTube](https://youtu.be/5NgNicANyqM)


### Neural networks and transformers

**Neural Networks (Playlist)**

3Blue1Brown visual lessons on neural networks, gradient descent, backpropagation, transformers and attention.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)


### Machine learning

**Andrew Ng: Machine Learning Course Playlist (Playlist)**

Foundational machine-learning lectures and exercises; playlist edition may differ from current courses.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI)


### Deep learning foundations

**MIT Deep Learning: Introduction and Overview**

[![MIT Deep Learning: Introduction and Overview video thumbnail](https://img.youtube.com/vi/O5xeyoRL95U/hqdefault.jpg)](https://youtu.be/O5xeyoRL95U)

Introductory MIT lecture on deep learning concepts and applications.

[Watch on YouTube](https://youtu.be/O5xeyoRL95U)


### Training neural networks

**Andrew Ng: Deep Learning Specialization, Course 2 (Playlist)**

Improving deep neural networks through tuning, regularization and optimization.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLkDaE6sCZn6Hn0vK8co82zjQtt3T2Nkqc)


### Machine learning strategy

**Andrew Ng: Deep Learning Specialization, Course 3 (Playlist)**

Diagnosing model errors and prioritizing improvements.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b)


### Convolutional neural networks

**Andrew Ng: Deep Learning Specialization, Course 4 (Playlist)**

Computer vision with convolutional neural networks.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF)


### Computer vision

**Stanford CS231n: Lecture 5, Convolutional Neural Networks**

[![Stanford CS231n: Lecture 5, Convolutional Neural Networks video thumbnail](https://img.youtube.com/vi/bNb2fEVKeEo/hqdefault.jpg)](https://youtu.be/bNb2fEVKeEo)

Stanford lecture explaining convolutional networks and their use in visual recognition.

[Watch on YouTube](https://youtu.be/bNb2fEVKeEo)


### Sequence models

**Recurrent Neural Networks (RNNs), Clearly Explained**

[![Recurrent Neural Networks (RNNs), Clearly Explained video thumbnail](https://img.youtube.com/vi/AsNTP8Kwu80/hqdefault.jpg)](https://youtu.be/AsNTP8Kwu80)

StatQuest introduction to recurrent networks, their structure and training challenges.

[Watch on YouTube](https://youtu.be/AsNTP8Kwu80)

**Long Short-Term Memory (LSTM), Clearly Explained**

[![Long Short-Term Memory (LSTM), Clearly Explained video thumbnail](https://img.youtube.com/vi/YCzL96nL7j0/hqdefault.jpg)](https://youtu.be/YCzL96nL7j0)

StatQuest explanation of LSTM networks and why they help model longer sequences.

[Watch on YouTube](https://youtu.be/YCzL96nL7j0)


### NLP and language models

**Stanford CS224N: Natural Language Processing with Deep Learning (Playlist)**

University lecture series on neural approaches to natural-language processing.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLoROMvodv4rOaMFbaqxPDoLWjDaRAdP9D)


### PyTorch programming

**PyTorch for Deep Learning and Machine Learning: Full Course**

[![PyTorch for Deep Learning and Machine Learning: Full Course video thumbnail](https://img.youtube.com/vi/V_xro1bcAuA/hqdefault.jpg)](https://youtu.be/V_xro1bcAuA)

Hands-on introduction to tensors, training neural networks and deep-learning workflows in PyTorch.

[Watch on YouTube](https://youtu.be/V_xro1bcAuA)


### Generative AI and LLM development

**Generative AI Full Course: Gemini, OpenAI, Llama, LangChain and Vector Databases**

[![Generative AI Full Course: Gemini, OpenAI, Llama, LangChain and Vector Databases video thumbnail](https://img.youtube.com/vi/mEsleV16qdo/hqdefault.jpg)](https://youtu.be/mEsleV16qdo)

Long course covering model APIs, application frameworks and retrieval infrastructure.

[Watch on YouTube](https://youtu.be/mEsleV16qdo)


### Neural networks from scratch

**Neural Networks: Zero to Hero (Playlist)**

Andrej Karpathy's coding-focused series on neural networks, language models and GPT-related building blocks.

[Open the full playlist on YouTube](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)


### Transformers and attention

**Attention Is All You Need: Paper Explained**

[![Attention Is All You Need: Paper Explained video thumbnail](https://img.youtube.com/vi/iDulhoQ2pro/hqdefault.jpg)](https://www.youtube.com/watch?v=iDulhoQ2pro)

Yannic Kilcher's explanation of the original Transformer research paper.

[Watch on YouTube](https://www.youtube.com/watch?v=iDulhoQ2pro)


**Note:** Some video and playlist titles still need direct verification on YouTube.


**More learning resources:** Explore the channels and courses below.


- **[Andrej Karpathy YouTube](https://www.youtube.com/@AndrejKarpathy)**: Lessons on neural networks and building language models.
- **[3Blue1Brown YouTube](https://www.youtube.com/@3blue1brown)**: Visual explanations of mathematics and neural networks.
- **[StatQuest YouTube](https://www.youtube.com/@statquest)**: Accessible lessons on statistics and machine learning.
- **[fast.ai](https://course.fast.ai/)**: Hands-on deep-learning course with code examples.
- **[CS50 AI](https://cs50.harvard.edu/ai/)**: Harvard course teaching AI methods with Python.
- **[Hugging Face Learn](https://huggingface.co/learn)**: Model, tutorial or project page on Hugging Face.
- **[Full Stack Deep Learning](https://fullstackdeeplearning.com/)**: Practical course on building and operating ML products.
- **[Made With ML](https://madewithml.com/)**: Lessons on data, model development, testing and deployment.
- **[Kaggle Learn](https://www.kaggle.com/learn)**: Short interactive exercises in Python, ML and data analysis.

## AI for SEO, AEO & GEO

**SEO** improves search-engine discoverability. **AEO** emphasizes content that directly answers questions. **GEO** is commonly used for visibility in AI-generated answers; exact definitions and metrics vary.

**Practical audit:** Check crawl access, rendered content, headings, canonicals, structured data, clear answers and reliable sources.

**Measure:** Search performance, identifiable AI referrals, citations and mentions on a defined prompt set, and conversions. AI citations cannot be guaranteed.


Resources for understanding search systems, AI-powered discovery, and how to evaluate visibility in generated answers. Vendor claims should be independently tested.

- **[Google Search Central](https://developers.google.com/search/docs)**: Official Google crawling, indexing and search guidance.
- **[Google AI Features and Your Website](https://developers.google.com/search/docs/appearance/ai-features)**: Google documentation for AI search features.
- **[Google Search Quality Rater Guidelines](https://guidelines.raterhub.com/searchqualityevaluatorguidelines.pdf)**: Google's handbook for evaluating search-result quality.
- **[Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a)**: Bing's recommendations for crawling, indexing and site quality.
- **[Bing Webmaster Tools](https://www.bing.com/webmasters/)**: Inspect Bing search traffic and indexing issues.
- **[Google Search Console](https://search.google.com/search-console/)**: Monitor Google Search clicks, impressions and indexing.
- **[Google Analytics](https://analytics.google.com/)**: Measure website traffic, engagement and conversions.
- **[Google Search Status Dashboard](https://status.search.google.com/)**: Official updates about Google Search incidents.
- **[Schema.org](https://schema.org/)**: Vocabulary for structured data.
- **[Google Rich Results Test](https://search.google.com/test/rich-results)**: Test supported structured data.
- **[OpenAI Crawlers](https://platform.openai.com/docs/bots)**: Documentation on OpenAI web crawlers.
- **[Common Crawl](https://commoncrawl.org/)**: Open web-crawl datasets for research.
- **[Google Research](https://research.google/)**: Google's research publications and projects.
- **[Microsoft Research](https://www.microsoft.com/en-us/research/)**: Microsoft's research publications and projects.
- **[GEO Research Paper](https://arxiv.org/abs/2311.09735)**: Research on generative engine optimization.
- **[Information Retrieval (Stanford)](https://nlp.stanford.edu/IR-book/)**: Free textbook on search and retrieval.

## Case Studies & Industry Applications

**What to look for:** The business problem, model and data, implementation, evaluation method, cost, limitations and measurable outcome.

**Example questions:** Was the AI solution compared with a simpler baseline? Were errors measured? Did it improve a real workflow?

**Note:** Some links below are engineering blogs rather than specific AI case studies.


- **[Google DeepMind Blog](https://deepmind.google/discover/blog/)**: Google DeepMind model or research information.
- **[OpenAI Research](https://openai.com/research/)**: OpenAI research or product information; check the publication date.
- **[Anthropic Research](https://www.anthropic.com/research)**: Anthropic research or product documentation.
- **[Netflix Tech Blog](https://netflixtechblog.com/)**: Engineering case studies from Netflix.
- **[Uber Engineering](https://www.uber.com/blog/engineering/)**: Engineering and architecture articles from Uber.
- **[Spotify Engineering](https://engineering.atspotify.com/)**: Technical case studies from Spotify.
- **[Airbnb Engineering](https://medium.com/airbnb-engineering)**: Engineering articles from Airbnb.

## Communities, News & Open-Source Collections


- **[SemiAnalysis](https://semianalysis.com/)**: Research and analysis of AI models, chips and infrastructure.
- **[Awesome LLM Collection](https://github.com/Hannibal046/Awesome-LLM)**: Curated collection of large language model resources.


**Use these for discovery**, not as final proof. Verify claims against original research, official documentation and project releases.

**Before adopting a tool:** Check the license, maintenance activity, security, compatibility and pricing.


- **[Hugging Face Community](https://huggingface.co/)**: Model, tutorial or project page on Hugging Face.
- **[Hugging Face Papers](https://huggingface.co/papers)**: Discover and discuss research papers.
- **[Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai)**: Code repository; inspect its README, license and recent activity.
- **[r/MachineLearning](https://www.reddit.com/r/MachineLearning/)**: Community discussion of machine-learning research.
- **[The Batch](https://www.deeplearning.ai/the-batch/)**: AI research and industry newsletter.
- **[Import AI](https://importai.substack.com/)**: Newsletter covering AI research and policy.
- **[Latent Space](https://www.latent.space/)**: AI engineering articles and interviews.

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