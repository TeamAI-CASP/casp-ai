## NER Models

| Model                                           | Description                                                                                                   | Use Case                                                    |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| `en_core_web_lg`                                | Large English model provided by SpaCy. It has higher accuracy due to more parameters and training data.       | Suitable for tasks requiring high accuracy in NER.          |
| `en_core_web_eg`                                | A custom or experimental model with specific enhancements for certain tasks or datasets.                      | Useful for specialized NER tasks with unique requirements.  |
| [SpaCy Models](https://spacy.io/usage/models)   | A collection of models available on SpaCy's website, covering various languages and use cases.                | General purpose, depending on the chosen model.             |

## Keyword Models

| Model                                      | Description                                                                                                      | Use Case                                                      |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| `sentence-transformers/all-MiniLM-L6-v2`   | A pre-trained model from Sentence-Transformers library, designed for efficient sentence embeddings.              | Ideal for extracting meaningful keywords from text for various NLP tasks like information retrieval and clustering. |

## Object Detection Models

| Model                      | Description                                                                                     | Use Case                                                    |
|----------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| `facebook/detr-resnet-50`  | DEtection TRansformer (DETR) model with ResNet-50 backbone by Facebook AI. It combines CNNs with Transformers for object detection. | Ideal for general object detection tasks, offering accurate bounding boxes and class labels.          |
| `google_formparser`        | A model designed by Google for parsing and extracting information from forms.                   | Suitable for extracting structured data from form documents, such as invoices, receipts, and other form-based inputs.  |

## Key-Value Models

| Model                                      | Description                                                                                                      | Use Case                                                    |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| `to-be/donut-base-finetuned-invoices`      | A model fine-tuned for extracting key-value pairs from invoice documents. It is based on the DONUT architecture. | Ideal for users needing to extract structured information from invoices for financial processing and record-keeping. |

## OCR Models

| Tool               | Description                                                                                          | Use Case                                                                                      | Open-Source or Paid            |
|--------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| Tesseract          | Open-source OCR engine known for its accuracy in recognizing text from images and documents.         | Suitable for general OCR tasks, especially when integrating with other systems.               | Open-Source                    |
| Paddle OCR         | OCR toolkit based on PaddlePaddle framework, offering robust text detection and recognition.         | Ideal for deep learning-based OCR tasks, providing high accuracy in various scenarios.        |Open-Source                    |
| easyocr            | Python package for OCR that supports over 80 languages and offers pre-trained models for text extraction. | Useful for multilingual OCR tasks and quick implementation of OCR in Python applications.    | Open-Source                    |
| AzureFormParser    | Part of Microsoft Azure's cognitive services, specialized in extracting key-value pairs from forms. | Suitable for extracting structured data from various types of forms and documents.           | Paid (Azure Subscription Required)  |
| GoogleDocumentAI   | Google's AI-powered service for document processing, capable of extracting text and structured data. | Ideal for integrating with Google Workspace applications and handling complex document workflows. | Paid (Google Cloud Pricing)         |
| HandWrittenERecognizer | A tool designed for recognizing handwritten text and converting it into digital format.             | Useful for tasks requiring OCR on handwritten documents or notes, providing specialized support. | Open-Source                    |

## Table Models

| Tool              | Description                                                                                          | Use Case                                                                                      |Open-Source or Paid            |
|-------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| Paddle            | A toolkit that provides table detection and extraction capabilities using deep learning models.     | Ideal for extracting tables from documents with complex layouts and varying structures.        |Open-Source                    |
| Camelot           | A Python library that offers table extraction from PDFs using heuristics and PDF parsing techniques.| Suitable for extracting tables from PDF documents with structured layouts and simple formats. |Open-Source                    |
| AzureFormParser   | Part of Microsoft Azure's cognitive services, specialized in extracting tables from documents.       | Useful for extracting tables from various types of documents and integrating with Azure services. | Paid (Azure Subscription Required)  |
| GoogleDocumentAI  | Google's AI-powered service for document processing, capable of extracting tables from documents.    | Ideal for extracting tables from documents stored in Google Workspace and cloud environments. | Paid (Google Cloud Pricing)         |

## Translator Models

| Tool              | Description                                                                                          | Use Case                                                                                      | Open-Source or Paid            |
|-------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| mtranslate        | A Python package providing a simple interface for Google Translate API.                             | Useful for translating text between languages using Google's translation service.            | Open-Source                    |
| AzureFormParser   | Part of Microsoft Azure's cognitive services, capable of translating text using Azure services.      | Suitable for integrating translation capabilities into applications using Azure services.    | Paid (Azure Subscription Required)  |
| GoogleDocumentAI  | Google's AI-powered service for document processing, offering translation capabilities for text.      | Ideal for translating text within documents stored in Google Workspace and cloud environments.| Paid (Google Cloud Pricing)         |


## ViT-L/14 Image Model

| Description                                                                                                      | Use Case                                                      |
|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| ViT-L/14 (Vision Transformer - Large/14) is a deep learning model designed for image classification tasks. It utilizes the Transformer architecture, treating images as sequences of patches, achieving high accuracy in image recognition. | - Image Classification: Accurate categorization of images into predefined classes. <br>- Feature Extraction: Extraction of significant image features for tasks like object detection and segmentation. <br>- Transfer Learning: Adaptation of ViT-L/14 on specific datasets to customize image classification tasks. |

## QnA Models

| Model Type | Model Name                        | Description                                                                       | Use Case                                      |
|------------|-----------------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------|
| GPT Model  | gpt-3.5-turbo                     | A state-of-the-art language model developed by OpenAI, known for generating human-like text. | Text generation, conversation, and content creation. |
| Llama Model| meta-llama/Llama-2-7b-chat-hf     | A high-performance language model developed by Meta, optimized for chat and conversational tasks. | Conversational AI, chatbots, and interactive applications. |

### Retriever Model Information

| Model                  | Description                                                                                 | Use Case                                                   |
|------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------|
| `all-mpnet-base-v2`    | A pre-trained model designed for efficient and effective retrieval of relevant documents.   | Ideal for information retrieval tasks, such as search engines and question-answering systems. |
| `RetrieverOptions.BM25Retriever` | A probabilistic retrieval model based on the BM25 algorithm, effective for keyword-based search. | Ideal for document retrieval and information retrieval tasks where keyword matching is essential.     |


### Reader Model Information

| Model                          | Description                                                                                           | Use Case                                                       |
|--------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| `deepset/minilm-uncased-squad2`| A lightweight, fine-tuned model for question answering using the SQuAD2.0 dataset, optimized for speed.| Ideal for extracting precise answers from a given context.      |