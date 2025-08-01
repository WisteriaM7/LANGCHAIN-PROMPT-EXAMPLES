# LangChain Prompt Engineering Examples

This repository contains two Jupyter notebooks demonstrating prompt engineering and dynamic placeholder usage with LangChain and Ollama LLMs.

## Notebooks

### 1. [PROMPT GENERATION TEMPLATE.ipynb](c:/Users/ruchita.maaran/Downloads/PROMPT%20GENERATION%20TEMPLATE.ipynb)

This notebook demonstrates:
- Basic prompt template creation using `PromptTemplate`.
- Formatting prompts with variables.
- Chaining prompt templates with models and output parsers.
- Using `ChatPromptTemplate` for chat-based prompts.
- Creating prompts with multiple placeholders.
- Using system and human messages in chat prompts.
- Advanced chaining and invoking models for various prompt styles.

**Key Libraries Used:**
- `langchain_community.llms.ollama`
- `langchain.prompts.PromptTemplate`
- `langchain_core.output_parsers.StrOutputParser`
- `langchain.prompts.ChatPromptTemplate`
- `langchain_core.messages.HumanMessage`
- `langchain_ollama.llms.OllamaLLM`

### 2. [DYNAMIC PLACEHOLDER.ipynb](c:/Users/ruchita.maaran/Downloads/DYNAMIC%20PLACEHOLDER.ipynb)

This notebook demonstrates:
- Advanced dynamic placeholders in chat prompt templates.
- Creating prompts with multiple variables for both system and human messages.
- Passing a dictionary of variables to generate highly customized prompts.
- Invoking the Ollama LLM with the generated prompt and displaying the result.

**Key Libraries Used:**
- `langchain_core.prompts.ChatPromptTemplate`
- `langchain_core.messages.HumanMessage`
- `langchain_ollama.llms.OllamaLLM`

## Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab
- [Ollama](https://ollama.com/) running locally with the required models (e.g., `tinydolphin`, `llama3.1`)
- Install dependencies:
  ```sh
  pip install langchain langchain-community langchain-core langchain-ollama
  ```

## Usage

1. Start your local Ollama server and ensure the required models are available.
2. Open either notebook in Jupyter.
3. Run the cells to see prompt generation and LLM invocation in action.
## License

MIT
