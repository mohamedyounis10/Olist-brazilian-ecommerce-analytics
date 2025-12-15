# Brazilian E‑Commerce Public Olist – Project 📊

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg">
  <img src="https://img.shields.io/badge/Pandas-2.0+-orange.svg">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg">
  <img src="https://img.shields.io/badge/PowerBI-Dashboard-yellow.svg">
  <img src="https://img.shields.io/badge/License-MIT-green.svg">
</p>

## 1. Overview

This project presents an end‑to‑end data analytics and business insights study on the **Brazilian E‑Commerce Public Olist** dataset. 
The goal is to explore customer behavior, seller performance, delivery efficiency, payment patterns, and review scores, and to present the findings through a clear and interactive **Power BI dashboard**.

This work was completed as part of the **Data Mining** course. 🎓

---

## 2. Project Structure 🧱

```text
Project/
├─ Brazilian E-Commerce Public Olist.pdf        # Dataset / project description (reference)
├─ Merge _ Schema.png                           # ERD / schema of table relationships
├─ notebook.ipynb                               # Main data analytics & EDA notebook
│
├─ Datasets/                                    # Raw CSV files from Olist
│  ├─ olist_customers_dataset.csv
│  ├─ olist_geolocation_dataset.csv
│  ├─ olist_order_items_dataset.csv
│  ├─ olist_order_payments_dataset.csv
│  ├─ olist_order_reviews_dataset.csv
│  ├─ olist_orders_dataset.csv
│  ├─ olist_products_dataset.csv
│  ├─ olist_sellers_dataset.csv
│  └─ product_category_name_translation.csv
│
└─ PowerBi-DashBoard/
   ├─ DataMiningProject.pbix                    # Power BI dashboard file
   ├─ br-states.json                            # GeoJSON for Brazil states map
   └─ delevary.png                              # Sample visualization / figure
```

---

## 3. Screenshots & Visuals 🖼️

> Replace the image paths below with your own (GitHub will show them automatically once you push the images).

- **Main Dashboard Overview**

  ```markdown
  ![Main Dashboard](images/main-dashboard.png)
  ```

- **Sales by Category & State**

  ```markdown
  ![Sales by Category and State](images/sales-by-category-state.png)
  ```

- **Delivery Performance & Delays Map**

  ```markdown
  ![Delivery Performance Map](images/delivery-performance-map.png)
  ```

- **Customer Reviews & Ratings**

  ```markdown
  ![Customer Reviews](images/customer-reviews.png)
  ```

> You can create a folder named `images/` in your repository and add your exported PNG screenshots there with matching file names.

---

## 4. Dataset

- **Name**: Brazilian E‑Commerce Public Olist  
- **Source**: Public e‑commerce dataset (commonly available on open data platforms such as Kaggle).  
- **Main entities**:
  - Customers, orders, order items, payments, reviews, products, sellers, and geolocation.
- **Key questions**:
  - How do orders and revenue evolve over time?
  - Which product categories and sellers perform best?
  - How efficient is the delivery process?
  - How do customers rate their overall experience?

---

## 5. Objectives 🎯

- **Customer analysis**: Understand customer distribution, demand, and behavior across regions.
- **Sales & product analysis**: Identify top‑performing categories, products, and trends.
- **Seller performance**: Evaluate seller activity, volume, and service quality.
- **Delivery performance**: Measure delivery times and delays versus estimated dates.
- **Review analysis**: Analyze review scores and customer satisfaction.
- **Dashboarding**: Build an interactive **Power BI** dashboard that summarizes the main KPIs and insights.

---

## 6. Methodology

The main steps implemented in `notebook.ipynb` include:

1. **Data loading**  
   Import all CSV files from the `Datasets/` folder.
2. **Data understanding**  
   - Inspect data types, distributions, and relationships between tables.  
   - Use the schema in `Merge _ Schema.png` to guide table joins.
3. **Data cleaning & preprocessing**  
   - Handle missing values and duplicates (if any).  
   - Standardize date/time formats.  
   - Create derived features (e.g., actual delivery time, delay vs estimated delivery).
4. **Data integration**  
   Join customers, orders, order items, payments, products, sellers, reviews, and geolocation into analytical tables.
5. **Exploratory Data Analysis (EDA)**  
   - Analyze orders over time and across regions.  
   - Study payment methods and order values.  
   - Examine seller performance and product categories.  
   - Explore review scores and their relationship with delivery.
6. **Visualization & reporting**  
   - Export curated datasets / tables for use in Power BI.  
   - Design the dashboard in `DataMiningProject.pbix` to present KPIs and insights.

---

## 7. How to Run the Notebook 💻

### 7.1. Prerequisites

- **Python 3.x**
- Recommended libraries (adjust to your environment / notebook content):
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn` (if any predictive models are used)
  - `jupyter` or `jupyterlab`

### 7.2. Setup (example)

```bash
# (Optional) create and activate a virtual environment
python -m venv venv
venv\Scripts\activate  # on Windows

# Install required packages (example)
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 7.3. Run

```bash
jupyter notebook
```

Then open `notebook.ipynb`, ensure the paths to the `Datasets/` folder are correct, and run the cells in order.

---

## 8. How to Use the Power BI Dashboard 📈

1. Install **Power BI Desktop**.
2. Open the file:
   - `PowerBi-DashBoard/DataMiningProject.pbix`
3. If prompted, update the data source paths to point to your local `Datasets/` directory.
4. Refresh the data to load the latest CSV files.
5. Explore the dashboard pages to view:
   - Overall KPIs (total orders, revenue, average review score, etc.).
   - Sales by product category, state, and seller.
   - Delivery performance and delays (with maps using `br-states.json`).
   - Review score distributions and related insights.

---

## 9. Results & Insights (Summary – to be customized)

> Replace this section with your specific findings.

You can briefly describe here:

- Main states and regions with the highest order volume.
- Best‑selling product categories and their contribution to revenue.
- Average delivery time and delay compared to estimated delivery date.
- Relationship between delivery performance and customer review scores.
- Recommendations to improve customer satisfaction and logistics.

---

## 10. Team 🤝

This project was developed collaboratively as a team.

- **Mohamed Younis** – [GitHub Profile](https://github.com/mohamedyounis10)
- **Jovanie Hanie** – [GitHub Profile](https://github.com/JovanieHanie)
- **Abdelrahman Omar** – [GitHub Profile](https://github.com/mohamedyounis10)

---

## 11. Acknowledgments 🙏

We would like to express our sincere gratitude to:

- **Dr. Mohamed Badawy** – for the continuous guidance, support, and valuable feedback throughout the Data Mining course and this project.  
- **Eng. Hosny Hossam** – for the technical support, practical advice, and help in implementing the analytical and visualization techniques.

---

## 12. License

You may add a license section here (e.g., MIT License) or keep the project private depending on your course and university requirements.
