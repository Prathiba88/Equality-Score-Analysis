# Equality-Score-Analysis
Gender pay equality analysis using Excel and Tableau
# Gender Pay Equality Analysis - Daikibo

This project analyzes gender-based pay equality using Daikibo's internal compensation data.

## 📄 Dataset
- **Source:** Daikibo Industrials
- **File:** `Equality Table - Completed.xlsx`
- **Columns:**
  - Factory
  - Job Role
  - Equality Score (from -100 to +100)
  - Equality Class (Fair, Unfair, Highly Discriminative)

## 📊 Visualization
- A Tableau dashboard was created to show:
  - Down Time per Factory
  - Down Time per Device Type
- Screenshot included as `dashboard-screenshot.png`.

## 🧮 Classification Logic
| Score Range       | Equality Class          |
|-------------------|--------------------------|
| -10 to +10        | Fair                     |
| -20 to -11 or 11–20 | Unfair                  |
| < -20 or > +20     | Highly Discriminative   |

## 🛠 Tools Used
- Microsoft Excel (Data classification)
- Tableau (Visualization)
- Git & GitHub (Version Control & Publishing)

## ✍ Author
Prathiba P
