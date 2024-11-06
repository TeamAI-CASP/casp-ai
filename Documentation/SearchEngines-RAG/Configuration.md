


# Search Engine RAG - Q&A System Documentation

<video controls autoplay loop muted width="100%">
    <source src="../images/QnA/QnA_SearchEngine_ UIcut.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>


This documentation provides a detailed guide on configuring the **Q&A System** in Drive Insights, covering model selection, retriever and reader configuration, and integration of complex question-answering models using the Hugging Face repository.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Q&A Model Setup](#qa-model-setup)
    - [Selecting the RAG Model](#selecting-the-rag-model)
    - [Configuring the Retriever](#configuring-the-retriever)
    - [Configuring the Reader](#configuring-the-reader)
3. [Dashboard Overview](#dashboard-overview)
4. [Sample Screenshots](#sample-screenshots)

---

## 1. Introduction

The **Drive Insights Q&A System** allows users to configure a question-answering model tailored to their needs, leveraging advanced retrievers and readers. With access to models from the Hugging Face repository, users can customize configurations for efficient information retrieval and complex question answering.

---

## 2. Q&A Model Setup

### Selecting the RAG Model

To set up a Retrieval-Augmented Generation (RAG) model:

1. Navigate to the **Q&A** section from the sidebar.
2. Select the desired RAG model from the dropdown, which includes models integrated from the Hugging Face repository.
3. Save the selection to apply the model to your configuration.

![RAG Model Selection](../images/QnA/Picture%201.png)

---

### Configuring the Retriever

The retriever is responsible for identifying relevant documents to answer user queries. To configure the retriever:

1. Go to **Retriever Settings** within the Q&A configuration.
2. Choose from various retrievers such as **BM25**, **DPR (Dense Passage Retriever)**, **Embedding-based**, or **Hybrid retrievers**.
3. Adjust specific parameters for your selected retriever, such as similarity metrics, embedding dimensions, and batch sizes.
4. Save your configuration.

![Retriever Configuration](../images/QnA/Picture%202.png)

---

### Configuring the Reader

The reader processes the content retrieved by the retriever to generate precise answers. To configure the reader:

1. Go to **Reader Settings** under the Q&A configuration.
2. Select a reader model from Hugging Face (e.g., `facebook/bart-large`, `deepset/roberta-base-squad2`).
3. Define parameters like `max sequence length`, `top-k results`, and other relevant settings.
4. Save the configuration to finalize your reader setup.

![Reader Configuration](../images/QnA/Picture%203.png)

---

## 3. Dashboard Overview

The dashboard provides an overview of the Q&A performance metrics and insights. 

1. Select the Q&A configuration from the **Dashboard**.
2. Review the **Model vs Label** metrics, displaying a comparison of actual labels versus predicted labels.
3. Explore **File Types** processed, **Answer Accuracy**, and **Retriever-Reader Response Time** for a comprehensive performance analysis.

![Q&A Dashboard](../images/QnA/Picture%204.png)

---

## 4. Sample Screenshots

Here are sample screenshots demonstrating the Q&A configuration steps and dashboard metrics.

1. **RAG Model Selection**  
   ![RAG Model Example](../images/QnA/Picture%201.png)

2. **Retriever Configuration**  
   ![Retriever Configuration Example](../images/QnA/Picture%202.png)

3. **Reader Configuration**  
   ![Reader Configuration Example](../images/QnA/Picture%203.png)

4. **Q&A Dashboard**  
   ![Dashboard Analytics](../images/QnA/Picture%204.png)

5. **File Insights**
    ![Dashboard Analytics](../images/QnA/Picture%205.png)

---
