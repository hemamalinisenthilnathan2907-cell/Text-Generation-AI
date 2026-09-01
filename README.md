# Text-Generation
AIA simple web-based AI Text Generator that generates text from a user-provided prompt using a pretrained Transformer language model.

📌 About

This project uses Hugging Face Transformers and Streamlit to create an interactive AI text generation application. 
Users can enter a prompt, adjust the generation settings, and generate AI-powered text.

✨ Features

📝 Simple prompt input
🤖 AI-powered text generation
🚀 Generate Text button
⏳ Loading message while generating
📄 Generated text display
🎛️ Adjustable maximum length
🌡️ Adjustable temperature
⚡ Model caching for better performance
💻 Simple and interactive Streamlit interface
🛠️ Technologies
Python
Streamlit
Hugging Face Transformers
PyTorch
Qwen Language Model
VS Code
🔄 How It Works
User enters a prompt
        ↓
Streamlit receives the input
        ↓
Qwen Model processes the prompt
        ↓
AI generates text
        ↓
Generated text is displayed
📦 Installation
Step 1: Clone the Repository
git clone https://github.com/your-username/AI-Text-Generator.git
Step 2: Open the Project Folder
cd AI-Text-Generator
Step 3: Install Requirements
pip install -r requirements.txt
▶️ Run the Application

Run the following command in the terminal:

streamlit run app.py

The application will open in your default web browser.

💡 Example
Input Prompt
Artificial Intelligence is
Generated Output

The AI model generates a continuation based on the given prompt.

🎛️ Generation Settings
Maximum Length

Controls the maximum number of tokens/length allowed for the generated output.

Temperature

Controls the randomness of the generated text.

Lower temperature → More predictable output
Higher temperature → More creative output

📚 Key Learning

Through this project, I learned:

Transformer-based AI models
Text generation using pretrained models
Hugging Face Transformers
Streamlit web applications
PyTorch
AI model integration
Model caching
Text generation parameters

📁 Project Structure

AI-Text-Generator/
│
├── Screenshots/
│
├── app.py
├── README.md
├── requirements.txt
└── .gitignore

🚀 Future Improvements

Add multiple language models
Add text download functionality
Add prompt history
Add chat-style interface
Improve the user interface
Add more generation controls

👩‍💻 Author

Hemamalini S
B.Sc. Computer Science with Artificial Intelligence
SDNB Vaishnav College for Women, Chennai
