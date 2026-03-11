# 🛒 Market Basket Analysis – Apriori Algorithm

## Project Overview
This project demonstrates **Market Basket Analysis** using the Apriori algorithm in Python. 
The main goal is to find strong association rules between products and visualize them for business insights.

---

## Dataset
- **File:** `Market_Basket_Optimisation.csv`
- **Transactions:** 7501 rows
- **Products per transaction:** up to 20

---

## Steps in the Project
1. **Importing Libraries**  
   - `numpy`, `pandas`, `matplotlib`, `apyori`

2. **Data Preprocessing**  
   - Read CSV file and convert it to a list of transactions  
   - Remove `nan` values

3. **Applying Apriori Algorithm**  
   - Parameters:
     - `min_support = 0.003`
     - `min_confidence = 0.2`
     - `min_lift = 3`
     - `min_length = 2`
     - `max_length = 2`

4. **Visualizing Results**  
   - Display first rules from Apriori  
   - Convert results into a Pandas DataFrame with columns: `Left Hand Side`, `Right Hand Side`, `Support`, `Confidence`, `Lift`  
   - Display **Top 10 rules by Lift**  
   - Professional visualization with **Lift & Confidence on primary Y-axis** and **Support on secondary Y-axis**

---

## Algorithm Used
- **Apriori Algorithm** for Association Rule Learning

**Why Apriori?**
- Finds strong association rules between products
- Easy to implement and understand
- Helps in marketing and promotions
- Widely used in retail Market Basket Analysis

---

## Model Evaluation
Evaluation focuses on:
- **Support:** How frequently items appear together
- **Confidence:** Probability of the consequent given the antecedent
- **Lift:** Strength of the association relative to random chance
- Visualization of top rules for interpreting product relationships

---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Apyori

---
