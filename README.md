# 🤖 CodeWise Bot: Your Knowledgeable AI Assistant 📚

Welcome to CodeWise Bot, the smart chatbot that turns your documents into a wealth of knowledge! Powered by Llama 2, Langchain, and FAISS, CodeWise Bot is your go-to assistant for finding answers, extracting insights, and navigating through large datasets with ease. Let’s dive into how you can set up and start using this powerful bot! 🚀

## 📑 Table of Contents

- [🌟 Introduction](#CodeWise-Bot:-Your-Knowledgeable-Assistant)
- [⚙️ Prerequisites](#prerequisites)
- [🔧 Installation](#installation)
- [🚀 Getting Started](#getting-started)
- [💬 Usage](#usage)
- [💡 Contributing](#contributing)
- [📜 License](#license)

## 🌟 Introduction

CodeWise Bot is an advanced AI-driven assistant that helps you search, query, and interact with your documents in an intuitive chat interface. It uses semantic search to extract relevant information quickly, thanks to the power of Llama 2 and FAISS.

✨ Features:

-💬 Chat with your documents like never before.
-🔍 FAISS-powered search for lightning-fast document retrieval.
-🚀 Built with Langchain for seamless integration and scalability.
-🧠 Llama 2 models for high-quality, natural conversations.
-📦 Easy to deploy and extend with new data sources.

## ⚙️ Prerequisites

Before you can jump into the world of CodeWise Bot, make sure your environment meets the following requirements:

-Python 3.6 or higher 🐍
-Install the following Python libraries (use the `requirements.txt` for quick installation):
    -`langchain` 🧠
    -`chainlit` 💬
    -`sentence-transformers` 🔡
    -`faiss-cpu` 🏎️
    -`PyPDF2` 📄
    -`huggingface_hub` 💻

 ## 🔧 Installation  

Let's get you set up so you can start using CodeWise Bot in no time: 

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/codewise-bot.git
    cd codewise-bot
    ```

2. Set up a Python virtual environment(optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the necessary models and data:

-Get your pre-trained models and any other resources (like FAISS indices) by following Langchain’s setup guides.

-Don’t forget to update `DB_FAISS_PATH` and other configuration paths in the code.

## 🚀 Getting Started

To launch your CodeWise Bot:

1. Follow the Installation steps to prepare your environment.

2. Update configuration files, particularly paths to your FAISS vector store and language models.

3. Add your documents (e.g., PDFs, text files) and load them into the FAISS database.

4. Run the bot by executing the Python script or integrating it into your app for easy querying.

## 💬 Usage

CodeWise Bot is super simple to use! Here’s how:

1. Start the bot by running the Python script or using your preferred method of deployment.

2. Ask anything about the documents you’ve ingested.

3. The bot will retrieve the most relevant information and give you an insightful response.

4. If there are source references, they will be included for better context.

5. Want to extend the bot? Add new documents, tweak the configurations, and expand its capabilities!

## 💡 Contributing

We ❤️ contributions! If you'd like to make CodeWise Bot even better, here’s how you can get involved:

1. Fork the repository to your own GitHub account.

2. Create a new branch for your feature or bug fix.

3. Make your changes and ensure all tests are passing.

4. Submit a pull request with a description of your changes.

5. If everything looks good, we’ll merge your pull request!

Let's build something amazing together! 🌟

## 📜 License

This project is licensed under the MIT License. Feel free to use and modify CodeWise Bot to fit your needs.

---

Thank you for choosing CodeWise Bot! 🎉 Whether you’re a developer, researcher, or curious learner, this bot will make your document exploration easier and more efficient than ever before! Happy coding! 🚀
