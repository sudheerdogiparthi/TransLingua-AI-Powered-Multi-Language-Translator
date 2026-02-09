# TransLingua-AI-Powered-Multi-Language-Translator
TransLingua is an AI-driven multi-language translation application that enables users to translate text between multiple languages with high accuracy and contextual understanding. Built with a clean UI and a powerful AI backend, it’s designed for students, developers, and global users.

# 📂 Project Structure
TransLingua-AI-Powered-Multi-Language-Translator/
├── app.py                     # Main application
├── .env                       # API keys (not committed)
├── requirements.txt           # Dependencies
├── README.md                  # Project documentation

# 🧰Technologies
- Python
- Streamlit
- Google Generative AI
- python-dotenv

# ⚙️Installation
**Step 1: Clone or Download the Project**
- git clone <your-repository-link>
- cd Project

**Step 2: Set Up a Virtual Environment**
- python -m venv venv
- venv\Scripts\activate

**Step 3: Install Dependencies**
- pip install -r requirements.txt

**Step 4: Environment Setup**
- GOOGLE_API_KEY=your_gemini_api_key

**Step 5: Run the Application**
- streamlit run app.py

# 🧪How It Works
1. The user enters text in the input box.
2. The user selects the source and target languages.
3. The application sends the input as a prompt to the Gemini AI model.
4. The AI generates and displays the translated text.

# ⚠️Notes
- Do not upload the .env file to GitHub to protect your API key and sensitive data.
- API usage may incur charges depending on the Gemini API usage limits and billing plan.
- Language options are currently fixed and can be extended by modifying the main Python file.

# 🚀 Future Improvements
- Add more language options dynamically
- Speech-to-text support
- Text-to-speech output
- Translation history
- Better error handling and validation
