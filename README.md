# Analyzing Customer Support Calls

## Project Overview
This project is designed to analyze customer support call recordings. The main goals are:

1. **Convert audio calls to text** for analysis.
2. **Analyze sentiment** of the transcribed calls (positive, negative, neutral).
3. **Extract named entities** (like names, companies, locations) from the text.
4. **Check audio quality** for future speech recognition modeling.
5. **Find similarity** of calls to a specific query (e.g., "wrong package delivery").

The project helps companies understand customer feedback and improve service quality.

## Features

- **Speech to Text**: Converts `.wav` audio files into readable text using Google Speech Recognition.
- **Audio Statistics**: Checks number of channels and frame rate to verify audio quality.
- **Sentiment Analysis**: Uses NLTK’s VADER module to detect positive, negative, or neutral sentiment.
- **Named Entity Recognition (NER)**: Uses spaCy to identify important entities in the text.
- **Similarity Analysis**: Finds the most relevant call text compared to a given query.

## Requirements

- Python 3.x
- Libraries:
  - `SpeechRecognition`
  - `pydub`
  - `spacy`
  - `nltk`

## Usage

1. Place your audio file in the project directory.  
 Example: `Testing audio.wav`

2. Run the main Python script:

```bash
python analyze_customer_calls.py
