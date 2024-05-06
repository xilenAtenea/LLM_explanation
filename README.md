# LLM: Question-answering with RAG

## Introduction
Welcome to the LLM EXplanation repository!

This project is dedicated to providing a detailed understanding of the creation and operation of an LLM (Large Language Model) designed to answer questions from students, teachers and collaborators at the Universidad Autónoma de Occidente in Cali, Colombia.

Using the LangChain framework and Ollama, an initial prototype has been developed using publicly available information in informative PDF documents and an official university website as data sources.

It is important to note that since this is an initial prototype, a limited amount of information has been used. The main objective of this project is to understand how the model works, how it must be created to work properly, the implemented RAG (Retrieval Augmented Generation) structure and, in general, how to implement the project in a functional way.

The repository includes a detailed notebook that explains some concepts considered key and shows the process of creating the model along with some images that provide visual support. In addition, we are working on an additional repository that will be available soon, which will contain the complete implementation of the model together with the necessary documentation for its use and execution.

Please note that this current repository is designed for educational and explanatory purposes only. We do not provide detailed instructions on how to use it or detail prerequisites, as its main purpose is to provide an in-depth understanding of how the model works.

## Repository Structure

#### img/
This folder contains the images used in the notebook. Its purpose is to allow the visualisation of the images within the repository, as without them, the understanding of the content of the notebook would be limited.

#### pdf_qa_CV.ipynb
This notebook is the heart of the project. It contains the code and detailed step-by-step explanations of how the model was created and works for question answering. In addition to showing images to facilitate the understanding of the topic, it also includes tests performed to validate the functioning of the model.

Remember that an additional repository will be released very soon that will allow you to run the project, perform your own tests and modify it according to your needs. 

## References
The images used in this project were obtained from [here](https://medium.com/@onkarmishra/using-langchain-for-question-answering-on-own-data-3af0a82789ed), which provides visual resources relevant to the content presented in the notebook.

The initial code was based on this [link](https://medium.com/@Sanjjushri/rag-pdf-q-a-using-llama-2-in-8-steps-021a7dbe26e1). It is important to note that one of the key differences in this implementation is the incorporation of Llama3. A way was found to integrate it with the existing code, which improved the performance and functionality of the model. For more details on this integration, see link_to_the_complete_explanation.
