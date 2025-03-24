# LangChain_DeepLearningAI
This repository hosts code examples exploring key topics such as prompt engineering, chaining LLM calls, and integrating external data sources using the LangChain framework. Ideal for developers, data scientists, and AI enthusiasts building intelligent applications.

[View Credential](https://learn.deeplearning.ai/accomplishments/694da37d-4d42-434a-aae3-b4fdf7e8b968?usp=sharing) on deeplearning.ai

## Contents

- **L1-Model_prompt_parser.ipynb**  
  Demonstrates direct API calls, prompt templates, output parsing, and model interactions using LangChain.

- **L2-Memory.ipynb**  
  Explores memory management strategies for conversational applications (e.g., Conversation Buffer, Token Buffer, and Summary Memory).

- **L3-Chains.ipynb**  
  Covers building chains including LLMChain, SimpleSequentialChain, SequentialChain, and Router Chains for multi-step workflows.

- **L4-QnA.ipynb**  
  Shows how to create a document Q&A system using CSV document loaders, vector stores, and retrieval chains.

- **L5-Evaluation.ipynb**  
  Demonstrates techniques for evaluating Q&A performance with manually defined and LLM-generated examples, including LLM-assisted grading.

- **L6-Agents.ipynb**  
  Illustrates the use of built-in tools (e.g., Wikipedia, LLM Math) and custom tools (e.g., a Python REPL agent and a custom "time" tool) to build and extend agent capabilities.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/unikill066/LangChain_DeepLearningAI.git
   cd LangChain_DeepLearningAI
   ```

2. **Install Dependencies:**
   Ensure you have Python 3.7+ installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the repository root with your OpenAI API key and any other necessary credentials:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Run the Notebooks:**
   Open the notebooks in Jupyter Notebook, JupyterLab, or VSCode to explore and interact with the examples.

## License

This repository is licensed under the MIT License.

## Contributing

Contributions, issues, and suggestions are welcome. Please feel free to open an issue or submit a pull request.

Enjoy exploring LangChain and building intelligent applications!
