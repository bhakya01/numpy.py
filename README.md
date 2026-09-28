# NumPy & Pandas Data Analysis Assignment

## 📌 Project Overview

This project demonstrates fundamental **NumPy and Pandas operations** using practical data-analysis scenarios.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Google Colab / Jupyter Notebook

---

# 1. NumPy Array Operations

## 🌡️ Scenario

Daily average temperatures recorded over two weeks are analyzed using NumPy.

### Week 1 Temperature Data

```python
[22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9]
```

### Tasks Covered

* Create a 1D NumPy array
* Inspect array shape
* Check data type
* Find number of elements
* Convert Celsius to Fahrenheit
* Find maximum temperature
* Find minimum temperature
* Calculate mean temperature
* Perform array indexing
* Perform array slicing

### Slicing Operations

The following temperature ranges are extracted:

* First three days
* Weekend temperatures (last two days)
* Middle three days

---

# 2. NumPy 2D Array

A 2D NumPy array is created to represent temperature data for two weeks.

### Week 1

```text
22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9
```

### Week 2

```text
19.2, 22.5, 21.3, 24.0, 23.5, 22.8, 20.1
```

### Tasks Covered

* Create a 2D NumPy array
* Inspect shape
* Inspect data type
* Find total number of elements
* Extract Week 1 temperatures
* Extract Week 2 temperatures
* Extract weekend temperatures for both weeks

---

# 3. Pandas Series

A Pandas Series named `marks` is created using student marks and custom rank labels.

### Marks

| Rank  | Mark |
| ----- | ---: |
| Rank1 |   95 |
| Rank2 |   92 |
| Rank3 |   89 |
| Rank4 |   85 |
| Rank5 |   80 |

### Tasks Covered

* Create a Pandas Series
* Use integer indexing
* Use `.loc`
* Use `.iloc`
* Apply boolean filtering
* Modify Series values
* Remove an entry
* Calculate CGPA

### CGPA Calculation

```python
CGPA = Marks / 10

# 4. Pandas DataFrame

A transaction dataset is created using Pandas.

### Dataset Columns

* `TransactionID`
* `ProductCategory`
* `Region`
* `Amount`

### Product Categories

* Electronics
* Clothing
* Furniture

### Regions

* North
* South
* East
* West

---

## 🔍 Data Exploration

The following DataFrame operations are performed:

### Display Data

* Complete DataFrame
* First five rows using `.head()`
* Last five rows using `.tail()`

### Inspect Structure

* Shape
* Column names
* Data types

### Select Columns

The following columns are selected:

```python
ProductCategory
Amount
```

### Select Last Three Columns

The last three columns are retrieved using `.iloc` or `.loc`.

### Filter Transactions

Transactions are filtered where:

```text
Region = North
AND
Amount > 200
```

### Category Analysis

Value counts are calculated for:

```python
ProductCategory
```

### Region Analysis

Unique regions are identified using:

```python
unique()
```

### Regional Average

The mean transaction amount is calculated for each region using:

```python
groupby()
```

---

# 5. DataFrame Manipulation

Several modifications are performed on the transaction dataset.

### Update Transaction

The amount for:

```text
TransactionID = 102
```

is changed to:

```text
165
```

### Add Discount Column

A new column called `Discount` is created.

The discount is calculated as:

```python
Discount = Amount * 0.10
```

### Remove Transaction

The row with:

```text
TransactionID = 109
```

is removed from the DataFrame.

### Delete Discount

After completing the calculation, the `Discount` column is deleted.

---

# 📂 Project Structure

```text
NumPy-Pandas-Assignment/
│
├── README.md
│
├── NumPy_Pandas_Assignment.ipynb
│
└── images/
    └── screenshots/
```

---

# 🎯 Learning Outcomes

After completing this assignment, the following concepts are practiced:

### NumPy

* Creating arrays
* 1D and 2D arrays
* Array properties
* Mathematical operations
* Aggregation functions
* Indexing
* Slicing
* Array shape and size

### Pandas Series

* Series creation
* Custom indexes
* `.loc`
* `.iloc`
* Boolean masking
* Updating values
* Removing values
* Mathematical calculations

### Pandas DataFrame

* DataFrame creation
* Data exploration
* Column selection
* Row filtering
* Unique values
* Value counts
* GroupBy operations
* Mean calculations
* Updating rows
* Adding columns
* Removing rows
* Deleting columns

---

# 💡 Key Concepts

This project provides hands-on practice with fundamental data-analysis operations that are commonly used when working with real-world datasets.

The NumPy section focuses on **numerical array operations**, while the Pandas section focuses on **structured data manipulation and analysis**.

---

## 👩‍💻 Author

**Bhakya M**

Data Analytics Learner | Python | SQL | Excel | Power BI | Pandas | NumPy

---

## ⭐ Conclusion

This assignment demonstrates the basic workflow of using **NumPy and Pandas for data analysis**, from creating and inspecting data structures to filtering, calculating, grouping, and modifying data.

It serves as a foundation for progressing toward more advanced **Python Data Analytics and Exploratory Data Analysis (EDA)** projects.


