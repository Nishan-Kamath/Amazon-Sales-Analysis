# Amazon Sales Analysis

This project analyzes Amazon sales data to provide insights into order status, fulfillment methods, order amounts, and shipping trends. The dataset includes various details about sales transactions and shipping information.

## Dataset

The dataset `Amazon Sale Report.csv` contains 128,976 entries and 21 columns, including:

- `index`: Index of the record
- `Order ID`: Unique identifier for the order
- `Date`: Date of the transaction
- `Status`: Current status of the order
- `Fulfilment`: Fulfillment method (Amazon or Merchant)
- `Sales Channel`: Sales platform (e.g., Amazon.in)
- `ship-service-level`: Shipping method (e.g., Standard, Expedited)
- `Category`: Product category (e.g., T-shirt, Shirt)
- `Size`: Product size
- `Courier Status`: Status of the shipment
- `Qty`: Quantity of items ordered
- `currency`: Currency used
- `Amount`: Total amount in INR
- `ship-city`: Shipping city
- `ship-state`: Shipping state
- `ship-postal-code`: Shipping postal code
- `ship-country`: Shipping country
- `B2B`: Indicates if the order is B2B
- `fulfilled-by`: Fulfillment provider
- `New`: Placeholder column (not used)
- `PendingS`: Placeholder column (not used)

## Analysis

1. **Order Status Distribution**
   - A bar chart visualizes the distribution of different order statuses.
   - Most orders are marked as "Shipped," indicating successful transactions.

2. **Fulfillment Method Distribution**
   - A pie chart shows the percentage distribution between Amazon and Merchant fulfillment.
   - Amazon handles a higher percentage of orders compared to merchants.

3. **Amount Distribution**
   - A histogram displays the distribution of order amounts in INR.
   - Most orders fall within the INR 500-1000 range, indicating a focus on relatively low-cost items.

4. **Category Distribution**
   - A count plot shows the distribution of orders across different product categories.
   - T-shirts are the most frequently sold item, while Trousers are the least.

5. **Size Distribution**
   - A count plot visualizes the distribution of order sizes.
   - The most popular size is Large (L), and sizes XS and 2XL have minimal or no orders.

6. **Top 10 Shipping States**
   - A bar chart highlights the top 10 shipping states based on the number of orders.
   - Maharashtra, Karnataka, and Tamil Nadu are the leading shipping destinations.

7. **High-Value Orders**
   - Orders above the average amount are filtered to identify high-value transactions.
   - The top 10 shipping states for high-value orders are also analyzed.

8. **Shipping Method Distribution**
   - A bar chart shows the distribution of shipping methods used.
   - The "Expedited" shipping method is preferred over the "Standard" method.

## How to Run

1. Clone this repository.
2. Ensure you have the necessary libraries installed:
   ```bash
   pip install pandas matplotlib seaborn
