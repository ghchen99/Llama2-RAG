# Streamlit App for Llama 2 - Retrieval Augmented Generation (RAG)

This Streamlit application integrates Meta's Llama 2 7b model for Retrieval Augmented Generation (RAG) with a user-friendly interface for generating responses based on large PDF files. The application utilizes Hugging Face transformers, llama index, and other dependencies to create an interactive experience.

## Getting Started
Hugging Face Token: Obtain your Hugging Face API token and replace <YOUR_HUGGINGFACE_TOKEN> in the auth_token variable within the code.

1. Run the Streamlit App:

* ``` streamlit run app.py``` 

2. Upload PDF File:

* Use the "Upload a PDF file" section to upload a PDF document.

3. Input Your Prompt:

* Enter your prompt in the text input box provided.

4. Generate Responses:

* Press Enter to trigger the generation process. The application will query the Llama 2 model and provide responses based on the given prompt and the content of the uploaded PDF file.
Notes

The application requires an internet connection to interact with the Hugging Face model and related services.
