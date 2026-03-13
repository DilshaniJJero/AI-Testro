# AI Testro

AI Testro is a web-based forensic analysis platform designed to detect AI-generated content across **text, images, audio, and video**. The system analyzes digital media using multiple forensic techniques to determine whether the content is human-created or AI-generated.

This project was developed as part of the **National Level Cyber Security Hackathon at SRM Institute of Science and Technology, Chennai Ramapuram**.

---

## Project Overview

With the rapid growth of artificial intelligence tools capable of generating realistic text, images, audio, and videos, verifying the authenticity of digital content has become increasingly challenging.

AI Testro provides a **unified forensic analysis system** that helps identify artificial content by examining hidden patterns, metadata, and AI generation artifacts.

The platform assigns a **probability score** and generates **forensic reports** that help investigators and analysts understand whether the content is likely AI-generated.

---

## Key Features

- Text AI Detection  
- Image Forensic Analysis  
- Audio Deepfake Detection  
- Video Deepfake Detection  
- Metadata Inspection  
- Statistical Pattern Analysis  
- Watermark / Artificial Trace Detection  
- Unified Analysis Platform  
- Forensic Report Generation  
- Dashboard with Analysis Statistics

---

## Metadata Analysis

The system extracts and analyzes important metadata such as:

- File name
- File type
- File size
- Creation date
- Modified date
- Resolution or pixel size
- Duration (audio/video)
- Device or software used
- Location (if available)

The platform also detects **metadata inconsistencies** that may indicate manipulated or synthetic content.

---

## Forensic Report Generation

After analysis, AI Testro generates a **detailed forensic report** including:

- Report ID
- Timestamp
- File hash value (SHA-256)
- AI probability score
- Metadata analysis
- Artifact detection results
- Short forensic explanation
- Detailed analysis summary

Reports can be downloaded in:

- PDF
- HTML
- DOC

These reports are designed to support **digital forensic investigations and cybersecurity analysis**.

---

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python (Flask)

### Libraries
- Pillow
- MoviePy
- Pydub
- ReportLab
- Flask-CORS

---

## Project Structure
AI-Testro
│
├── frontend
│ ├── index.html
│ ├── dashboard.html
│ ├── styles.css
│ └── script.js
│
├── backend
│ ├── app.py
│ ├── analysis
│ │ ├── text_detector.py
│ │ ├── image_forensics.py
│ │ ├── audio_detector.py
│ │ └── video_detector.py
│
├── reports
│
└── README.md


---

## Use Cases

AI Testro can be used by:

- Cybersecurity investigators  
- Digital forensic analysts  
- Journalists and fact-checking teams  
- Social media monitoring platforms  
- Law enforcement agencies  

---

## Future Improvements

- Advanced machine learning detection models
- Blockchain-based evidence verification
- Real-time social media monitoring
- Automated deepfake detection models
- Improved AI watermark detection

---

## Project Goal

The goal of AI Testro is to create a **scalable forensic platform capable of detecting AI-generated content and supporting digital evidence verification in cybersecurity investigations.**

---

## Hackathon

Developed for the **National Level Cyber Security Hackathon**  
**SRM Institute of Science and Technology – Ramapuram Campus**

---

## License

This project is developed for research and educational purposes.
