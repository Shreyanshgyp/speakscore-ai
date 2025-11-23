# speakscore-ai
📌 Overview

This project provides an AI-assisted scoring system for evaluating students’ spoken self-introductions. It uses a mix of rule-based logic and lightweight NLP techniques to analyze a transcript and compute a final score based on a predefined rubric.

🚀 Features

Evaluates structure: salutation, basic details, additional info, and closing

Scores must-have and good-to-have keywords

Measures speech rate (WPM)

Detects filler words

Calculates vocabulary richness (TTR)

Performs sentiment analysis using VADER

Simple and interactive Gradio UI

Returns an overall score + detailed criterion-wise breakdown

🧠 How It Works

The scoring engine processes the transcript through several evaluation blocks:

Content & Structure – Checks presence of key details and sequence flow

Speech Rate – Words per minute based on duration

Language Quality – Basic grammar checks + vocabulary diversity

Clarity – Filler-word frequency

Engagement – Sentiment and positivity

Each block contributes to the final rubric-based score (0–100).

💻 Usage

Paste the transcript into the text box

Enter the duration of the audio in seconds

Click Submit

Receive complete scoring + feedback

📂 Tech Stack

Python

Gradio (UI)

VADER Sentiment Analyzer

Regex & Rule-based Logic for scoring

🎯 Purpose

This tool supports communication training programs by delivering quick, objective, and transparent evaluation of spoken introductions. It helps students understand their strengths and areas to improve.
