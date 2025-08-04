🎤 Voice-Based Deep Learning Chatbot

This project is a voice-enabled chatbot developed using Natural Language Processing (NLP) and Deep Learning techniques. The system interprets spoken user input, classifies it into predefined intents using a trained neural network model, and responds through both text and voice output.

🔧 Features
✅ Voice-to-text input using SpeechRecognition
✅ Intent classification using a deep learning model (Keras + TensorFlow)
✅ Text and voice-based responses via pyttsx3
✅ Streamlit-based web interface for demo interaction (optional)
✅ Easily extendable intents file for additional patterns and responses

🛠️ Technologies Used

Python 3.x

NLTK (Natural Language Toolkit)

TensorFlow / Keras

SpeechRecognition

pyttsx3 (Text-to-Speech)

Streamlit (optional UI)

NumPy, Matplotlib

📁 Project Structure
voice-chatbot/
├── assets/ — Images like diagrams and screenshots
├── intents.json — Dataset with user intents, patterns, and responses
├── train.py — Script to train the model
├── model.h5 — Saved trained model
├── words.pkl — Pickled vocabulary
├── classes.pkl — Pickled intent labels
├── chat.py — Voice-based chatbot logic
├── app.py — Streamlit web interface
├── requirements.txt — Project dependencies
└── README.md — Project documentation

🚀 Getting Started

Install dependencies:
pip install -r requirements.txt

Train the model:
python train.py

Run the voice chatbot:
python chat.py

(Optional) Run the Streamlit UI:
streamlit run app.py

📌 Future Scope

Add multilingual support

Integrate BERT or LLMs for improved accuracy

Deploy to cloud platforms or mobile devices

Add user authentication and context handling

Store and analyze chat history

🤝 Contributing
Pull requests are welcome. Feel free to fork the repo, make changes, and submit a PR. For major changes, please open an issue first to discuss what you’d like to change.

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgments
Thanks to the open-source community and available tutorials that helped shape this project.

✨ If you found this project useful, give it a ⭐ on GitHub and share it with others!
