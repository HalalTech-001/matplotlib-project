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

