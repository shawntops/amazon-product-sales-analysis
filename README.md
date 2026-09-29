# Amazon Product & Sales Analysis

## Overview

This Power BI project analyzes Amazon e-commerce product data to explore product performance, pricing, discounts, ratings, reviews, and category-level trends.

A major part of the project involved transforming imperfect source data into a structure suitable for analysis before building measures and interactive report visuals.

## Business Questions

The analysis was designed to explore questions such as:

- Which products appear most frequently in the dataset?
- Which categories contribute the most revenue?
- How do products and categories compare by average rating?
- How are discounts distributed across products?
- What patterns exist in customer ratings and reviews?
- How can product-level performance be summarized in an interactive report?

## Tools Used

- **Power BI**
- **Power Query**
- **DAX**
- Data cleaning and transformation
- Data modeling
- Interactive slicers
- Dashboard visualization

## Data Preparation

The source data required several cleaning and transformation steps before it could be analyzed reliably.

### Currency Cleaning

Price fields contained currency symbols that prevented direct numeric conversion. These values were cleaned before converting the columns into appropriate numeric data types.

### Percentage Transformation

The discount percentage field was converted into a proper percentage format for analysis and reporting.

### Error Handling

Conversion errors encountered during transformation were reviewed and replaced with null values where appropriate rather than allowing invalid values to distort the model.

### Duplicate Investigation

Duplicate-looking records were investigated instead of being removed blindly. Some records contained small differences across other fields, demonstrating the importance of checking the full record before treating observations as true duplicates.

### Product Name Transformation

Product descriptions contained names combined with additional specifications. The data was transformed to create cleaner product-name fields that were more useful for report visuals.

### Review Data

Reviewer-related fields were prepared for analysis, including the creation of a reviewer-focused table where needed.

## Dashboard KPIs

The completed Power BI dashboard summarizes the dataset with the following headline metrics:

| KPI | Result |
| --- | ---: |
| Total Products | **1K** |
| Average Rating | **4.10** |
| Average Discount | **47.7%** |
| Total Rating Count | **27M** |
| Unique Reviewers | **9K** |

## Analysis & Measures

Measures and report visuals were developed to examine:

- Product ratings and top-performing products
- Category performance by average rating
- User engagement across products
- Price versus rating patterns
- Discount behavior
- Reviewer activity

## Report Development

The Power BI report included analysis such as:

### Category Performance by Average Rating

Categories were compared using average customer ratings to identify differences in perceived product performance. **Office Products, Toys & Games, and Home Improvement** each displayed an average rating of approximately **4.3** on the dashboard, while **Computers & Accessories** followed at approximately **4.2**.

### Product Performance

Product-level analysis was used to identify highly rated products and compare user engagement. The dashboard's highest-rated products include items with **5.0 average ratings**, while a separate engagement visual highlights products attracting larger volumes of user activity.

### Interactive Filtering

Slicers were added to allow users to explore the report dynamically, including changing slicer presentation from button-style controls to dropdowns where appropriate.

## Key Analytical Takeaway

This project reinforced that e-commerce analysis requires more than building charts. Source fields such as prices, discounts, product descriptions, reviews, and duplicated records must first be validated and transformed into reliable analytical fields.

The cleaning decisions made in Power Query directly affected the quality of the measures and report visuals produced later in Power BI.

## Dashboard

The completed report includes:

- Five headline KPI cards
- Top-performing products by rating
- Category performance by average rating
- Top products by user engagement
- Price vs. rating scatter analysis
- Main-category filtering

**Dashboard screenshot:** ready to be added to the repository as `images/amazon-product-performance-dashboard.png`.

## Skills Demonstrated

- Power BI report development
- Power Query
- DAX measures
- Data cleaning
- Data type conversion
- Error and null handling
- Duplicate investigation
- Text transformation
- E-commerce analytics
- KPI development
- Interactive filtering
- Data visualization

---

### About Me

I'm **Temitope Shobayo**, a data analyst working with Excel, Power BI, and SQL to transform raw data into structured analysis and decision-ready insights.

[View my GitHub profile](https://github.com/shawntops) · [Connect with me on LinkedIn](https://www.linkedin.com/in/shobayo/)
