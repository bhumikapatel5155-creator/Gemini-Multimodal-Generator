# 🤖 Gemini Multimodal Content Generator

### AI-Powered Text, Image Prompt & Audio Generation Platform

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-FF4B4B)
![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini-4285F4)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 1. Project Overview

The **Gemini Multimodal Content Generator** is an AI-powered web application developed using Python, Streamlit, and Google's Gemini API.

The application provides a single platform for generating AI-based text, creating detailed image generation prompts, and converting written text into speech.

It integrates Generative AI and Text-to-Speech technology to simplify content creation through an interactive and user-friendly interface.

The application provides four major functionalities: Text Generation, Image Prompt Generation, Audio Generation, and Multi-Modal Generation.

## 🎯 2. Problem Statement

Creating different types of digital content often requires multiple applications and tools.

For example:
- Text generation requires an AI writing tool.
- Image creation requires a separate image generation platform.
- Audio narration requires a text-to-speech application.

Switching between different tools can make the content creation process less convenient.

This project addresses this problem by providing multiple content-generation capabilities through one web-based application.

## 🎯 3. Project Objectives

- Develop an interactive AI-powered content generation application.
- Integrate Google Gemini API for text generation.
- Generate detailed prompts for external AI image generators.
- Convert text into speech using Google Text-to-Speech.
- Combine multiple content-generation functionalities in one interface.
- Provide downloadable generated content.

## 🚀 4. Key Features

### 4.1 Text Generation

- Accepts user prompts as input.
- Uses Google Gemini API to generate AI-powered responses.
- Provides model selection.
- Allows users to download generated text.

### 4.2 Image Prompt Generator

- Accepts image ideas from users.
- Provides different art-style options.
- Supports quality-level selection.
- Uses Gemini to generate detailed image prompts.
- Provides links to external image-generation platforms.

**Note:** This module generates image prompts, not actual images.

### 4.3 Audio Generation

- Converts written text into speech.
- Uses Google Text-to-Speech (gTTS).
- Supports multiple languages.
- Provides an audio player.
- Allows users to download generated audio in MP3 format.

### 4.4 Multi-Modal Generation

- Accepts one input prompt.
- Generates text using Gemini.
- Creates an optimized image-generation prompt.
- Converts generated text into audio.
- Provides downloadable outputs.

## 🛠️ 5. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| Google Gemini API | AI text generation |
| Google GenAI SDK | Gemini API integration |
| gTTS | Text-to-speech conversion |
| HTML/CSS | Web presentation where applicable |

## 🏗️ 6. System Architecture

The application follows a modular architecture.

```text
             USER
               |
               v
       STREAMLIT INTERFACE
               |
               v
        USER INPUT / PROMPT
               |
       +-------+--------+
       |       |        |
       v       v        v
     TEXT    IMAGE     AUDIO
   GENERATION PROMPT  GENERATION
       |       |        |
       v       v        v
    GEMINI   GEMINI    gTTS
      API      API      |
       |       |        |
       v       v        v
    TEXT    DETAILED   AUDIO
   OUTPUT    PROMPT    OUTPUT
       |
       v
    DOWNLOAD
```

The multi-modal module combines these functionalities to generate multiple content types from one user prompt.

## ⚙️ 7. Working Methodology

**Step 1: User Input**

The user enters a prompt or text through the Streamlit interface.

**Step 2: Processing**

The application processes the input according to the selected functionality.

**Step 3: AI Integration**

For text and image-prompt generation, the application communicates with Google's Gemini API.

**Step 4: Audio Conversion**

The gTTS library converts the provided or generated text into speech.

**Step 5: Output Generation**

The application displays generated text, image prompts, and audio.

**Step 6: Download**

Users can download supported generated outputs.

## 📸 8. Application Screenshots

### Main Dashboard
![Main Dashboard](screenshot/main-dashboard.png)

### Text Generation
![Text Generation](screenshot/text-generation.png)

### Image Prompt Generation
![Image Prompt Generation](screenshot/image-generation.png)

### Audio Generation
![Audio Generation](screenshot/audio-generation.png)

### Multi-Modal Generation
![Multi-Modal Generation](screenshot/multi-model.png)

## 💻 9. Installation and Setup

### Prerequisites

- Python installed on your system.
- Internet connection.
- Google Gemini API key.
- Git installed.

### Step 1: Clone the Repository

```bash
git clone https://github.com/bhumikapatel5155-creator/Gemini-Multimodal-Generator.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Gemini-Multimodal-Generator
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
streamlit run gemini_multimodal_app.py
```

### Step 5: Configure API Key

Enter your Google Gemini API key in the sidebar of the application.

## 🔑 10. API Configuration

This application uses the Google Gemini API for AI-based text and image-prompt generation.

To obtain an API key:

1. Visit [Google AI Studio](https://aistudio.google.com/apikey).
2. Generate an API key.
3. Copy the key.
4. Enter it into the application's API key field.

**Security Note:** Never hardcode or publicly upload your API key. Keep credentials private.

## 📂 11. Project Structure

```text
Gemini-Multimodal-Generator/
│
├── gemini_multimodal_app.py
│
├── requirements.txt
│
├── README.md
│
├── .gitignore
│
└── screenshots/
    └── main-dashboard.png
```

## ⚠️ 12. Limitations

- Text and image-prompt generation depend on Gemini API availability.
- API usage may be subject to rate limits and quotas.
- Image generation is not directly implemented; the application generates prompts for external image generators.
- Audio quality and language support depend on the gTTS service.
- Internet connectivity is required for online API services.

## 🔮 13. Future Enhancements

- Integrate direct AI image generation.
- Add more advanced audio customization.
- Improve user interface and user experience.
- Add user authentication and content history.
- Introduce additional AI models.
- Improve API error handling and response management.

## 📚 14. Learning Outcomes

Through this project, I gained practical experience in:

- Python application development.
- Integrating external APIs.
- Working with Generative AI.
- Building interactive applications using Streamlit.
- Implementing Text-to-Speech functionality.
- Handling user inputs and generated outputs.
- Managing project code using Git and GitHub.

## 👩‍💻 15. Author

**Bhumika Patel**

B.Tech – Artificial Intelligence and Machine Learning

GitHub: [@bhumikapatel5155-creator](https://github.com/bhumikapatel5155-creator)

---

⭐ If you find this project useful, consider giving the repository a star!