# 🚀 BankGenie

## 📌 Table of Contents
- [Introduction](#introduction)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
AI-Driven Hyperpersonalization & Recommendation System
Introduction
In today’s digital world, users expect highly personalized experiences tailored to their unique preferences and behaviors. Our AI-Driven Hyperpersonalization & Recommendation System leverages advanced machine learning techniques to analyze user activity, demographics, and real-time interactions, delivering highly relevant banking and financial service recommendations.

This project is designed to enhance customer engagement, improve financial decision-making, and drive business growth by offering:
✅ Personalized banking recommendations based on transaction history, social media sentiment, and user profile.
✅ AI-powered chatbot for real-time financial assistance and service recommendations.

##  Demo Video Link
https://drive.google.com/file/d/1CMc74-t8X4kZleQoyof7hMGQ2eZ_RKAV/view?usp=sharing

## 💡 Inspiration
With the rise of AI-driven experiences in sectors like e-commerce and entertainment, we saw a gap in hyperpersonalized financial services that truly cater to individual users. Traditional banking often provides one-size-fits-all recommendations, leading to irrelevant offers and missed opportunities for both customers and businesses. We wanted to bridge this gap by leveraging AI, machine learning, and real-time behavioral analysis to create a system that not only understands user needs but also evolves with them. Our goal was to build a solution that transforms banking into an intelligent, intuitive, and highly personalized experience—where users get the right financial insights at the right time, empowering them to make smarter financial decisions effortlessly.

## What Does Our AI Do?
Our AI-powered system redefines banking experiences by delivering hyperpersonalized financial recommendations tailored to each user’s unique needs. By analyzing transaction patterns, user profiles, and real-time activity, it ensures that customers receive relevant and timely financial insights rather than generic suggestions.

Through context-aware service recommendations, the AI understands factors like occupation, age, financial history, and spending behavior to suggest the most suitable banking products—whether it’s an investment plan for a young professional or a retirement savings option for an older customer.

Beyond traditional data, our AI also incorporates behavioral insights from social media activity, analyzing sentiment and interests to refine financial suggestions. This enables proactive recommendations, such as travel insurance for frequent travelers or specialized credit card offers based on spending trends.

Additionally, our Conversational AI chatbot acts as an intelligent assistant, providing real-time financial guidance, answering queries, and helping users navigate banking services effortlessly. With natural language interactions, it ensures a seamless, engaging, and interactive user experience.

## 🛠️ How We Built It
Step 1: Understanding Requirements & Data Collection -
Gathered customer transaction data, comments, and financial needs from an Excel file.

Step 2: Data Preprocessing & Feature Engineering - 
Cleaned text data (removing stop words, punctuation, and special characters).
Mapped transaction types to a rating system for collaborative filtering.
Tokenized and vectorized text features using TF-IDF for similarity analysis.

Step 3: Implementing Content-Based Filtering (TF-IDF + Cosine Similarity) -
Combined customer interests, financial needs, and occupation into a single text representation.
Applied TF-IDF vectorization to convert text into numerical features.
Computed cosine similarity scores between customers for recommendations.

Step 4: Implementing Collaborative Filtering (SVD - Singular Value Decomposition) -
Created a user-item interaction matrix where customers rate services based on transactions.
Used SVD to predict missing ratings and recommend services based on similar users.

Step 5: Sentiment Analysis Using VADER -
Used VADER SentimentIntensityAnalyzer to analyze customer comments.
Classified customer sentiment as positive, negative, or neutral to refine recommendations.

Step 6: Generative AI for Offer Customization (Mistral AI Integration) -
Sent a request to Mistral AI’s local API to return offers based on user interests.
Ensured responses were formatted as valid JSON for easy integration.

Step 7: Chatbot Development & Integration -
Designed an API-based chatbot for real-time interaction.
Implemented intent classification using TF-IDF to match user queries with services.

Step 8: API Development Using FastAPI -
Created endpoints

## 🚧 Challenges We Faced
Data Quality & Availability
Balancing Personalization & Privacy


## 🏃 How to Run
1. Clone the repository  
   ```sh
   https://github.com/ewfx/aidhp-marsbytes.git
   ```
2. Install dependencies  
   ```sh
   npm install  # or pip install -r requirements.txt (for Python)
   ```
3. Run the project  
   ```sh
   python .\python_server.py
   node server.js
   ng serve
   ```
   run the python server and node server in backend directory.

## 🏗️ Tech Stack
- 🔹 Frontend: Angular
- 🔹 Backend: Node.js/ Python 
- 🔹 Database: faker

## 👥 Team
- **Surya** 
- **Radhika**
- **Mayuri Tambe**
- **Ananya Jain**
