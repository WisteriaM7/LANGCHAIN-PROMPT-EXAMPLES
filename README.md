# 🧠 LangChain Prompt Playground 🚀

Welcome to the **LangChain Prompt Playground**!  
This repo is your hands-on lab for mastering prompt engineering and dynamic template magic using LangChain and Ollama LLMs. Whether you’re a curious beginner or a prompt power-user, these notebooks will help you craft, chain, and experiment with LLM prompts like a pro.

---

## 📚 Notebooks Included

### 1. PROMPT GENERATION TEMPLATE.ipynb

**What’s inside?**
- 🏗️ Build prompt templates with `PromptTemplate`
- 🧩 Format prompts with variables for flexible LLM queries
- 🔗 Chain templates, models, and output parsers for streamlined workflows
- 💬 Use `ChatPromptTemplate` for conversational AI
- 🎭 Mix multiple placeholders and message types (system/human)
- 🛠️ Advanced chaining for creative prompt engineering

**Key Libraries:**
- `langchain_community.llms.ollama`
- `langchain.prompts.PromptTemplate`
- `langchain_core.output_parsers.StrOutputParser`
- `langchain.prompts.ChatPromptTemplate`
- `langchain_core.messages.HumanMessage`
- `langchain_ollama.llms.OllamaLLM`

---

### 2. DYNAMIC PLACEHOLDER.ipynb

**What’s inside?**
- 🎛️ Dynamic placeholders for ultra-custom prompts
- 🧑‍💻 Multi-variable templates for both system and human messages
- 🪄 Pass dictionaries to generate highly tailored prompts
- 🤖 Invoke Ollama LLM and see your creative prompts in action

**Key Libraries:**
- `langchain_core.prompts.ChatPromptTemplate`
- `langchain_core.messages.HumanMessage`
- `langchain_ollama.llms.OllamaLLM`

---

## ⚡ Getting Started

1. **Requirements**
   - Python 3.8+
   - Jupyter Notebook or JupyterLab
   - [Ollama](https://ollama.com/) running locally with models like `tinydolphin` and `llama3.1`
   - Install dependencies:
     ```sh
     pip install langchain langchain-community langchain-core langchain-ollama
     ```

2. **How to Use**
   - Fire up your local Ollama server and make sure your models are ready.
   - Open either notebook in Jupyter.
   - Run the cells, tweak the templates, and watch your prompts come to life!

---

## ✨ Why Use This Repo?

- **Experiment Freely:** Tweak templates, swap models, and see instant results.
- **Learn by Doing:** Each notebook is packed with practical, hands-on examples.
- **Creative Playground:** Mix, match, and invent new prompt styles for any use case.

---

## 📜 License

MIT — Use, remix, and share!
