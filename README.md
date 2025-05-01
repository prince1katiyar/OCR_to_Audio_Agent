# OCR & Audio Conversion App

**OCR & Audio App** is a Streamlit-based web application that enables users to extract text from images and PDFs through Optical Character Recognition (OCR) and convert the extracted text to speech using OpenAI's Text-to-Speech (TTS) service.

## Features

- **OCR Text Extraction:** Extract text from image and PDF files using the Mistral API.
- **Text to Audio Conversion:** Convert the extracted text into speech using OpenAI's TTS API.
- **Multiple Input Sources:** Supports both local file upload and URL input for images and PDFs.
- **Output Folder:** Allows saving the extracted text and audio files locally in the user-defined folder.
- **Editable OCR Results:** Users can edit the extracted text before saving or converting to audio.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ocr-audio-app.git
    ```

2. Navigate into the project directory:
    ```bash
    cd ocr-audio-app
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the app:
    ```bash
    streamlit run app.py
    ```

## Usage

Once the app is running, open the URL in your browser. The app has two main functionalities:

### 1. OCR Text Extraction

Enter your Mistral API Key and select the file type (PDF or Image). You can upload files locally or provide URLs for the app to extract text using OCR. Once processed, you can preview and edit the extracted text.

### 2. Text to Audio Conversion

After extracting the text using OCR, you can convert the text to speech using OpenAI's TTS service. Select a voice style, then download the audio or save it to your defined output folder.

## API Integration

This app uses two external APIs:

- **Mistral API:** For Optical Character Recognition (OCR) to extract text from images and PDFs.
- **OpenAI API:** For converting extracted text to speech (Text-to-Speech).

## Folder Structure

```bash
├── app.py                 # Main Streamlit app script
├── requirements.txt       # List of required Python dependencies
└── README.md              # This README file
