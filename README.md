## Multi-doc Summarizer app

# Overview

Multi-doc Summarizer is a Streamlit-based web application that allows users to upload documents in various formats (PDF, DOCX, PPTX, TXT) and generate concise summaries using Google's Gemini API.

# Features

Supports multiple document formats: PDF, DOCX, PPTX, and TXT.

Extracts text content from uploaded documents.

Uses Google's Gemini API for AI-generated summaries.

Customizable summary length using a word limit slider.

User-friendly Streamlit interface for easy interaction.

# Technologies Used

Python: Core programming language.

Streamlit: Web framework for building interactive applications.

PyMuPDF: Extract text from PDF files.

python-docx: Extract text from DOCX files.

python-pptx: Extract text from PPTX files.

Google Generative AI (Gemini): For text summarization.

dotenv: Load API keys securely.

## Installation

# Prerequisites

Ensure you have Python installed on your system.

# Steps

Clone the repository:

git clone https://github.com/your-repo/multi-doc-summarizer.git
cd multi-doc-summarizer

Install dependencies:

pip install -r requirements.txt

Set up your API key:

Create a .env file in the root directory.

Add your Google API key:

GOOGLE_API_KEY=your_api_key_here

Run the application:

streamlit run app.py

# Usage

Upload a document (PDF, DOCX, PPTX, or TXT).

Choose the maximum summary word count using the slider.

Click the "Summarize Content" button to generate a summary.

View the summarized text displayed on the screen.




