# 🚀 Astro Bot: Space Trivia Chatbot  

Astro Bot is a dynamic chatbot designed to provide real-time space-related information and updates. From rocket launches to meteor showers and groundbreaking scientific discoveries, Astro Bot makes space science accessible to everyone through an engaging conversational interface.  

---

## 🌌 Features  

- **Real-Time Updates**: Stay informed about space events like rocket launches, meteor showers, and major scientific advancements.  
- **Conversational Interaction**: Engage with the bot to ask questions and receive detailed, easy-to-understand answers.  
- **Simplified Space Science**: Complex scientific data is made digestible for learners of all levels.  
- **Educational Resources**: Promotes interest in space exploration by sharing additional learning materials.  

---

## 🛠️ Tech Stack  

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python, Flask  
- **APIs**: Integrated with [NASA Open Data](https://data.nasa.gov/) and [Gemini API](https://ai.google.dev/gemini-api/docs) for real-time updates and NLP capabilities.  

---

## ⚙️ Installation & Setup  

Follow these steps to set up and run Astro Bot on your system:  

### 1. Clone the Repository  

```bash  
git clone   https://github.com/Sanchet237/AstroBot-Space_Trivia.git
cd AstroBot  
```  

### 2. Install Dependencies  

Create a virtual environment and install required Python packages:  

```bash  
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  
pip install -r requirements.txt  
```  

### 3. Run the Server  

Start the Flask server using the following command:  

```bash  
python server.py  
```  

Access the chatbot at:  
`http://127.0.0.1:5000/`  

---

## 📖 How It Works  

1. **Interactive Chat**: Ask Astro Bot any space-related question, and it will respond in real-time.  
2. **Real-Time Data Integration**: The bot retrieves live updates from APIs like NASA's database and simplifies them for the user.  
3. **Educational Outreach**: Users are encouraged to explore and learn more about space through the bot's responses.  

---

## 🌟 Benefits  

- **Accessibility**: Makes space science easily available to a wider audience.  
- **Engagement**: Keeps users informed and engaged with the latest in space exploration.  
- **Learning Opportunities**: Encourages deeper exploration of space-related topics.  

---

## 🗂️ Project Structure  

```bash  
AstroBot/  
├── templates/              # HTML templates for the user interface  
├── static/                 # Static files (CSS, JavaScript)  
├── server.py               # Flask backend server  
├── llm.py                  # Script for NLP integration  
├── requirements.txt        # Python dependencies  
├── .gitignore              # Git ignore file  
└── README.md               # Project documentation  
```  

---

## 🌠 Goals and Aspirations  

Astro Bot aims to:  
- Democratize space knowledge by making it accessible to everyone.  
- Foster curiosity and learning about space science.  
- Build a community of space enthusiasts and learners.  

---

## 🤖 Artificial Intelligence  

Astro Bot utilizes the **Gemini API** for Natural Language Processing (NLP) to deliver intuitive and human-like interactions. Learn more:  
[Gemini API Documentation](https://ai.google.dev/gemini-api/docs)  

---

## 🛰️ Space Data Sources  

- NASA Open Data: [data.nasa.gov](https://data.nasa.gov/)  

---

## 📚 References  

- [Pexels](https://pexels.com)  
- [Unsplash](https://unsplash.com)  
- [NLTK Documentation](https://www.nltk.org/)  

---

Astro Bot invites you to explore the universe in a new, interactive way. 🌌 Let's make space science exciting for everyone!