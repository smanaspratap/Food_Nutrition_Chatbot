Food Nutrition Bot
An interactive chatbot that provides detailed nutritional information from food names or images. Built using Streamlit, XGBoost Regressor, and integrated with the Gemini API for enhanced conversational flow.

Key Features
Provides detailed nutritional information based on food names or images
Interactive chatbot interface for easy user interaction
Uses XGBoost Regressor for accurate nutritional prediction
Integrated with Gemini API for improved conversational flow
Ideal for gym enthusiasts and health-conscious users

Project Structure
FoodNutritionBot/
│
├── app.py                # Main Streamlit application
├── model.py              # XGBoost model implementation
├── requirements.txt      # Required dependencies
├── README.md             # Project documentation
└── .env                  # API keys and sensitive data (not shared publicly)

Installation and Setup
Follow these steps to run the project locally:

1. Clone the repository
git clone https://github.com/your-username/FoodNutritionBot.git
cd FoodNutritionBot

2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate    # On Mac/Linux
.\venv\Scripts\activate     # On Windows

3. Install dependencies
pip install -r requirements.txt

4. Add your Gemini API key
Create a .env file in the root folder and add:

GEMINI_API_KEY=your_api_key_here

5. Run the application
streamlit run app.py

6. Access the chatbot
Open your browser and visit: http://localhost:8501

How It Works
The chatbot accepts text or image inputs from users.
For text-based queries, it retrieves detailed nutritional information.
For image-based queries, it leverages the Gemini API for food recognition and generates relevant nutritional details.
The XGBoost Regressor is used to predict missing nutritional data accurately.

Future Enhancements
🔹 Expand the database to include more food varieties
🔹 Improve the image recognition model for better accuracy
🔹 Add calorie tracking and meal planning features

Contributing
Contributions are welcome! If you’d like to improve this project, feel free to fork the repository and submit a pull request.
