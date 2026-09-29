# E-commerce Conversion Funnel Analysis

## 📌 Project Overview

This project analyzes e-commerce user behavior using SQL to understand how users move through the conversion funnel — from viewing a page to completing a purchase.

The analysis focuses on conversion rates, traffic sources, and the time users take to move through different stages of the purchasing journey.

<img width="1051" height="497" alt="image" src="https://github.com/user-attachments/assets/c4906cb2-91bc-43b1-8797-bec0caac2353" />


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

##  Key Insights

- **Overall conversion is 16.6%** (4,268 visitors → 708 purchases in the last 30 days).
- **Biggest drop-off:** page view → add to cart (only 31.2%). Cart → checkout is the second biggest (71.4%). Payment → purchase is strong at 92.2%.
- **Email is the best channel:** 33.9% view-to-purchase, about 2x organic and 5x social, from just 10% of traffic.
- **Social drives 29% of views but only 12% of purchases** (6.7% view-to-purchase). Users browse but rarely add to cart.
- **Users convert quickly:** about 11 min view → cart, 13 min cart → purchase, 25 min view → purchase, consistent across all sources.

##  Recommendations

1. Invest more in email marketing (highest-converting, lowest-volume channel).
2. Reduce or rethink social spend; improve landing pages before scaling it.
3. Optimize product pages to lift view → cart, the largest drop-off.
4. Reduce cart abandonment with early shipping info, guest checkout, and quick reminder emails.




##  Project Objective

The objective of this project is to demonstrate practical SQL and data analysis skills by analyzing e-commerce user journeys and identifying opportunities to better understand conversion behavior.

##  Author

**Muhammad Bukhtawar Javed | BJ Analysis**

Data Analyst | SQL | Excel | Power BI | Data Analysis
