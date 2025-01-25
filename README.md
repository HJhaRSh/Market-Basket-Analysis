

# **Market Basket Analysis Using Apriori Algorithm and Power BI**

This project demonstrates **Market Basket Analysis** using the **Apriori algorithm** to identify **frequent itemsets** and generate **association rules**. The insights are visualized using **Power BI** to create an interactive dashboard for analyzing product relationships and customer purchasing behavior.

---

## **Project Overview**

- **Objective**: To identify frequently bought products and generate association rules for understanding relationships between products in a retail dataset.
- **Dataset**: Custom transaction dataset (CSV or Excel format) containing information about products, quantities, and transaction details.
- **Techniques Used**:
  - Data preprocessing and feature extraction.
  - Applying the **Apriori algorithm** for frequent itemset generation.
  - Evaluating association rules based on **support**, **confidence**, and **lift**.
  - Visualizing insights using Power BI.

---

## **Key Features**

1. **Python Implementation**:
   - **Data Preprocessing**: Cleans and formats transaction data for analysis.
   - **Frequent Itemset Generation**: Uses the **Apriori algorithm** to discover frequent itemsets.
   - **Association Rule Mining**: Generates association rules based on key metrics like support, confidence, and lift.
   - **CSV Export**: Exports the results to a CSV file for further analysis and Power BI integration.

2. **Power BI Visualization**:
   - **Scatter Plot**: Visualize product associations with metrics like support and confidence.
   - **Cluster Distribution**: Represent product associations using bar or pie charts.
   - **Association Analysis**: Explore customer behavior and product relationships through interactive filters.

3. **Insights**:
   - Identifying product pairs that are often bought together.
   - Recognizing high-confidence product recommendations.
   - Understanding which products boost sales together.

---

## **Project Structure**

- **Python Script**:
  - `market_basket_analysis.py`: Full Python code for data preprocessing, frequent itemset generation, rule mining, and CSV export.

- **Dataset**:
  - `transactions.csv`: Input dataset used for analysis (replace with your own data).

- **Power BI File**:
  - `Market_Basket_Analysis_Dashboard.pbix`: Interactive Power BI dashboard for exploring the results.

- **Clustered Results**:
  - `association_rules_cleaned.csv`: CSV file containing product associations and their metrics.

---

## **Tools & Libraries**

- **Python**:
  - Libraries: `pandas`, `mlxtend`, `scipy`, `tabulate`
- **Power BI**:
  - For interactive dashboard creation and visualization.

---

## **How to Run the Project**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/market-basket-analysis.git
   ```

2. Install the required Python libraries:
   ```bash
   pip install pandas mlxtend scipy tabulate
   ```

3. Run the Python script:
   ```bash
   python market_basket_analysis.py
   ```

4. Open `Market_Basket_Analysis_Dashboard.pbix` in **Power BI Desktop** to view and interact with the dashboard.

---

## **Results**

- **Frequent Itemsets**: Products frequently bought together.
- **Association Rules**: Product recommendations based on association rules (e.g., "if A is bought, B is also likely to be bought").
- **Product Insights**: Insights on customer purchasing behavior and product combinations.

---

## **Future Enhancements**

- Incorporate more advanced recommendation algorithms (e.g., collaborative filtering, content-based filtering).
- Experiment with alternative algorithms like **FP-growth** for faster frequent itemset generation.
- Add integration with a real-time transactional system for continuous analysis.

---

## **Contributions**

Contributions are welcome! Feel free to open an issue or submit a pull request with suggestions or improvements.

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
