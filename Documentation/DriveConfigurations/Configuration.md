
# Drive Insights Web Application Documentation

This documentation provides a step-by-step guide on using the **Drive Insights** web application, covering configuration creation, media pre-processing, and dashboard navigation.

<video controls autoplay loop muted width="100%">
    <source src="../images/Drives/DriveInsights_UIcut.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>



This documentation provides a step-by-step guide on using the **Drive Insights** web application, covering configuration creation, media pre-processing, and dashboard navigation.
---

## Table of Contents

1. [Introduction](#introduction)
2. [Creating a Configuration](#creating-a-configuration)
3. [Adding Folders to Configuration](#adding-folders-to-configuration)
4. [Selecting Pre-Processing Techniques](#selecting-pre-processing-techniques)
    - [Images](#images)
    - [Documents (PDFs)](#documents-pdfs)
    - [Audio](#audio)
    - [Videos](#videos)
5. [Dashboard Overview](#dashboard-overview)
6. [Sample Screenshots](#sample-screenshots)

---

## 1. Introduction

The **Drive Insights** application enables users to create configurations for analyzing various media types, including images, documents, audio, and video files. Configurations streamline document and media processing by associating each configuration with specific pre-processing models.

---

## 2. Creating a Configuration

To create a new configuration:

1. Navigate to the **Configurations** tab from the sidebar.
2. Click on the **Configure Drive** button.
3. Enter the **Configuration Name**.
4. Select the **Files** type (e.g., images, documents).
5. Choose a **Keyword Model** that matches your needs (e.g., `sentence-transformer/all-MiniLM-L6-v2`).
6. Click **Save** to add the new configuration to the list.

![Configuration Screenshot](../images/Drives/Picture%201.png)

---

## 3. Adding Folders to Configuration

Once a configuration is created, you can add folders that will be analyzed under this configuration.

1. Select the configuration you wish to add folders to.
2. Click on **Add Folder** and select the directory containing the files you want to process.
3. Click **Save** to confirm.

![Adding Folders](../images/Drives/Picture%202.png)

---

## 4. Selecting Pre-Processing Techniques

For each file type, specific pre-processing techniques can be applied to ensure optimal processing and analysis. This section details the pre-processing options available for each media type.

### Images

For images, the following pre-processing techniques are available:

- **Resize**: Adjusts image dimensions.
- **Compression**: Reduces file size for faster processing.
- **OCR**: Extracts text from images.
<!-- 
![Image Pre-Processing](./images/Drives/Picture%203.png) -->

### Documents (PDFs)

Documents such as PDFs can be pre-processed with the following options:

- **Text Extraction**: Extracts text content from PDFs.
- **Optical Character Recognition (OCR)**: Useful for scanned documents.
- **Keyword Highlighting**: Identifies and highlights relevant keywords.
<!-- 
![PDF Pre-Processing](./images/Drives/Picture%204.png) -->

### Audio

For audio files, you can apply:

- **Speech-to-Text Conversion**: Transcribes audio content.
- **Noise Reduction**: Enhances clarity of audio by reducing background noise.

<!-- ![Audio Pre-Processing](./images/audio_preprocessing.png) -->

### Videos

Video files have the following pre-processing techniques:

- **Frame Extraction**: Extracts key frames for analysis.
- **Speech-to-Text**: Converts spoken content in videos to text.
- **Object Detection**: Identifies objects within video frames.

<!-- ![Video Pre-Processing](./images/video_preprocessing.png) -->

---

## 5. Dashboard Overview

The dashboard provides a comprehensive view of configuration metrics, processed records, and visual insights.

1. Navigate to the **Dashboard** tab to access the summary.
2. Select a configuration and folder to view detailed data analytics.
3. Visual elements include:
   - **Record Count**: Displays the total number of processed files.
   - **Model vs Label**: Shows the distribution of classifications.
   - **File Types**: Visualizes different file formats processed in the selected configuration.

![Dashboard Overview](../images/Drives/Picture%203.png)

---

## 6. Sample Screenshots

Below are sample screenshots for easy reference. 

1. **Configuration Page**  
   ![Configuration Example](../images/Drives/Picture%204.png)

2. **Folder Selection**  
   ![Folder Selection](../images/Drives/Picture%205.png)

3. **Dashboard with Analytics**  
   ![Dashboard Analytics](../images/Drives/Picture%206.png)

---
=