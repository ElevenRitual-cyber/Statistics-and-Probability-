### **Mean, Median, and Mode**  

In statistics, **Mean, Median, and Mode** are measures of **central tendency**, which help summarize a dataset with a single representative value. Each measure has its strengths and weaknesses depending on the nature of the data.  

---

## **1. Mean (Arithmetic Average)**  
### **Definition:**  
The **mean** is the sum of all values divided by the total number of values. It represents the "balance point" of a dataset.  

### **Formula for Mean:**  
For a dataset \( X = [x_1, x_2, ..., x_n] \), the mean is calculated as:  
\[
\mu = \frac{1}{n} \sum_{i=1}^{n} x_i
\]
Where:  
- \( \mu \) = Mean  
- \( n \) = Number of values  
- \( x_i \) = Each individual value  

### **Example:**  
Consider the dataset: **[10, 20, 30, 40, 50]**  
\[
\text{Mean} = \frac{10 + 20 + 30 + 40 + 50}{5} = \frac{150}{5} = 30
\]

### **Advantages of Mean:**  
✔ Uses all data points, making it a **comprehensive** measure.  
✔ Easy to calculate and widely used in statistics and data analysis.  

### **Disadvantages of Mean:**  
❌ **Sensitive to outliers** (extremely high or low values).  
❌ Not always representative when data is skewed.  

### **When to Use Mean?**  
- When data is **normally distributed** (bell-shaped).  
- When **outliers are not present** (e.g., average height of students).  
- When **all values are equally important** (e.g., calculating GPA).  

---

## **2. Median (Middle Value)**  
### **Definition:**  
The **median** is the middle value in an ordered dataset. If there are an even number of values, the median is the average of the two middle values.  

### **How to Find the Median?**  
- **Step 1:** Sort the data in ascending order.  
- **Step 2:** Identify the middle value.  
  - If \( n \) is **odd**, the median is the middle value.  
  - If \( n \) is **even**, the median is the **average** of the two middle values.  

### **Example 1 (Odd Number of Values):**  
Dataset: **[10, 20, 30, 40, 50]**  
\[
\text{Median} = 30
\]  

### **Example 2 (Even Number of Values):**  
Dataset: **[10, 20, 30, 40, 50, 60]**  
\[
\text{Median} = \frac{30 + 40}{2} = 35
\]

### **Advantages of Median:**  
✔ **Not affected by outliers** (e.g., extreme incomes in salary data).  
✔ Works well with **skewed distributions**.  

### **Disadvantages of Median:**  
❌ Ignores actual values (only considers the middle position).  
❌ Less efficient for small datasets.  

### **When to Use Median?**  
- When data is **skewed** (e.g., house prices, salaries).  
- When **outliers are present** (e.g., CEO salaries in a company).  
- When data contains **ordinal values** (e.g., ranking survey responses).  

---

## **3. Mode (Most Frequent Value)**  
### **Definition:**  
The **mode** is the value that appears most frequently in a dataset.  

### **Types of Mode:**  
- **Unimodal:** One mode (e.g., [1, 2, 2, 3] → Mode = 2).  
- **Bimodal:** Two modes (e.g., [1, 2, 2, 3, 3] → Modes = 2 & 3).  
- **Multimodal:** More than two modes (e.g., [1, 1, 2, 2, 3, 3] → Modes = 1, 2, & 3).  
- **No Mode:** If all values appear the same number of times.  

### **Example:**  
Dataset: **[10, 20, 20, 30, 40, 40, 40, 50]**  
\[
\text{Mode} = 40
\]  

### **Advantages of Mode:**  
✔ Works well with **categorical data** (e.g., most popular car color).  
✔ Useful when **the most common value is important** (e.g., most frequently sold product).  

### **Disadvantages of Mode:**  
❌ Can have **multiple modes**, making it hard to interpret.  
❌ Not always useful for **small datasets**.  

### **When to Use Mode?**  
- When dealing with **categorical data** (e.g., most common hair color).  
- When finding the **most common response** in surveys.  
- When analyzing **frequency distributions** (e.g., most frequent error code in software logs).  

---

## **Comparison of Mean, Median, and Mode**  

| Measure  | Best Used When | Affected by Outliers? | Example Use Case |
|----------|--------------|----------------|----------------|
| **Mean** | Data is evenly distributed | ✅ Yes | Average test scores |
| **Median** | Data has outliers/skewness | ❌ No | Median house prices |
| **Mode** | Finding most frequent value | ❌ No | Most popular phone brand |

---

## **Practical Applications & Python Code**  

### **Example Dataset: Salaries in a Company**  
Dataset: **[30k, 35k, 40k, 45k, 50k, 1M]** (1M is an outlier)  

1. **Mean:**  
\[
\text{Mean} = \frac{30 + 35 + 40 + 45 + 50 + 1000}{6} = 200.8k
\]  
🚨 **Misleading because of the 1M outlier!**  

2. **Median:**  
Sorted dataset: **[30k, 35k, 40k, 45k, 50k, 1M]**  
\[
\text{Median} = \frac{40k + 45k}{2} = 42.5k
\]  
✅ **Better representation of typical salary.**  

3. **Mode:**  
If dataset = **[30k, 35k, 40k, 40k, 50k, 1M]**, mode = **40k**  
🔹 **Useful if looking for the most common salary.**  


- **Use Mean** when data is normally distributed and **no outliers exist**.  
- **Use Median** when data is **skewed** or has **outliers**.  
- **Use Mode** for **categorical data** or when finding **most frequent values**.  
  [More](https://statisticseasily.com/measures-of-central-tendency-mean-mode-median/)



  ![image](https://github.com/user-attachments/assets/1b9bf679-3b70-4b37-94df-3735d0962a97)

