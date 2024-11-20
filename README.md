# Marketing Insights for E-Commerce Company

#### Business Problem Statement  
A fast-growing e-commerce company seeks to shift from intuition-based marketing to a data-driven approach. By analyzing customer demographics, transaction data, marketing spend, and discount details from 2019, the project aims to:  
- Gain a comprehensive understanding of customer behavior.  
- Optimize marketing campaigns across various channels.  
- Leverage insights to enhance customer retention.  
- Predict customer lifetime value (CLTV).  
- Drive sustainable revenue growth.  

---
### Dataset Description  

#### **1. Online_Sales.csv**  
| **Column**           | **Description**                                                |
|-----------------------|----------------------------------------------------------------|
| **CustomerID**        | Unique identifier for each customer.                          |
| **Transaction_ID**    | Unique identifier for each transaction.                       |
| **Transaction_Date**  | Date when the transaction occurred.                           |
| **Product_SKU**       | Unique identifier for the product.                            |
| **Product_Description** | Description of the purchased product.                      |
| **Product_Category**  | Category of the product.                                      |
| **Quantity**          | Number of items purchased.                                    |
| **Avg_Price**         | Price per unit of the product.                                |
| **Delivery_Charges**  | Shipping or delivery charges for the transaction.             |
| **Coupon_Status**     | Indicates if a discount coupon was applied (Yes/No).          |

#### **2. Customers_Data.csv**  
| **Column**           | **Description**                                                |
|-----------------------|----------------------------------------------------------------|
| **CustomerID**        | Unique identifier for each customer.                          |
| **Gender**            | Gender of the customer (Male/Female).                         |
| **Location**          | Geographical location of the customer.                       |
| **Tenure_Months**     | Duration (in months) the customer has been with the company.  |

#### **3. Discount_Coupon.csv**  
| **Column**           | **Description**                                                |
|-----------------------|----------------------------------------------------------------|
| **Month**            | Month in which the discount coupon was applied.               |
| **Product_Category** | Category of the product eligible for the discount.            |
| **Coupon_Code**      | Unique identifier for the discount coupon.                    |
| **Discount_pct**     | Percentage of discount offered by the coupon.                 |

#### **4. Marketing_Spend.csv**  
| **Column**           | **Description**                                                |
|-----------------------|----------------------------------------------------------------|
| **Date**             | Date of marketing activity.                                    |
| **Offline_Spend**    | Amount spent on offline marketing (e.g., TV, radio, print).    |
| **Online_Spend**     | Amount spent on online marketing (e.g., social media, ads).    |

#### **5. Tax_Amount.csv**  
| **Column**           | **Description**                                                |
|-----------------------|----------------------------------------------------------------|
| **Product_Category** | Category of the product.                                       |
| **GST**              | Percentage of GST applicable to the product category.          |

---

### Approach  

This project employs data analysis techniques to extract actionable insights that drive customer retention and revenue growth.  

#### Key Objectives:  
1. **Customer Segmentation and Behavior Analysis**: Understand drivers of customer acquisition and churn through descriptive statistics and segmentation.  
2. **Marketing Campaign Effectiveness**: Evaluate the impact of online and offline marketing efforts on revenue and customer behavior using hypothesis testing.  
3. **Discount Optimization**: Analyze the effect of promotions on revenue and customer engagement to refine discount strategies.  
4. **CLTV Prediction**: Build models to estimate future customer value for prioritizing retention efforts.  
5. **Cross-Selling Opportunities**: Perform market basket analysis to uncover frequently co-purchased products.  
6. **Data-Driven Recommendations**: Present actionable insights through compelling visualizations and reports.  
 
