# E-commerce Conversion Funnel Analysis

## 📌 Project Overview

This project analyzes e-commerce user behavior using SQL to understand how users move through the conversion funnel — from viewing a page to completing a purchase.

The analysis focuses on conversion rates, traffic sources, and the time users take to move through different stages of the purchasing journey.

## Business Questions

This project answers the following questions:

1. How many users reach each stage of the conversion funnel?
2. What is the conversion rate between each funnel stage?
3. Which traffic sources generate the most users and purchases?
4. How does conversion performance vary by traffic source?
5. How long does it take users to move from page view to cart and from cart to purchase?
6. Where are the major drop-offs in the customer journey?

## Tools & Technologies

* SQL Server
* T-SQL
* SQL CTEs
* Aggregate Functions
* CASE Statements
* Date & Time Functions
* Window Functions
* GitHub

## Funnel Stages

The analysis follows these main stages:

**Page View → Add to Cart → Checkout → Payment → Purchase**

These stages help identify where users continue their journey and where potential drop-offs occur.

## Dataset

The project uses a `user_events` table containing user interaction events.

### Main Fields

 Column                                      
 `user_id`                
 `event_type`                      
 `event_date`              
 `traffic_source` 

### Event Types

* `page_view`
* `add_to_cart`
* `checkout_start`
* `payment_info`
* `purchase`

##  Analysis Performed

### 1. Funnel Stage Analysis

Calculated the number of unique users reaching each stage of the funnel.

### 2. Conversion Rate Analysis

Calculated conversion rates between:

* Page View → Add to Cart
* Add to Cart → Checkout
* Checkout → Payment
* Payment → Purchase

### 3. Traffic Source Analysis

Compared funnel performance across different traffic sources to understand which channels generate users and purchases.

### 4. Time-to-Conversion Analysis

Measured the average time users take to move through the purchasing journey:

* View → Cart
* Cart → Purchase
* View → Purchase

## 💡 Key Insights

The analysis can help identify:

* Major funnel drop-off points
* Traffic sources with stronger conversion performance
* Areas where the purchasing journey may be improved
* How quickly users typically move from browsing to purchasing





## 🎯 Project Objective

The objective of this project is to demonstrate practical SQL and data analysis skills by analyzing e-commerce user journeys and identifying opportunities to better understand conversion behavior.

## 👤 Author

**Your Name**

Data Analyst | SQL | Excel | Power BI | Data Analysis
