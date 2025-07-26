# Video Summarizer using Gemini API

A Streamlit-based web application that extracts meaningful content from `.mp4` videos by identifying keyframes and generating a summary using Google’s Gemini 1.5 Pro model.

---

## 🧠 Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python, OpenCV, FFmpeg  
- **AI/LLM:** Google Gemini 1.5 Pro (`google.generativeai` SDK)  
- **Auth:** Custom login/signup with local JSON-based user storage  
- **Frame Comparison:** SSIM (Structural Similarity Index) from `skimage`  
- **Audio Extraction:** FFmpeg (optional)  
- **Dependencies:** See `requirements_updated.txt`

---

## 🚀 Features

- Upload and preview `.mp4` video files  
- Extract 1 frame per second, filter redundant frames using SSIM  
- Upload selected frames to Gemini for content summarization  
- Optional audio extraction setup (commented code available)  
- User authentication with hashed password storage  
- Cleanup of all uploaded/generated files after summarization

---

## 🔧 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Video-Summariser-using-gemini.git
cd Video-Summariser-using-gemini
