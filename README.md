# End-to-End E-Commerce Product Analysis 

### 🔗 [Click here to view the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Book1_17652865669810/Dashboard1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link)

---

##  Project Overview

This project analyzes sales performance across various e-commerce product categories (Watches, Bags, Accessories). The goal was to take raw, messy data and turn it into actionable business intelligence regarding **Revenue, Volume, and Pricing Strategy**.

My workflow was divided into two main stages:
1.  **Data Engineering (Python):** Cleaning and processing raw data using Pandas in Jupyter Notebook.
2.  **Data Visualization (Tableau):** Building an interactive dashboard to explore the cleaned data.

### Dashboard Preview
<img width="2730" height="1534" alt="Dashboard 1" src="https://github.com/user-attachments/assets/a712bb9f-060c-450d-b639-5ece11fa4401" />

---

## Part 1: Data Cleaning & Analysis (Python)

Before visualizing, I used Python (`E-Commerce Product Analysis.ipynb`) to prepare the dataset. The raw data contained formatting issues that needed to be resolved to ensure accurate analysis.

**Key Python Steps:**
* **Library Usage:** Used `Pandas` for data manipulation and `Seaborn`/`Matplotlib` for initial exploratory data analysis (EDA).
* **Data Cleaning:**
    * Handled missing values in critical columns.
    * Converted currency strings and numerical fields into proper data types for calculation.
    * extracted relevant features from text fields.
* **Output:** Exported a refined dataset (`cleaned_data.csv`) ready for Tableau.

---

## Part 2: Tableau Dashboard Insights

Once the data was clean, I imported it into Tableau to answer specific business questions.

**Key Questions Answered:**
1.  **Where is the revenue coming from?** The Treemap reveals which specific categories drive the most financial value, differentiating them from those that simply drive volume.
2.  **Do discounts actually drive volume?** I used Scatter Plots to visualize the correlation between discount percentages and unit sales.
3.  **Does price stability matter?** I used Box-and-Whisker plots to analyze the pricing distribution within categories, identifying outliers and consistent pricing bands.
4.  **Quality Checks:** Analyzed customer ratings to see if high-volume products maintain high customer satisfaction.

---

## Technical Skills Demonstrated

This project showcases a full data analysis lifecycle:

* **Python (Pandas & NumPy):** Data wrangling, cleaning, and type conversion.
* **Tableau Calculated Fields:** Created custom metrics like `Estimated Revenue` (Units Sold × Price).
* **Advanced Visualization:**
    * **Treemaps** for hierarchical data.
    * **Box Plots** for statistical distribution analysis.
    * **Scatter Plots** for correlation analysis.
* **Dashboard Design:**
    * Implemented **Filter Actions** for cross-chart interactivity.
    * Designed **Custom Tooltips** to tell data stories in plain English.
    * Applied **Data-Ink Ratio** principles (removing gridlines, optimizing labels) for a professional look.

---

## Repository Structure

* `E-Commerce Product Analysis.ipynb`: The Jupyter Notebook containing the Python data cleaning and EDA code.
* `cleaned_data.csv`: The final processed dataset used for the dashboard.
* `README.md`: Project documentation.

---

## Author

**Buddhi Sankalana Mahanama**
* [Tableau Public Profile](https://public.tableau.com/app/profile/your-profile)
