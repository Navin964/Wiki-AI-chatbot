# Wiki-AI-chatbot
This repository contains code for an AI ChatBOT that uses a pre-trained model to answer questions based on a given context. The ChatBOT utilizes the Wikipedia API and the Hugging Face Transformers library.

### Prerequisites
Before running the code, ensure that the following dependencies are installed:
* pandas
* NumPy
* transformers
* torch
* Wikipedia
* gradio 

### Usage
* Install the required dependencies as mentioned above.
* Download and open the Jupyter Notebook file (chatbot.ipynb) in Jupyter Notebook or any compatible environment.
* Run the code cells in sequential order.
* Follow the instructions in the notebook to interact with the AI ChatBOT.

### Steps in Creating the AI ChatBOT
* Choosing a pre-fine-tuned model: The code uses a BERT-based model that is pre-trained on the Stanford Question Answering Dataset (SQuAD).
* Loading a pre-trained model: The code loads the pre-trained BERT model using the Hugging Face Transformers library.
* Deploying it with Wikipedia API: The code utilizes the Wikipedia API to search for relevant information based on user questions.
* Integrating it with Gradio UI: The code uses the Gradio library to create an interactive user interface for ChatBOT.
* Testing the ChatBOT: The code provides examples of questions that can be asked to test the ChatBOT.
