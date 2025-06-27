# 🌍 Jatayuv AI - Personalized Travel Recommender
Jatayuv AI is a smart travel recommendation system that helps users discover ideal destinations, plan itineraries, and estimate budgets based on their preferences, interests, and style — powered by machine learning and Streamlit.
Internship Assignment Report

## 📌 Objective
Build a sentiment analysis tool that listens to travelers' feedback on social media and analyzes emotional tones related to their journey, helping **Jatayuv AI** improve user experience through real-time insights and alerts.

---

## 📁 Dataset Overview

The dataset used in this project (`travel_recommendation_dataset.csv`) contains user-generated feedback and preferences related to travel destinations. It is designed to support sentiment analysis, recommendation systems, and behavior analysis in the travel domain.

### 🧾 Key Features

| Column Name          | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `user_id`            | Unique identifier for each user                                             |
| `user_name`          | Username or handle of the reviewer                                          |
| `location`           | Geographical location of the user                                           |
| `destination`        | Travel destination mentioned in the review                                  |
| `review_text`        | Raw textual feedback given by the user about their travel experience        |
| `rating`             | Numerical rating provided by the user (typically on a 1–5 scale)            |
| `sentiment`          | Sentiment label (Positive, Neutral, Negative) assigned to the review        |
| `travel_type`        | Purpose of travel (e.g., family, solo , frinds  etc.)                       |
| `review_date`        | Date on which the review was posted                                         |

### 🧠 Usage

This dataset supports:
- **Sentiment analysis**: Classifying emotional tone using TextBlob, VADER, or BERT.
- **Visualization**: Generating charts to show sentiment trends, ratings distribution, etc.
- **Recommendation**: Understanding user preferences based on destination and travel type.
- **Alerts**: Triggering notifications based on spikes in negative reviews.

---

## 🌍 Context
Social media is constantly buzzing with traveler experiences—from joyful check-ins to frustrating delays. Airlines and travel platforms increasingly rely on AI tools to monitor and respond to these sentiments in real time. Tools like **Mindtree's PaxPulse**, **Sprinklr**, and **Hootsuite** demonstrate the power of social listening in the travel industry.

This project is a prototype that mimics such systems using natural language processing (NLP), sentiment analysis models (TextBlob, VADER, BERT), and visual alert mechanisms.

---

## 📊 Assignment Breakdown

### 🔍 Phase 1: Research
- Studied tools like PaxPulse, Sprinklr, and Hootsuite.
- Compared their features, sentiment engines, and limitations.

### 📥 Phase 2: Data Collection & Preprocessing
- Collected 100–200 social media posts (e.g., tweets ,etc).
- Cleaned text data: removed stopwords, links, mentions, hashtags, and emojis.

### 🧠 Phase 3: Sentiment Analysis Engine
- Applied sentiment models (TextBlob, VADER, and BERT) to classify tweets as **Positive**, **Neutral**, or **Negative**.
- Optionally extracted keywords or topics for insights.

### 📈 Phase 4: Visualization & Alerts
- Visualized sentiment distribution using bar and pie charts.
- Triggered a **simulated alert** if more than **30% of feedback is negative**.

### 🤖 Phase 5: Real-Time Interaction (Bonus)
- Simulated bot responses to negative tweets using simple rule-based logic.

---

## 🛠️ Technologies Used
- Python (Pandas, Matplotlib, Seaborn)
- NLP Tools: TextBlob, VADER, BERT via Hugging Face Transformers
- Twitter API or sample datasets
- Jupyter Notebooks

---

## 📌 Outcome
A working prototype that analyzes real-time social media data to detect user sentiment, generate visual insights, and simulate alerts—helping Jatayuv AI enhance traveler engagement and experience.

---

## 🙌 Acknowledgment

This project was built as part of an internship assignment for Jatayuv AI and demonstrates skills in data science, ML, recommender systems.

## 📬 Contact
Beachani Jaya Krishna
📍jadcherla | CSE Graduate 
📧 beachanijayakrishna@gmail.com 

