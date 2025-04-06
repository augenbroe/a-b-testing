# a-b-testing

## 🎯 Objective
To determine whether the new signup page design leads to a statistically significant improvement in user conversion rates using a simulated dataset of 10,000 users.

## 📊 Dataset
- Simulated data using Python and NumPy
- Users randomly assigned to either `control` or `variant` group
- Conversion outcomes generated using binomial probabilities:
  - Control group: 10% conversion rate
  - Variant group: 12% conversion rate

## 🧠 Methodology
- Calculate group sizes and conversion rates
- Use a **two-proportion z-test** to assess statistical significance
- Visualize results with a bar chart of conversion rates

## ✅ Results
- Conversion Rate (Control): ~10%
- Conversion Rate (Variant): ~12%
- P-value: [insert after running the notebook]  
- Based on the p-value and business context, a recommendation is made regarding whether to implement the new page design.

## 📈 Visualization
Bar plot comparing conversion rates across groups for a quick snapshot of performance.

## 🧰 Tools Used
- Python
- Pandas
- NumPy
- Statsmodels
- Seaborn / Matplotlib
- Google Colab (for running the analysis)
