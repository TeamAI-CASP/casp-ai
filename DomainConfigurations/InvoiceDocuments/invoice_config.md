# Configuration Overview

This document provides an overview of the configuration settings for the specified system.

## Configuration Name
**Configuration Name:** `configuration_name`

## Mount Configuration
The mount configuration settings specify how and where to mount data for processing.

- **Mount Type:** Azure
- **Mount Script:** cds-mount-script
- **Database Name:** marqo_images
- **NER Models:**
  - `en_core_web_lg`
  - `en_core_web_eg`
  - [SpaCy Models](https://spacy.io/usage/models)
- **Document Types:**
  - images
  - documents
  - videos
  - audios
- **Folder Depth:** 6
- **Environment:** qna
- **Keyvault Enabled:** true
- **Machine Password:** bot
- **File Scan Enabled:** false
- **Force Scan Enabled:** false
- **Folders to Mount:**
  - `/mnt/documents/jnj`
  - `/mnt/documents/zf`

## Keyword Configuration
The keyword configuration settings specify the models and parameters for keyword extraction.

- **Keyword Models:**
  - `sentence-transformers/all-MiniLM-L6-v2`
- **N-grams:** 3
- **Diversity:** 0.7
- **Use MMR:** true
- **Keyword Limit:** 10
- **Quantize:** true
- **Layout Model:** PaddleGPU
- **Keypair Model:** Azure
- **Speech Models:** (empty)
- **Speech Sampling Rate:** 16000
- **Speech Quantize:** true
- **Object Detection Models:**
  - `facebook/detr-resnet-50`
  - `google_formparser`
- **Object Detection Quantize:** true
- **Classification Models:** (empty)
- **Classification Quantize:** true
- **Key-Value Models:**
  - `to-be/donut-base-finetuned-invoices`
- **Key-Value Quantize:** true
- **Zero-Shot Models:** (empty)
- **Zero-Shot Quantize:** true
- **OCR Selection:**
  - Tesseract
  - Paddle
  - easyocr
  - AzureFormParser
  - GoogleDocumentAI
  - HandWrittenERecognizer
- **Table Selection:**
  - Paddle
  - Camelot
  - AzureFormParser
  - GoogleDocumentAI
- **Translator Selection:**
  - mtranslate
  - AzureFormParser
  - GoogleDocumentAI

## Text Configuration
The text configuration settings specify how to process and clean text data.

- **Classification Sample:** 10
- **Page Limit:** 5
- **Clean Empty Lines:** true
- **Clean Whitespace:** true
- **Clean Header/Footer:** true
- **Split By:** word
- **Split Length:** 0
- **Split Respect Sentence Boundary:** true
- **Split Overlap:** 0
- **Sample Text:**
  ```plaintext
  It’s difficult to say without more information about what the code is supposed to do and what’s happening when it’s executed. One potential issue with the code you provided is that the resultWorkerErr channel is never closed,

## Marqo Configuration
The Marqo configuration settings specify how to process images.

- **Image Model:** ViT-L/14
- **Normalize Image:** true

## Invoice Example

![Extracted Invoice](Invoice_img.png)

### Explanation of Extracted Fields

- **Bill To:** Aaron Bergman
- **Ship To:** 98103, Seattle, Washington, United States
- **Date:** Mar 06 2012
- **Ship Mode:** First Class
- **Balance Due:** $50.10
- **Item:** 
  - **Description:** Global Push Button Manager's Chair, Indigo
  - **Category:** Chairs, Furniture, FUR-CH-4421
- **Quantity:** 1
- **Rate:** $48.71
- **Amount:** $48.71
- **Subtotal:** $48.71
- **Discount:** $9.74 (20%)
- **Shipping:** $11.13
- **Total:** $50.10
- **Notes:** Thanks for your business
- **Order ID:** CA-2012-AB101015140-40974

This image showcases an invoice with various fields extracted and highlighted. The extracted fields include billing and shipping information, invoice details such as date and shipping mode, item details, pricing, and additional notes. This structured extraction enables efficient processing and analysis of invoice data.