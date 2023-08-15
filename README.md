# Speak Spectrum

Speak Spectrum is a tool designed to process video inputs, delivering precise text analytics and transcripts by leveraging Microsoft Azure's Speech Analytics and SpeechToText services.

## 🎥 Demo

[![Speak Spectrum Demo](https://cfvod.kaltura.com/api_v3/index.php/service/thumbAsset/action/serve/thumbAssetId/1_80zfflj4/v/11/ks/MzFmOWJkMDJhM2EyYzk1MzZmOWMwYTU1YjQzN2YyOGY4Yzc0NDYxMXwzOTEyNDE7MzkxMjQxOzE2OTIyMTA2MDA7MDsxNjkyMjEwNjAwOztkb3dubG9hZDoxXzd4aGt0MjJ2LGRpc2FibGVlbnRpdGxlbWVudGZvcmVudHJ5OjFfN3hoa3QyMnYsc3ZpZXc6MV83eGhrdDIydixkb3dubG9hZGFzc2V0OjFfODB6ZmZsajQ7Ow==)](https://media.oregonstate.edu/media/t/1_7xhkt22v)

> Click on the image above to view the Speak Spectrum demo.

## Features

- **Video Input Support**: Easily upload your videos and let Speak Spectrum do the heavy lifting.
- **Azure-Powered Transcription**: High-accuracy transcription of video content using Azure's SpeechToText service.
- **Text Analytics**: In-depth analysis of transcripts to identify key trends, terms, and insights.
- **Intuitive User Interface**: A clean and user-friendly interface built with Angular to access and manage your video transcripts and analytics.

## Getting Started

### Prerequisites

1. Node.js
2. Angular CLI
3. Microsoft Azure account with access to Speech Analytics and SpeechToText services.

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/KedarDhere/SpeakSpectrum
    cd speak-spectrum
    ```

2. **Backend Setup**
    ```bash
    npm install
    ```

    Create a `.env` file in the `backend` folder and set your Azure credentials:

    ```
    AZURE_SPEECH_KEY=YOUR_AZURE_SPEECH_KEY
    AZURE_TEXT_ANALYTICS_KEY=YOUR_AZURE_TEXT_ANALYTICS_KEY
    ```

    Start the server:
    ```bash
    npm start
    ```

3. **Frontend Setup**
    ```bash
    npm install
    ng serve
    ```

    Your frontend should now be running on `http://localhost:4200/`.

## Usage

1. **Upload Video**: Use the upload button to select and submit your video file.
2. **View Transcript**: Once processing is complete, you can view the video's full transcript.
3. **Text Analytics**: Navigate to the analytics section to view in-depth insights derived from the video transcript.

## Acknowledgments

- Microsoft Azure for their powerful Speech Analytics and SpeechToText services.
- All contributors who have helped in bringing this project to life.

---
