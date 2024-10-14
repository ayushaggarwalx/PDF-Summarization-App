
# PDF Summarization App

The PDF Summarization App is a user-friendly web application built using the Streamlit framework and Hugging Face Transformers library. This app allows users to upload PDF files and generate concise summaries of their content using using the Lamini Flan T5 language model. This powerful open-source model has 248 million parameters and is fine-tuned on the T5 architecture by Google.

## Lamini Flan T5: A Powerful Language Model ![Logo](https://miro.medium.com/v2/resize:fit:908/0*GWUPZyMXUv3HjD03.png)


Lamini Flan T5 is an underrated language model that was released by Google a few years ago. With 248 million parameters, it is smaller compared to other large-Scale language models available today. Despite its size, Lamini Flan T5 is capable of generating high-quality summaries and text generation. We will be utilizing the summarization pipeline of this model in our Streamlit application.

## Setting Up the Environment

Before building the Streamlit application, we need to set up the required environment. This includes installing the necessary libraries and dependencies, such as Transformers, Torch, and Streamlit. We will also download and store the Lamini Flan T5 model locally, as we do not require any API keys for this open-source model.

## Uploading and Preprocessing the PDF File

To enable document summarization, the application will allow users to upload PDF files. We will utilize the capability of Streamlit to handle file uploads and preprocess the uploaded PDF files using the Langchain library. The Langchain library provides functionality for text splitting and document loading, which will be utilized to extract the content of the PDF files.

## Utilizing the Lamini Flan T5 Model for Summarization

Once the PDF file is uploaded and preprocessed, we will leverage the Lamini Flan T5 language model for summarization. We will use the summarization pipeline provided by the model to generate concise summaries of the uploaded documents. The pipeline takes the preprocessed text as input and returns the summarization as output.

## Displaying the Summarized Text

The summarization generated by the Lamini Flan T5 model will be displayed to the user in the Streamlit application. We will utilize the interactive components of Streamlit to Create a user-friendly interface that presents the summaries in a readable format. The application will also provide options for downloading or sharing the summaries.

## Testing the Streamlit Application

To ensure the functionality and performance of the Streamlit application, we will conduct thorough testing. This will involve uploading different PDF documents and verifying the accuracy and coherency of the generated summaries. We will also assess the responsiveness and user experience of the application.


## Acknowledgements

 - [MBZUAI/LaMini-Flan-T5-248M](https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M)
 - [LaMini-LM: A Diverse Herd of Distilled Models from Large-Scale Instructions(Research Paper)](https://arxiv.org/pdf/2304.14402)
