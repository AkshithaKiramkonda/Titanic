🚢 Titanic Survival Predictor - Will You Survive?
![titanic](back.jpg)

🎩 Step aboard the Titanic—virtually! This interactive Flask web app predicts whether you would have survived the legendary voyage. Using a powerful Random Forest model, it analyzes key passenger details and determines your fate. Will you make it to safety or sink with the ship? Let’s find out!

Features at a Glance

✅ Interactive & User-Friendly – Enter details, click predict, and get instant results!

✅ Machine Learning Magic – Uses a trained Random Forest classifier to make predictions.

✅ Encodes Categorical Features – Transforms inputs like gender and embarkation point with pre-trained encoders.

✅ Emoji-Powered Results – Get a cheerful 😊 or heartbreaking 😢 prediction!

✅ Fast & Lightweight – Built with Flask for seamless performance.


🏗 Project Blueprint

📂 Titanic-Survival-App/




📜 app.py                 # Flask application - the brain behind the magic  

📂 templates/             # Houses HTML templates for rendering  

📂 static/                # (Optional) CSS/JS files for styling  

📜 random_forest_titanic.pkl   # Pre-trained survival predictor model  

📜 label_encoder_sex.pkl       # Encodes gender data  

📜 label_encoder_embarked.pkl  # Encodes embarkation points  

📜 requirements.txt        # List of necessary dependencies  

📜 README.md              # This document!  


1️⃣ Clone This Repository

git clone https://github.com/your-username/titanic-survival-flask.git

cd titanic-survival-flask

2️⃣ Install the Essentials

pip install -r requirements.txt

3️⃣ Fire Up the Ship!

python app.py

 Now, open your browser and set sail to http://127.0.0.1:5000/

🔮 How It Works

1️⃣ Enter Passenger Details – Class, Age, Gender, Fare, etc.

2️⃣ Click “Predict” – The model evaluates your survival chances.

3️⃣ Get Your Fate – A happy 😊 or tragic 😢 outcome is displayed!

🔍 Behind the Scenes:

Your details are transformed using pre-trained encoders.

The Random Forest model predicts survival based on historical Titanic data.

The result is returned with an engaging emoji-based verdict.
