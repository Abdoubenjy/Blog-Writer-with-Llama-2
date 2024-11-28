# Blog Writer with Llama 2 🤖

This project is a **Streamlit application** that generates blog content using the **Llama 2 language model**. It allows users to input a topic, specify a writing style, and set a word limit to generate blogs dynamically. The application leverages the `langchain` library and the `CTransformers` integration to interact with the Llama 2 model.

---

## 🚀 Features

- **Dynamic blog generation**: Specify a topic, target audience, and word count.
- **Interactive UI**: Built with Streamlit for a user-friendly experience.
- **Powered by Llama 2**: Utilizes a local Llama 2 model for content generation.
- **Customizable prompts**: Adaptable template to fine-tune blog content for different use cases.

---

## 🛠️ Installation

### Prerequisites
1. Python 3.9 or higher.
2. A compatible GPU or sufficient CPU resources to run the Llama 2 model.
3. The Llama 2 model file (`llama-2-7b-chat.ggmlv3.q8_0.bin`) placed in the `Model/` directory.

### Setup Instructions

1. **Create a virtual environment:**
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate

2. **Download the Llama 2 model:**
   Place the llama-2-7b-chat.ggmlv3.q8_0.bin file in the Model/ directory.

3. **Install dependecies:**
    pip install -r requirements.txt

4. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>

## 📂 Project Structure
.
├── Model/
│   └── llama-2-7b-chat.ggmlv3.q8_0.bin  # Llama 2 model file
├── app.py                                # Main Streamlit app script
├── requirements.txt                      # Python dependencies
└── README.md                             # Project documentation

## ⚙️ Dependencies

Key Python libraries used:

Streamlit - For building the interactive UI.
LangChain - To manage prompts and LLM integrations.
CTransformers - For running the Llama 2 model locally.


   


