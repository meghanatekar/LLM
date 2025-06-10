# LLM
LLM model - Gemini Health App
![Uploading Screenshot (1384).png…]()

 Project Setup Instructions (Using Anaconda, VS Code & Streamlit)
1. Install Anaconda Navigator
Download and install Anaconda Navigator from the official site.

2. Launch Visual Studio Code
Open VS Code from Anaconda Navigator or directly from your desktop.

3. Set the Terminal to Use cmd
In VS Code, go to:

sql
Copy
Edit
Terminal → New Terminal
Make sure the default shell is set to Command Prompt (cmd).

4. Create a Virtual Environment with Python 3.10
cmd
Copy
Edit
conda create -p venv python=3.10 -y
5. Create Essential Project Files in VS Code
Inside your project folder, create the following files:

.env

requirements.txt

app.py

6. Add Google API Key to .env
Open the .env file and paste your MakerSuite Google API Key:

ini
Copy
Edit
GOOGLE_API_KEY=your_key_here
Save the file.

7. Activate the Virtual Environment
cmd
Copy
Edit
conda activate venv/
8. Install Required Packages
cmd
Copy
Edit
pip install -r requirements.txt
9. Add All Downloaded Files to Your Desktop
Move your project folder (including all .py, .txt, and .env files) to your Desktop for easy access.

10. Run Your Streamlit App
cmd
Copy
Edit
streamlit run app.py
⚠️ Facing Errors?
For any setup or runtime issues, use ChatGPT to get step-by-step debugging help. Paste the error message, and it will guide you with clear solutions.


   

