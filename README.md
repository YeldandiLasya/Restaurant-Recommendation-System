# 🍽️ Restaurant Recommendation System

> Personalized dining recommendations using Machine Learning and Natural Language Processing.

## 📑 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Limitations and Future Work](#limitations-and-future-work)
- [License](#license)
- [Contact](#contact)

## 📖 About the Project
In today’s food landscape, choosing the perfect restaurant can be overwhelming.  
This project simplifies that process by providing personalized restaurant recommendations based on **restaurant type**, **cuisine**, and **location**.  
Built with machine learning techniques (TF-IDF and cosine similarity) and deployed using Streamlit.

## ✨ Features
- Personalized recommendations based on user preferences.
- Easy-to-use web interface built with Streamlit.
- Fast, real-time suggestion engine using TF-IDF and cosine similarity.
- Top 10 most relevant restaurants displayed based on user inputs.

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **Scikit-Learn**
- **Streamlit**
- **Zomato Dataset (from Kaggle)**

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/vishnuvardhanreddythornala/Restaurant-Recommendation-System.git

# Navigate to the project directory
cd Restaurant-Recommendation-System

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

## 🚀 Usage
1. Enter your **preferred restaurant type** (e.g., Fine Dining, Cafe).
2. Enter your **preferred cuisine** (e.g., Italian, Indian).
3. Enter your **preferred location** (e.g., Downtown, City Center).
4. Click **Get Recommendations**.
5. View the top 10 matching restaurants!

## 📁 Project Structure
```
Restaurant-Recommendation-System/
├── zomato.csv
├── Recommendapp.py
├── requirements.txt
├── README.md
```

## ⚡ Limitations and Future Work
- Dataset quality affects recommendation accuracy.
- Does not account for real-time restaurant availability.
- Future Work:
  - Integrate real-time APIs like Zomato.
  - Enhance UI/UX.
  - Include dietary filters and ratings.

## 📜 License
This project is licensed under the **MIT License**.
