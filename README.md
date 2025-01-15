# Basic-RAG

## Introduction

This project is part of Project 1 for SOICT-HUST. Its goal is to develop a system based on Retrieval-Augmented Generation (RAG).  

Retrieval-Augmented Generation (RAG) addresses the limitations of traditional language models by combining their generative capabilities with document retrieval from external sources. When a question is provided, RAG retrieves relevant documents and integrates the retrieved content with the summarization and generation capabilities of large language models (LLMs) to deliver accurate and reliable answers.  

 
## Project Features

1. **Answering Questions in Vietnamese:**  
   The system is designed to support question-answering in Vietnamese, providing clear and concise responses.  

2. **Extracting Information from PDF Documents:**  
   Users can upload PDF documents (e.g., textbooks or study materials), and the system leverages RAG to search and extract answers effectively.  

## Installation and Usage  

### Step 1: Set up the Environment  
- Open the project notebook on Google Colab.  
- Connect to a GPU runtime  

### Step 2: Upload PDF Documents  
- Use the provided interface in the notebook to upload PDF files, or specify links to PDF resources.  

### Step 3: Run the Model  
- Execute the cells in the notebook sequentially to:  
  - Load and preprocess the PDF documents.  
  - Extract and retrieve relevant information.  
  - Load model and create a pipeline.
### Step 4: Enter Questions  
- Provide your question in the interactive input field within the notebook. Ensure that your question is relevant to the content of the uploaded PDF document for accurate results.

### Step 5: View the Results  
- The model will process your question and generate a response based on the information retrieved from the document. The answer will be displayed in the output field for you to review.

## Technologies Used

- **Programming Language:** Python  
- **Language Models:** Vicuna-7b-v1.5
- **PDF Processing Libraries:** PyPDF2 
- **Deployment Platform:** Google Colab  

