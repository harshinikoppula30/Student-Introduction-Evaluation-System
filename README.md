# Student Introduction Evaluation System

## Overview
A Python-based application that evaluates student self-introductions using NLP techniques and a predefined scoring rubric. It analyzes communication-related aspects and generates an overall score out of 100.

## Features
- Salutation and keyword detection
- Introduction flow evaluation
- Speech rate calculation (WPM)
- Grammar checking
- Vocabulary richness analysis
- Filler word detection
- Sentiment analysis
- Overall performance scoring

## Technologies Used
Python | NLTK | TextBlob | LanguageTool | Gradio

## How It Works
Users provide an introduction transcript and speech duration. The application evaluates the input against eight criteria and displays a detailed score breakdown in JSON format through a Gradio interface.

## How to Run
1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Run the notebook cells.
4. Enter the transcript and speech duration in the Gradio interface.
5. View the evaluation results.

## Project Type
Rule-Based NLP Application
