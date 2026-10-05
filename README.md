# Filter Dataset Records Using Pandas

## Veda Technology – AI/ML Internship Task

This project demonstrates how to filter and retrieve relevant records from a dataset using **Python and Pandas**. Different filtering conditions are applied to a Student Performance Dataset using Boolean operators.

---

## 📌 Objective

The objective of this task is to learn how to:

- Filter rows from a Pandas DataFrame.
- Apply single filtering conditions.
- Apply multiple filtering conditions.
- Use Boolean operators such as `&` and `|`.
- Use parentheses when combining multiple conditions.
- Check the number of records returned after filtering.

---

## 🛠️ Tools and Technologies

- **Python**
- **Pandas**
- **Jupyter Notebook**
- **GitHub**

---

## 📊 Dataset

For this task, a **Student Performance Dataset** was created using Pandas.

The dataset contains the following columns:

| Column | Description |
|---|---|
| `Student_ID` | Unique ID of each student |
| `Name` | Student name |
| `Gender` | Gender of the student |
| `Age` | Age of the student |
| `Math_Score` | Mathematics score |
| `Science_Score` | Science score |
| `Attendance` | Attendance percentage |

The dataset contains **15 student records**.

---

## 🔍 Filtering Examples

### 1. Math Score Greater Than 80

Students with a Math score greater than 80 were selected.

```python
high_math = df[df["Math_Score"] > 80]
