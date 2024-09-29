# ♻️ Scrap Price Prediction using Linear Regression

## Project Overview
In this project, we build a linear regression model to predict the price of scrap materials based on various independent variables. The model helps uncover actionable insights that could optimize pricing strategies, streamline operations, and potentially unlock new revenue streams. By analyzing the relationships between variables, we aim to identify factors influencing scrap prices that may not have been previously tapped into for business growth or cost management.

---

## 🚀 Business Context and Problem Statement
Scrap metal trading is a market driven by numerous variables, including material type, demand fluctuations, geographic factors, and more. Understanding how these variables impact prices is critical for companies to remain competitive. Predictive models can not only forecast prices but also help businesses make informed decisions about inventory management, procurement, and sales strategies.

### 💡 Hypothesis
Before diving into data analysis, we hypothesized the following:
1. **Primary Drivers of Price**: Variables such as material type, market demand, and regional factors will likely emerge as the most significant contributors to scrap price determination.
2. **Counter-Intuitive Insights**: Certain overlooked factors, such as minor fluctuations in transport costs or seasonal demand, may have a larger-than-expected influence on prices.
3. **Revenue Generation Opportunities**: By predicting when prices will peak or drop, companies can adjust purchasing strategies to improve margins, thus uncovering untapped opportunities for profit.

---

## 🗂 Dataset Overview
The dataset used for this project includes:
- **Independent Variables**: Material type, transportation costs, demand fluctuations, geographical factors, and more.
- **Target Variable**: Scrap price.

The dataset was cleaned to remove any null values or noise to ensure a smooth analysis process.

---

## 🛠️ Approach
1. **Exploratory Data Analysis (EDA)**: Conducted to understand the relationships between variables and discover potential trends or anomalies. Special attention was given to factors that could be counter-intuitive or present unexpected business opportunities.
   
2. **Hypothesis Testing**: As we progressed, the hypotheses were continually tested to sharpen insights and guide further analysis. For instance, we examined whether transportation costs, often overlooked, had a significant impact on pricing trends.

3. **Model Building**: A multiple linear regression model was constructed using three key independent variables, with coefficients that describe their respective impact on the target variable—scrap price. 
   
4. **Evaluation**: The model's performance was evaluated using standard metrics such as R-squared, Mean Squared Error (MSE), and Adjusted R-squared, helping us quantify how well our hypotheses held up against the data.

---

## 📈 Key Insights and Findings
- **Confirmed Hypotheses**: As expected, material type and market demand were strong drivers of scrap prices.
- **Counter-Intuitive Insight**: Surprisingly, small variations in transportation costs significantly affected the price, offering potential optimization opportunities for businesses.
- **Actionable Business Insight**: By leveraging this predictive model, businesses could gain advanced knowledge of when prices will likely fluctuate, allowing them to adjust their buying strategies accordingly. For example, purchasing during forecasted price drops could improve profit margins significantly.

---

## Conclusion and Future Work
This project demonstrates the potential for predictive modeling in the scrap metal industry, offering key insights that can drive more informed business decisions. Future work could involve adding more variables, such as economic indicators or international demand trends, to enhance the model’s predictive power.

By proactively using these insights, businesses can tap into overlooked opportunities for revenue generation, thus staying ahead in a competitive market.

---

## How to Run the Project ⚙️
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/scrap-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd scrap-price-prediction
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the model:
   ```bash
   python linear_regression.py
   ```

---

## Acknowledgements
This project is part of a broader initiative to leverage data science for business insights, and I'd like to thank my collaborators for their support.

----
