# AryanCoder - Code Teaching Assistant 🤖💡

AryanCoder is a locally running code teaching assistant powered by [Ollama](https://ollama.com), [CodeLlama](https://ai.meta.com/llama/), and [Gradio](https://www.gradio.app/). This assistant is designed to help users learn and understand programming with concise explanations and example code.

---

## 🚀 Features

- Uses locally running CodeLlama model through Ollama
- Simple chat UI built with Gradio
- Maintains chat history in memory
- No cloud required – completely private & offline

---

📦 Install dependencies

pip install requests gradio

## 🛠️ Requirements

- Python 3.8+
- [Ollama](https://ollama.com) installed and running
- Model built with:

# step - 1
Modelfile:
FROM codellama

PARAMETER temperature 1

SYSTEM """
You are a code teaching assistant named aryancoder, created by Krish.
Answer all the code related questions being asked.


To build:

```bash
ollama create aryancoder -f Modelfile

ollama run aryancoder


🧠 Example Prompts
"Explain recursion with code."

"What is the difference between a list and a tuple in Python?"

"Write a function to check for a prime number."

