# Nutritionist_GenAi_doctor_using_gemini-pro-vision
Welcome to the Calories Advisor App! This application uses the Gemini API to analyze images of food and provide nutritional information, including total calories and a breakdown of nutrients.

## Setup Instructions

Follow these steps to set up and run the app:

## Create a virtual enviorment
1. Create a virtual enviorment `sh conda create -p venv python==3.10`
2. Start the virtual enviorment `sh conda activate venv/`

## Install requirements.txt 
3. Install requirements.txt `sh pip install -r requirements.txt`

## Add your api key
4. Create a .env file and store the gemini api key as `GOOGLE_API_KEY="your api key"`

## Run app using streamlit
5. Run the app usigng `sh streamlit run app.py`