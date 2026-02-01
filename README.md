# 📈 AI for Stock Decision Making

## 🔍 Project Overview
This project applies **Machine Learning and Deep Learning techniques** to historical stock market data in order to support **investment decision-making**.  
Instead of only predicting future stock prices, the project focuses on transforming predictions into **actionable decisions**:  
👉 **Buy** or **Not Buy**.

The system analyzes time-based stock behavior across multiple sectors and companies to learn patterns that help investors make more informed decisions.

---

## 🎯 Problem Statement
Stock market prices are highly volatile and influenced by many factors, making manual analysis difficult and unreliable for individual investors.  
Relying solely on intuition or basic indicators can lead to poor investment decisions.

**The challenge:**  
How can historical stock data be leveraged using AI models to predict future price movements and convert them into clear investment decisions?

---

## 💡 Proposed Solution
This project builds an AI-driven pipeline that:
1. Processes historical stock market data.
2. Constructs time windows to capture temporal patterns.
3. Trains multiple models to predict future prices.
4. Converts predictions into **Buy / Not Buy** decisions.
5. Compares model performance to select the most effective approach.

The solution emphasizes **decision-oriented AI**, not just raw prediction.

---

## 📊 Dataset Description
- Real historical stock market data.
- Covers **10 different sectors**.
- Includes **10 companies per sector**.
- Time span: up to **4 years of historical data**.
- Data organized with company and sector information.
- Features include stock prices over time.

> The dataset structure allows both cross-sector analysis and time-series modeling.

---

## ⚙️ Tools & Technologies
- **Programming Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - TensorFlow / Keras

---

## 🔎 Methodology

### 1️⃣ Data Cleaning & Preprocessing
- Handling missing values.
- Selecting relevant features.
- Formatting data for time-series analysis.
- Preparing clean and structured datasets for modeling.

---

### 2️⃣ Time Window Construction
Instead of analyzing single-day prices, the project builds **time windows** that represent stock behavior over consecutive days.

This allows models to learn:
- Trends
- Volatility
- Temporal dependencies

This step significantly improves the realism of predictions.

---

### 3️⃣ Model Development
Multiple models are trained and evaluated:

- **Linear Regression**
  - Used as a baseline model.
  - Helps assess whether the data is predictable.

- **Random Forest**
  - Captures non-linear relationships.
  - Performs well in decision-based classification.

- **LSTM (Long Short-Term Memory)**
  - A deep learning model specialized for time-series data.
  - Learns long-term temporal patterns in stock prices.

---

### 4️⃣ Decision Classification
Predicted prices are converted into:
- **Buy**
- **Not Buy**

This step transforms numerical predictions into practical investment decisions.

---

### 5️⃣ Model Evaluation
Models are evaluated using:
- Accuracy
- ROC Curve
- Comparative performance analysis

The best-performing model is selected based on both prediction quality and decision reliability.

---

## 📈 Results & Insights
- Time-series models outperform simple regression approaches.
- LSTM demonstrates strong performance in capturing temporal stock behavior.
- Decision-based classification provides clearer value than raw price prediction.
- The system shows potential for real-world investment support tools.

---

## 🚀 Live Testing
The project includes a live testing phase where:
- Trained models are loaded.
- Next-day stock prices are predicted.
- Immediate **Buy / Not Buy** decisions are generated.

This demonstrates the system’s applicability beyond academic experimentation.

---

## 📝 Conclusion
This project highlights how AI can be used to bridge the gap between **data analysis and decision-making** in financial markets.  
By combining time-series modeling with machine learning, the system provides a structured and scalable approach to stock investment decisions.

---

## 👥 Project Contributors
This project was developed as a **collaborative academic team project**.  
My contribution focused on data preprocessing, model building, and performance evaluation.

Information Technology – Artificial Intelligence & Data Science  
King Saud University
