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
