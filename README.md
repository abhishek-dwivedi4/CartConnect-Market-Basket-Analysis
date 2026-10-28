 # CartConnect: Market Basket Analysis 🛒

An advanced data analytics project focused on uncovering hidden associations and customer purchasing behaviors using transactional retail data. 

## 📌 Project Overview
The **CartConnect** project implements Market Basket Analysis to understand which products are frequently bought together. Utilizing the **Apriori algorithm** within **IBM SPSS Modeler**, the analysis processes extensive transactional datasets to generate actionable cross-selling insights.

* **Dataset:** `Groceries_dataset.csv` (comprising over 38,000 transaction records).
* **Tool Used:** IBM SPSS Modeler.
* **Core Algorithm:** Apriori Association Rules.

---

## ⚙️ Implementation Workflow

1. **Project Setup & Data Import:** Loaded raw transactional data into SPSS Modeler using a Var. File source node.
2. **Data Roles Configuration:** Configured the Type node to define field measurement levels and set the `Item` field role to **Both** while excluding non-analytical identifiers (`Transaction ID`, `Member Number`, `Date`).
3. **Model Configuration:** Configured the Apriori node with transactional formatting (`Transaction_ID` as ID, `Item` as Content).
4. **Parameter Tuning:** Adjusted model parameters (Minimum Support set to 1.0% - 2.0%, Minimum Confidence set to 10% - 15%).
5. **Execution & Evaluation:** Generated association rules evaluated via three primary metrics:
   * **Support:** Measures the overall popularity of the item combination.
   * **Confidence:** Measures the reliability and conditional probability of the inference.
   * **Lift:** Evaluates positive correlation (`Lift > 1`).

---

## 📁 Repository Contents
* **`CartConnect_ IBM SPSS Modeler Guide.pdf`**: Detailed step-by-step implementation and technical guide.
* **`CartConnect Market Basket Analysis Final on 29th.pptx`**: Comprehensive presentation deck detailing project objectives, workflow, and business metrics.

---

## 💼 Resume Highlights
* "Engineered a Market Basket Analysis model in IBM SPSS using the Apriori algorithm on a 38k+ row dataset.
* "Optimized model parameters (Support, Confidence, Lift) to mine transactional data for frequent itemsets and association rules.

---

## 👨‍💻 Author
**Abhishek Dwivedi**
