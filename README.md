# 🎥 Video AI Summarizer Agent

This **Streamlit-based AI application** enables users to analyze and summarize video content using **Gemini 2.0 Flash Exp**. Users can upload videos, input queries, and receive AI-generated insights with additional web research.

## 🚀 Features
- **Multimodal AI Analysis**: Upload a video and get AI-powered insights based on your queries.
- **Gemini 2.0 Flash Exp**: Utilizes advanced AI for in-depth video content analysis.
- **Web Research Integration**: Enhances responses with supplementary information from DuckDuckGo.
- **User-Friendly Interface**: Built using Streamlit for seamless interaction.

## 🛠️ Tech Stack
- **Streamlit**: Interactive UI for video analysis.
- **Phi AI Agent**: AI-powered reasoning and response generation.
- **Gemini 2.0 Flash Exp**: Google's generative AI model.
- **DuckDuckGo API**: Fetches additional web-based information.

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/video-ai-summarizer.git
   cd video-ai-summarizer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your API key:
   - Create a `.env` file in the root directory.
   - Add your Google API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📌 How to Use

1. **Upload a video file** (`mp4`, `mov`, `avi`).
2. **Enter a query** about the video content.
3. Click **"Analyze Video"** to let the AI process and summarize the insights.
4. View the **detailed AI-generated response**.

## ⚡ Future Enhancements
- Support for **additional video formats** and real-time processing.
- **Enhanced transcription and summarization** capabilities.
- Integration with **speech-to-text models** for audio
