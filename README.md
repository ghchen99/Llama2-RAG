# Streamlit App for Llama 2 - Retrieval Augmented Generation (RAG)

This Streamlit application integrates Meta's Llama 2 7b model for Retrieval Augmented Generation (RAG) with a user-friendly interface for generating responses based on large PDF files. The application utilizes Hugging Face transformers, llama index, and other dependencies to create an interactive experience.

<img width="809" alt="demo" src="https://github.com/ghchen99/Llama2-RAG/assets/56446026/5507404f-0a60-40ea-8a02-9a195a3dc62a">


## Getting Started

1. Hugging Face Token: Obtain your Hugging Face API token and update the auth_token variable within the code.

2. Run the Streamlit App: ```streamlit run app.py``` 

3. Upload PDF File: Use the "Upload a PDF file" section to upload a PDF document.

4. Input Your Prompt: Enter your prompt in the text input box provided.

5. Generate Responses: Press Enter to trigger the generation process. The application will query the Llama 2 model and provide responses based on the given prompt and the content of the uploaded PDF file.
   
**Notes**

The application requires an internet connection to interact with the Hugging Face model and related services.
