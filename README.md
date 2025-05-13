# LLM-streamlit-app
# Student Data Extractor using LLMs (PDF & Image Files)

This project is a Streamlit-based web application designed to extract structured student information from image and PDF documents using state-of-the-art Large Language Models (LLMs).

##  Overview

The app integrates two powerful vision-language models:

- **[Gemini 1.5 Flash (Google)]** – fast and capable of processing complex documents.
- **[LLaMA 3.2 11B Vision Instruct (Unsloth)]** – efficient and open-source, great for vision-based document understanding.

It allows users to upload student-related files (e.g., scanned certificates, forms, or grade reports) and extract structured data like names, student IDs, grades, etc.

##  Features

-  Accepts both **PDF** and **image (JPG/PNG)** formats.
-  Uses LLMs to extract structured data without requiring manual templates.
-  Secure integration using encrypted API keys and ngrok tokens.
-  Supports loading files directly from **Google Drive**.
-  Displays extracted data in a clean, tabular format with download options.
-  Merging the extracted data of student ID's with a list of the original ID's
-  Result are available as a downloadable CSV , all record also save to a local SQLite database 



