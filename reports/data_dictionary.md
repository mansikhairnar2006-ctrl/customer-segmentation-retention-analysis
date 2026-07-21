# Data Dictionary

## Customers Table

| Column | Description |
|---------|-------------|
| customer_id | Identifier for each customer record |
| customer_unique_id | Unique customer across multiple purchases |
| customer_zip_code_prefix | Customer ZIP code prefix |
| customer_city | Customer city |
| customer_state | Customer state |

---

## Orders Table

| Column | Description |
|---------|-------------|
| order_id | Unique order identifier |
| customer_id | Links to the customer table |
| order_status | Current status of the order |
| order_purchase_timestamp | Date and time when the order was placed |
| order_delivered_customer_date | Date the customer received the order |

---

## Order Payments Table

| Column | Description |
|---------|-------------|
| payment_type | Payment method |
| payment_value | Amount paid |

---

## Products Table

| Column | Description |
|---------|-------------|
| product_id | Product identifier |
| product_category_name | Product category |

---

## Reviews Table

| Column | Description |
|---------|-------------|
| review_score | Customer rating (1–5) |
| review_comment_message | Customer review text |