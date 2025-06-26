# conversionanalysis-sql
Boosting Conversion for an E-commerce Brand

📘 Case Study: Boosting Conversion for an E-commerce Brand
Background:
Your company, ShopNex, is a mid-size e-commerce brand in India. Over the past 3 months, your traffic has increased, but sales conversion has dropped. Leadership wants you to deep dive using the existing SQL database to find out what's happening.

🧩 Scenario Objective
Make data-driven decisions by writing a series of SQL search queries across multiple dimensions—traffic, product views, cart actions, checkout, and order status.

You will need to:

Find where drop-offs happen

Analyze user behavior

Identify top-performing and poor-performing products

Suggest next steps backed by query insights

🗂️ Sample Database Schema
user_activity(user_id, session_id, activity_type, product_id, activity_timestamp)

activity_type can be: view, add_to_cart, checkout, purchase

product(product_id, category, price, stock_qty, is_active)

orders(order_id, user_id, product_id, quantity, order_status, order_date)

order_status: completed, cancelled, returned, failed

site_traffic(date, source, visits)


