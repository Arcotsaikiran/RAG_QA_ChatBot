# Conversational Q&A Chatbot with PDF Integration

This project is a **Conversational Q&A Chatbot** built with **Streamlit**, **LLM** (**Google Gemini AI**), and **FAISS**, designed to allow users to upload PDF documents, extract their content, and ask questions based on the context of those documents.

---

## Features
- Upload multiple PDF files and process their content.
- Extract text from PDFs and split it into manageable chunks.
- Utilize Google Generative AI for embedding and question-answering.
- Store text embeddings in a local FAISS index.
- Provide context-based, conversational answers to user questions.

---

## Installation

### Prerequisites
- Python 3.8 or higher.
- An active **API Key** 
- Required Python libraries installed. Install them using:

```bash
pip install -r requirements.txt

```



### Before Uploading Files

The initial state of the app, where users can upload their PDF files.

![2](https://github.com/user-attachments/assets/1478840e-e4be-49b9-85b1-06a22685288a)

---

### Upload Files

Upload your documents using the "Browse files" and click on "Submit & Process".

![3](https://github.com/user-attachments/assets/330f5852-7093-4025-a18a-75f604bc042b)


---


### After Uploading Files
Once PDF files are uploaded and processed, users can start asking questions.

![4](https://github.com/user-attachments/assets/1c8655c3-7d0b-4a7e-9a26-196dadb40373)

---
