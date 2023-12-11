# Phishing Websites Detection with Flask UI
> A Flask-based application for detecting phishing websites using machine learning.

## Features 🌟
- 🌐 Real-time phishing website detection
- 🔍 Machine Learning Integration
- 🖥️ User-friendly Flask UI

## Technology Stack 💻
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) for core application
- ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) for web framework
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) for database

## Requirements 📋

- ![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white) Mongo DB Atlas database.
- ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) A Computer or laptop with Windows OS along with Python 3.8 or above.
- ![Chrome Browser](https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white) Chrome Browser (optional).
- 
## Installation Guide 🛠️

1. **Clone the Repository**
   ```sh
   git clone https://github.com/avinashtechlvr/Phishing_Websites_Detection_with_Flask_Ui.git
   ```

2. **Navigate to the Directory**
   ```sh
   cd Phishing_Websites_Detection_with_Flask_Ui
   ```

3. **Install Dependencies**
   - Ensure Python is installed.
   - Install required Python packages:
     ```sh
     pip install -r requirements.txt
     ```

4. **Database Setup**
   - Create a MongoDB Atlas Database to set up your own MongoDB Atlas database.
   - For guidance, refer to the MongoDB Atlas documentation: [Getting Started with MongoDB Atlas](https://docs.atlas.mongodb.com/getting-started/).
   - Update the MongoDB connection URI in the application configuration.

5. **Run the Application**
   ```sh
   python app.py
   ```
   - The application should now be running on `localhost`.

6. **Access the Web Interface**
   - Open a web browser and go to `http://localhost:5000`.


Here's a formatted "Usage" section for your README, complete with icons:

## Usage 📚

1. **Database Configuration**
   -After creating your database, go to `database.py` and update the client URL with your Mongo DB Atlas URL.

2. **Running the Application**
   - Execute `app.py`. A local host link will appear in the terminal/console.

3. **Testing the Website**
   -  Open the local host link in a browser, enter a URL (e.g., `https://www.google.com`) and click 'Check Now'.
   - If the URL is safe, you'll be redirected to the website. If it's a phishing URL, you'll receive a notification.

