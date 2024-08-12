# Expense Tracker

## Overview

The **Expense Tracker** is a web-based application designed to help users manage their personal expenses. It allows users to register, log in, and add expenses under various categories. The application also provides visualizations such as pie charts, bar charts, and line charts to help users better understand their spending habits.

## Features

- **User Registration and Login:** Secure user authentication using Flask sessions.
- **Expense Management:** Users can add, update, and delete expenses under different categories.
- **Data Visualization:** Interactive charts and graphs to visualize expenses over time and by category.
- **MongoDB Integration:** All user data is stored in a MongoDB database.

## Technologies Used

- **Backend:** Flask, Flask-PyMongo
- **Frontend:** HTML, CSS, Jinja2 Templates
- **Database:** MongoDB
- **Data Visualization:** Plotly
- **Deployment:** Gunicorn (for production)
- **Others:** Python-dotenv for managing environment variables

## Setup Instructions

Follow these steps to set up the Expense Tracker project on your local machine.

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/Expense-Tracker.git
cd Expense-Tracker
```

### 2. Create a Virtual Environment

It's recommended to create a virtual environment to manage your dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
```

### 3. Install Dependencies

Install all the required Python packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a `.env` file in the root directory of the project and add the following environment variables:

```bash
MONGO_USERNAME=your_mongo_username
MONGO_PASSWORD=your_mongo_password
MONGO_CLUSTER=your_mongo_cluster
MONGO_DBNAME=your_database_name
SECRET_KEY=your_secret_key
```

Replace the placeholder values with your actual MongoDB credentials and a secret key.

### 5. Run the Application

Start the Flask development server:

```bash
python app.py
```

The application will be running on `http://127.0.0.1:5000/`. Open this URL in your web browser to access the Expense Tracker.

### 6. Accessing the Application
1. **Register** a new user account.
2. **Log in** with your registered credentials.
3. **Start Managing** your expenses!

