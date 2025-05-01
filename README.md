<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OCR & Audio App</title>
</head>

<body>
    <h1>OCR & Audio Conversion App</h1>
    <p><strong>OCR & Audio App</strong> is a Streamlit-based web application that enables users to extract text from images
        and PDFs through Optical Character Recognition (OCR) and convert the extracted text to speech using OpenAI's
        Text-to-Speech (TTS) service.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>OCR Text Extraction:</strong> Extract text from image and PDF files using the Mistral API.</li>
        <li><strong>Text to Audio Conversion:</strong> Convert the extracted text into speech using OpenAI's TTS API.</li>
        <li><strong>Multiple Input Sources:</strong> Supports both local file upload and URL input for images and PDFs.</li>
        <li><strong>Output Folder:</strong> Allows saving the extracted text and audio files locally in the user-defined folder.</li>
        <li><strong>Editable OCR Results:</strong> Users can edit the extracted text before saving or converting to audio.</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository: 
            <pre>git clone https://github.com/your-username/ocr-audio-app.git</pre>
        </li>
        <li>Navigate into the project directory: 
            <pre>cd ocr-audio-app</pre>
        </li>
        <li>Install the required dependencies:
            <pre>pip install -r requirements.txt</pre>
        </li>
        <li>Run the app:
            <pre>streamlit run app.py</pre>
        </li>
    </ol>

    <h2>Usage</h2>
    <p>Once the app is running, open the URL in your browser. The app has two main functionalities:</p>
    <h3>1. OCR Text Extraction</h3>
    <p>Enter your Mistral API Key and select the file type (PDF or Image). You can upload files locally or provide URLs
        for the app to extract text using OCR. Once processed, you can preview and edit the extracted text.</p>

    <h3>2. Text to Audio Conversion</h3>
    <p>After extracting the text using OCR, you can convert the text to speech using OpenAI's TTS service. Select a voice
        style, then download the audio or save it to your defined output folder.</p>

    <h2>API Integration</h2>
    <p>This app uses two external APIs:</p>
    <ul>
        <li><strong>Mistral API:</strong> For Optical Character Recognition (OCR) to extract text from images and PDFs.</li>
        <li><strong>OpenAI API:</strong> For converting extracted text to speech (Text-to-Speech).</li>
    </ul>

    <h2>Folder Structure</h2>
    <pre>
    ├── app.py                 # Main Streamlit app script
    ├── requirements.txt       # List of required Python dependencies
    └── README.md              # This README file
    </pre>

    <h2>Contributing</h2>
    <p>If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.
        Make sure to follow the existing code structure and style conventions.</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2>Contact</h2>
    <p>For any questions or issues, feel free to contact me through GitHub or email at your-email@example.com.</p>

</body>

</html>
