# 📉 Teco Customer Churn Analysis

This project investigates customer churn patterns in the telecommunications sector using historical data. The goal is to uncover the primary factors that lead to customer attrition and recommend actionable strategies to improve customer retention.

## 🎯 Objective

To analyze churn behavior across various dimensions—such as contract types, payment methods, customer demographics, and tenure—and provide insights that can support business decisions in reducing churn rates.

## 🧰 Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  
- **Dataset:** Customer Churn.csv

## 📂 Project Structure

Teco-Customer-Churn-Analysis/
│
├── TCA.ipynb # Main notebook for analysis and visualizations
├── Customer Churn.csv # Customer dataset with churn info
├── README.md # Project documentation
└── visuals/ (optional) # Saved visualizations and graphs


## 📊 Key Insights

- 📅 **Contract Type and Churn**:  
  - 42% of customers with month-to-month contracts churned, compared to only 11% with yearly contracts and 3% with two-year contracts.
  - 🔁 **Recommendation**: Encourage long-term contracts through incentives.

- 💳 **Payment Method and Churn**:  
  - 45% churn rate among customers using electronic checks, versus ~15–18% for other methods.
  - 🔐 **Recommendation**: Promote secure, reliable payment options like credit cards and bank transfers.

- 🕒 **Tenure and Churn**:  
  - Customers with less than 1 year of tenure show a 50% churn rate; this drops to 15% for those with 3+ years.
  - 🎯 **Recommendation**: Focus on first-year customer engagement programs.

- 🌐 **Internet Service Type**:  
  - Fiber Optic users had a 30% churn rate compared to 20% for DSL users.
  - ⚙️ **Recommendation**: Improve fiber service quality or offer loyalty benefits.

- 👴 **Senior Citizens**:  
  - Churn rate among seniors is 41%, versus 26% for non-seniors.
  - ❤️ **Recommendation**: Create personalized support programs for elderly customers.

## 📈 Visualizations

- Bar graphs comparing churn across contract types and payment methods.
- Line charts showing churn rate trends over customer tenure.
- Percentage comparisons between service types and demographics.

## 🔍 Future Enhancements

- Integrate predictive modeling using logistic regression or decision trees.
- Build a Streamlit-based dashboard for interactive analysis.
- Link churn probability scores with customer contact strategies.

## 🤝 Contributions

Contributions are welcome! Feel free to fork the repo, improve the analysis, or add a dashboard and submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
