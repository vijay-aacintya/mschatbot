## Chatbot for PDF files with Persistent Directory

This project reads all the PDFs in the data folder, creates a vectorstore, and enables interaction with the content of these PDFs. You can add PDFs with any type of content and use the chat feature to ask questions and receive answers.

Understanding and complying with Microsoft Licensing Agreements can be quite challenging, often requiring an advanced understanding of complex terms. To help with this, I've included PDF agreements from various Microsoft licensing programs. Using this chatbot has been a humorous yet effective way to grasp and get quicker answers about these agreements.

However, I encountered some limitations. There were too many PDFs, and the free version of Groq restricted the number of tokens processed per minute and the size of the chunks. Consequently, I had to significantly reduce the number of files for processing. For this project, I used only three files from the website Microsoft Licensing Programs. If you can afford to increase your limits, you could potentially query the entire set of agreements using this tool.

## Features
**Website Interaction:** The chatbot uses LangChain and HuggingFace to interact with and extract information from various websites.<br>
**Large Language Model Integration:** Compatibility with models like GPT-4, Mistral, Llama2, and ollama. In this code I am using Llama2, but you can change it to any other model.<br>
**Streamlit GUI:** A clean and intuitive user interface built with Streamlit, making it accessible for users with varying levels of technical expertise.<br>
**Python-based:** Entirely coded in Python.<br>
**IDE:** Pycharm by JetBrains

In any project creating the virtual environment is critical, most of the errors originate there. So I have provided a comprehensive requirements.txt. Create your Virtual Environment using this file.

![mschatbot1](https://github.com/user-attachments/assets/8da06012-6e72-4871-897f-56cb4eb1709e)

![mschatbot2](https://github.com/user-attachments/assets/aad5f305-ba8a-4776-95c2-2216db714b0f)

![mschatbot3](https://github.com/user-attachments/assets/e878fd1f-8529-4578-b483-cf0e9310b693)

**Note:** This project is for educational and research purposes. Ensure to comply with the terms of use and guidelines of the utilized APIs and services.
