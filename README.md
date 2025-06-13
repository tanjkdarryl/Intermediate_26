# BuildingBloCS June Conference 2025 Hackathon

## TOMMO (A gentle, accessible mental health check-in platform for everyday self-awareness)

## Overview
<<<<<<< Updated upstream
> TOMMO is a Streamlit-powered mental health web application designed to help users reflect on their emotional well-being. Unlike traditional clinical tools, TOMMO offers warmth, anonymity, and interactivity through three core self-assessment features:
> PHQ-9 Depression Screener
> Facial Emotion Recognition
> Audio Input Recognition
=======
> TOMMO is a Streamlit-powered mental health web application designed to help users reflect on their emotional well-being. Unlike traditional clinical tools, TOMMO offers warmth, anonymity, and interactivity through three core self-assessment features which are
> PHQ-9 Depression Screener, 
> Facial Emotion Recognition and
> Suicide Risk Text Analysis (NLP-based)
>>>>>>> Stashed changes
> The app does not diagnose or store data — it simply listens, reflects, and encourages.

## Features
### Feature 1: PHQ-9 Self Test
1. Based on the globally validated PHQ-9 questionnaire.
2. Presented in a conversational, checkbox-driven format.
3. Final score includes a breakdown of severity and thoughtful suggestions.

### Feature 2: Facial Emotion Detection
1. Uses webcam access and OpenCV with deep learning to analyze facial expressions.
2. Detects emotional states like sadness, anger, and neutrality.
3. Processes locally; no data is stored or uploaded.

<<<<<<< Updated upstream
# Feature 3 - Audio Input Recognition
1. Accepts audio files from the user.
2. An Pytorch machine learning model evaluates for suicide risk indicators in the audio.
3. Results are efficiently compared and classified through reviewing Kaggle Speech Emotion Recogntion datasets for a most honest output.
=======
### Feature 3: Suicide Text Detection
1. Accepts written input from the user.
2. An NLP model evaluates for suicide risk indicators in the text.
3. Results are delivered with care and if needed, links to external support are provided

## Datasets Used
1. Kaggle (Suicide and Depression Detection) - Suicide_Detection.csv

## Instructions to Run
1. Clone the Github repository
2. Run Facial_Recog_v4.ipynb file
- Environment Setup & Kaggle API Key Configuration
- Device Configuration
- Streamlined Model Architecture (Faster Training)
- Simplified Data Augmentation (Faster)
- Optimized Training Function
- Model Save Path
- Main Execution
>>>>>>> Stashed changes
