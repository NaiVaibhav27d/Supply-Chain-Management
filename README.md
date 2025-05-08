# 📦 Supply Chain Management Dashboard Project

This project visualizes and analyzes supply chain data to help stakeholders monitor inventory, evaluate supplier performance, and optimize logistics.

## 📊 Dataset Overview

The dataset includes detailed information across the supply chain, covering:

| Feature                    | Description |
|---------------------------|-------------|
| `Product type`            | Type of product (e.g., skincare, haircare) |
| `SKU`                     | Stock Keeping Unit identifier |
| `Price`                   | Selling price of the product |
| `Availability`            | Stock available |
| `Number of products sold` | Quantity sold |
| `Revenue generated`       | Total revenue from sales |
| `Customer demographics`   | Demographic information of customers |
| `Stock levels`            | Inventory stock level |
| `Lead times`              | Days to procure stock |
| `Order quantities`        | Quantity ordered from supplier |
| `Shipping times`          | Time taken to deliver products |
| `Shipping carriers`       | Carrier used for shipment |
| `Shipping costs`          | Cost of shipping |
| `Supplier name`           | Supplier providing the product |
| `Location`                | Supplier’s location |
| `Production volumes`      | Number of units produced |
| `Manufacturing lead time` | Time taken to manufacture |
| `Manufacturing costs`     | Cost incurred in manufacturing |
| `Inspection results`      | Quality check status |
| `Defect rates`            | Percentage of defective items |
| `Transportation modes`    | Type of transportation used (e.g., road, air) |
| `Routes`                  | Route of shipment |
| `Costs`                   | Overall transportation or process cost |

## 🛠️ Technologies Used

- **Streamlit** – For building the interactive web app
- **Plotly** – For creating dynamic visualizations
- **DuckDB** – For in-memory querying and analytics on CSV data

## 📈 Objectives

- Visualize product sales and revenue trends
- Analyze defect rates and supplier performance
- Monitor shipping and logistics costs
- Evaluate lead and shipping times to optimize delivery
