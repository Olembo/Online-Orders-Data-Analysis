# Online-Orders-Data-Analysis
Analyze and visualize personal online shopping habits from 2018 to 2025.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Analysis Highlights](#analysis-highlights)
6. [Key Findings](#key-findings)
7. [Technologies](#technologies)
8. [Future Work](#future-work)
9. [License](#license)

---

## Project Overview

This repository explores a personal dataset of online orders placed by a two person household between 2018 and 2025. The goal is to:

- Understand spending trends over time  
- Measure savings from discounts and promotions  
- Compare shopping behavior between household members  
- Identify favorite categories and platforms  
- Assess delivery performance and costs  

All insights are tied to real-life events (e.g., moves, life milestones, the pandemic).

## Dataset

The cleaned CSV contains the following columns:
order_id, purchase_date, platform, items_name, category,
quantity, unit_price, shipping_cost, discount_amount,
total_price, payment_method, delivery_date, shipping_address,
city, country, return/refund, order_by,
delivery_days, discount_used, order_month, order_year,
order_month_year, is_returned


**Data sources:** personal online order history export (CSV) covering purchases from 2018 to 2025. All data is anonymized.

##  Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Olembo/online-orders-analysis.git
   cd online-orders-analysis

2. (Optional) Create and activate a virtual environment:
   python3 -m venv venv
   source venv/bin/activate

3. Install dependencies:
   pip install -r requirements.txt

## Usage

1. Open the Jupyter notebook:
jupyter notebook ProjectOrder.ipynb

2. Run all cells to reproduce data cleaning, aggregation, and visualizations.

3. View the interactive dashboard (if deployed):
  Tableau Public: DashboardLink#############

## Analysis Highlights

  1. Spending Trends: Quarterly and yearly spending annotated with key life events.

  2. Discount Metrics: 6.65% average savings rate (NT$25,764 total saved).

  3. Delivery Insights: 59% same-day delivery rate; average delivery time dropped to 0.9 days by 2023.

  4. Household Comparison: 520 orders by me vs. 255 by my wife; average order value NT$692 vs. NT$1,412.

  5. Category & Platform: Top spending on electronics and food; Shopee and Food Panda as top platforms.

## Key Findings

- Life Events Drive Spending: Major spikes in Q2 2020 (pandemic) and Q4 2024 (move to Taiwan & baby).

- High Savings: NT$25,764 saved through promos, with Uber Eats and Shopee offering the best deals.

- Fast Delivery: Over 75% of orders arrive within one day; free or low-cost shipping on most orders.


## Technologies

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Tableau Public

## Future Work
- Expand to include machine-learning–based purchase forecasting.


## License
This project is released under the MIT License.
