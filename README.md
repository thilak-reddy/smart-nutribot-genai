# Health Management App - Smart Nutribot

## Overview

The **Smart Nutribot** is a health management application designed to help users analyze the nutritional content of their meals. By leveraging Google's Gemini Vision API, the app provides calorie breakdowns of food items based on an uploaded image and offers tailored health recommendations based on user-provided health conditions.

## Features

- **Calorie Analysis**: Upload an image of food items to get a detailed calorie breakdown.
- **Health Recommendations**: Enter health conditions to receive tailored nutritional advice and precautions.
- **Interactive UI**: User-friendly interface built with Streamlit for seamless interactions.

## Prerequisites

Before using this app, ensure you have the following installed and configured:

- Python 3.8 or above
- Required Python libraries: `dotenv`, `streamlit`, `google.generativeai`, `Pillow`

## Setup

1. Clone the repository or download the code:
   ```bash
   git clone https://github.com/<your-username>/Health-Management-App.git
   cd Health-Management-App
   ```
2. Install the required dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a .env file in the root directory and add your Google Gemini Vision API key:
   ```bash
   GOOGLE_API_KEY=your_google_api_key_here
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```
