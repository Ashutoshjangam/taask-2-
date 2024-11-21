Summer Heat Wave Mobile Alert System
Overview
The Summer Heat Wave Mobile Alert System is a predictive alert system designed to inform users of upcoming heat waves. This system uses data analysis and machine learning models to predict heat waves and sends alerts via SMS to registered users using the Twilio API. The project is aimed at helping people prepare and take precautions during extreme weather conditions, particularly in regions prone to high temperatures.

Features
Predictive Modeling: Utilizes machine learning algorithms to forecast heat waves based on historical weather data.
Data Collection: Automatically collects and updates weather data from reliable sources.
Mobile Alerts: Sends SMS alerts to users when a heat wave is predicted in their area.
User Registration: Allows users to register their phone numbers to receive alerts.
Web Interface: Provides a user-friendly interface for managing alerts and viewing weather data.
Technologies Used
Python: For data analysis, machine learning, and backend development.
Pandas: For data manipulation and analysis.
Scikit-learn: For developing predictive models.
Flask: For creating the web interface and API endpoints.
Twilio API: For sending SMS alerts.
SQLite: For storing user data and alerts.
Heroku: For deploying the web application.
Installation
Prerequisites
Python 3.7+
Twilio account (for SMS services)
Heroku account (for deployment)
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/Ashutoshjangam/task-2
cd heat-wave-alert-system
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Set up environment variables:

Create a .env file in the root directory and add your Twilio credentials and other configurations:

plaintext
Copy code
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
Run the application locally:

bash
Copy code
python app.py
Deploy to Heroku:

Initialize a Git repository (if not already done):
bash
Copy code
git init
Add a remote for Heroku:
bash
Copy code
heroku git:remote -a your-heroku-app-name
Deploy the application:
bash
Copy code
git push heroku main
Usage
Register a user:

Access the web interface or use the provided API endpoint to register a user's phone number.
Users will start receiving SMS alerts when a heat wave is predicted.
View Predictions:

Use the web interface to view the current weather data and upcoming heat wave predictions.
Project Structure
plaintext

![WhatsApp Image 2024-11-22 at 00 03 36_a8f20d55](https://github.com/user-attachments/assets/e07d7c01-e88f-40cb-a8d2-8f3ee058f699)


Contributing
Contributions are welcome! Please create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or feedback, please reach out to [ashutoshjangam2k@gmail.com] or open an issue in the GitHub repository.
