# matplotlib-project
# Introduction
A beginner-friendly Python data visualization project using Matplotlib to analyze business performance, identify trends, compare results, and communicate insights through clear and meaningful charts in Jupyter Notebook.
## PROJECT  PERFPRMANCE VISUALIZATION
months = [1, 2, 3, 4, 5, 6]

revenue = [150000, 165000, 158000, 190000, 215000, 240000]

customers = [80, 92, 88, 110, 125, 140]

product_a = [45, 50, 48, 60, 68, 75]

product_b = [35, 40, 42, 45, 52, 58]


plt.figure(figsize=(8, 10))

plt.subplot(3, 1, 1)
plt.plot(months, revenue, marker="o")
plt.title("Monthly Revenue Trends")
plt.xlabel("Month")
plt.ylabel("Revenue(Naira)")

plt.subplot(3, 1, 2)
plt.plot(months, customers , marker="o")
plt.title("Monthly customers Growth")
plt.xlabel("Month")
plt.ylabel("Customers Growth")

plt.subplot(3, 1, 3)
plt.plot(months, product_a, "ok", months, product_b, "ob")
plt.title("Product Performance Comparison")
plt.xlabel("Month")
plt.ylabel("Product Performance")

plt.tight_layout()

plt.show()
<img width="790" height="989" alt="download" src="https://github.com/user-attachments/assets/bbb6416e-dc9b-4850-95e5-66c51ee483ff" />

## Business analysis and interpretation
Using the supplied dataset, these are the main observations you can report.

###### Observation 1: Revenue increased overall
Revenue rose from ₦150,000 in Month 1 to ₦240,000 in Month 6, an increase of ₦90,000, or 60%. However, revenue declined slightly from ₦165,000 in Month 2 to ₦158,000 in Month 3.
###### Observation 2: Customer numbers generally increased
Customers increased from 80 in Month 1 to 140 in Month 6. There was a small decline from 92 customers in Month 2 to 88 in Month 3.
###### Observation 3: Product A recorded higher sales in the final month
In Month 6, Product A sold 75 units, compared with 58 units for Product B. Product A sold 17 more units.
###### Observation 4: Revenue and customers both declined in Month 3
Revenue fell by ₦7,000 while customer numbers fell by four compared with Month 2. Both measures subsequently increased in Month 4.


## What additional information would help?
###### To understand the reasons behind these patterns, I would request:
- Product prices and profit margins.
- Marketing expenditure by month.
- Customer purchase frequency and average order value.
- Stock availability and operating expenses.
This would help the business owner investigate not only revenue and sales volume but also profitability and the possible factors behind changes in performance.

