# 🦈 Shark Tank India EDA Project

## 📜 Project Description
This project acts as a comprehensive **Exploratory Data Analysis (EDA)** of the **Shark Tank India** dataset. The goal is to uncover hidden trends in investment behavior, understand deal success rates, and analyze the performance of pitchers and sharks. By examining variables such as ask amounts, deal valuations, and equity percentages, this analysis provides valuable insights into what makes a successful pitch and how different sharks approach investments.

## 📊 Dataset Details
The analysis uses the `EDA_Shark_Tank_India.csv` dataset, which contains detailed information about pitches, including:
- **Pitcher Ask Amount & Valuation**
- **Deal Amount & Valuation**
- **Equity Offered & Given**
- **Shark Participation** (Ashneer, Anupam, Aman, Namita, Vineeta, Peyush, Ghazal)
- **Episode Number**

## ❓ Key Questions Answered
This project addresses 18 critical questions, including:
1. What is the success rate of deals?
2. What are the average and median deal amounts?
3. Which shark has made the highest number of investments?
4. What is the total amount invested by all sharks combined?
5. Are there outliers in deal equity distribution?
6. Is there a correlation between *Ask Valuation* and *Deal Valuation*?

## 🛠️ Technologies Used
- **Python** 🐍
- **Pandas** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization) 📈
- **Jupyter Notebook** (Interactive Analysis)

## 💡 Key Insights
- **Investment Personalities**: Sharks display distinct behaviors; some are high-volume investors (like Peyush and Aman), while others are more balanced or cautious.
- **Valuation Correlation**: There is a very weak linear relationship between what pitchers ask for and the final deal valuation.
- **Ask vs. Success**: Pitchers asking for smaller amounts (below ₹1 crore) have a significantly higher chance of securing a deal.

## 🚀 How to Run
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Open the notebook `ANIRBAN RAY_EDA PROJECT_SHARK TANK INDIA.ipynb` in Jupyter.
3. Run the cells to reproduce the analysis and visualizations.
