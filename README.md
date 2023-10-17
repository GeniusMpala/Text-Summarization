# Text-Summarization
Text Summarization with Openai and Lanchain

Setup and Running Locally
Clone the repository


git clone [Your Repository Link]
cd [Your Repository Directory]
Set up a virtual environment (Recommended)



python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages


pip install -r requirements.txt
Run the Streamlit app

streamlit run [Your App Script Name].py
This will open a new browser window with the application running.

Deploying on Cloud
Using Streamlit Sharing (Recommended for Streamlit apps)
Push your code to a public GitHub repository.
Sign up for Streamlit Sharing.
Once approved, you'll be able to deploy directly from your GitHub repo.
Using Heroku
Create a Procfile in your repository with the following content:




mkdir -p ~/.streamlit/

echo "\
[server]\n\
headless = true\n\
port = $PORT\n\
enableCORS = false\n\
\n\
" > ~/.streamlit/config.toml
Push your code to a GitHub repository.

Sign up for a Heroku account if you don't have one.

Install the Heroku CLI.

Log in using heroku login.

Create a new Heroku app: heroku create your-app-name.

Push your code to Heroku: git push heroku master.

Your app should now be live at https://your-app-name.herokuapp.com.

