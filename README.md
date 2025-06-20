# AI Customer Review Analyzer

A simple yet powerful **AI-powered Web Application** designed to analyze customer reviews using **Google Gemini API**, classify them into sentiment categories (Positive, Negative, Neutral), and visually display the results. Built using **React.js** for the frontend, **Flask (Python)** for the backend, and **MongoDB** for storing data, this tool helps businesses quickly understand customer opinions.

---

## 🖼️ Preview

| Home Page | Review Input Sample |
|:--------:|:------------------:|
| <img src="./Home Page.png" width="800"/> | <img src="./review sample.png" width="800"/> |

| Result Bar Graph | Sentiment Classification Graph |
|:---------------:|:-----------------------------:|
| <img src="./result bargraph.png" width="800"/> | <img src="./result values.png" width="800"/> |

---

## 🎥 Live Demo

## 🎥 Live Demo

<p align="center">
  <img src="./Review Analyser Video.gif" width="400"/>
</p>


---

## 📖 About the Project

The **AI Customer Review Analyzer** allows users to enter multiple product or service reviews and instantly receive an AI-generated sentiment analysis result. This system saves time and effort required to manually process thousands of customer reviews.

---

## 🔍 Detailed Explanation

### 🎯 **Objective:**

To automate the analysis of customer reviews by determining the sentiment (Positive, Negative, Neutral) using an AI model, thereby assisting businesses in gaining actionable insights from customer feedback.

---

### ⚙️ **System Workflow:**

#### 1. **Frontend (React.js):**
- Users input a list of customer reviews into a simple and intuitive form.
- On clicking the **"Analyze"** button:
  - Reviews are sent to the Flask backend via REST API.
  - The received sentiment results are shown as **dynamic bar charts**.
  - Data visualizations are rendered using chart libraries to give immediate insights.

#### 2. **Backend (Flask & Python):**
- The Flask server receives the reviews via API requests.
- For each review:
  - The **Gemini AI API** is called to classify the sentiment.
  - The result (Positive/Negative/Neutral) is stored in **MongoDB** for logging and future use.
- The backend returns the sentiment results back to the React frontend.

#### 3. **Database (MongoDB):**
- Stores all input reviews along with their analyzed sentiment for historical data tracking.

---

## 🚀 Features

✔️ **Multi-Review Analysis** — Analyze multiple reviews in one go.  
✔️ **Google Gemini AI Integration** — Real-time AI-powered text sentiment analysis.  
✔️ **Beautiful Data Visualization** — Sentiment results shown as easy-to-read bar graphs.  
✔️ **MongoDB Storage** — Persist the review data and sentiment for later review or audit.  
✔️ **Fully Responsive UI** — React-based smooth, modern web interface.  
✔️ **Easy to Extend** — Modular code structure for future improvements.

---

## 🛠️ Technologies Used

- **Frontend:** React.js, Axios, Chart.js
- **Backend:** Flask (Python)
- **AI Model:** Google Gemini API
- **Database:** MongoDB (NoSQL)
- **Other Tools:** Yarn, Node.js, Python libraries (Flask-CORS, Requests)
