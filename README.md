# NYC Jobs Posting Analysis 💼🌟

This project analyzes a dataset of NYC job postings to understand salary trends and factors affecting them. 🚀

---


## Power BI Dashboard 🔄

[View the interactive Power BI Dashboard here](#)

---

![NYC Jobs Analysis GIF](https://media.giphy.com/media/l3q2K5jinAlChoCLS/giphy.gif)

## Data Cleaning and Preprocessing 🏯

1. **Handling Missing Values:**
   - 🔄 Dropped 9 columns with more than 50% null values.
   - ✨ Imputed missing categorical values with the mode in 5 columns.

2. **Text Data Cleaning:**
   - Cleaned and standardized text data in columns like `Job Description`, `Preferred Skills`, and `Minimum Qual Requirements` by:
     - 🔄 Removing special characters.
     - ✨ Removing extra spaces.
     - 🔄 Converting text to lowercase.

3. **Date Conversion:**
   - ⏳ Converted 3 date columns (`Posting Date`, `Posting Updated`, `Process Date`) to datetime objects.

4. **Target Variable Creation:**
   - 🔍 Merged `Salary Range From` and `Salary Range To` to create a new target variable `Salary_Range_Mean`.

5. **Duplicate Removal:**
   - 🌀 Removed 2274 duplicate rows from the dataset.

---

## Exploratory Data Analysis (EDA) 🔢

- Performed **univariate** and **multivariate** analysis to understand variable relationships.
- Used visualizations like:
  - 🔹 Countplots.
  - 🔹 Barplots.
  - 🔹 Heatmaps.
  - 🔹 Pairplots.
- Explored the relationship between `Salary_Range_Mean` and other features such as:
  - `Agency`.
  - `Posting Type`.
  - `Business Title`.
  - `Civil Service Title`.
  - `Level`.
  - `Job Category`.

---

## Key Findings 📊

1. **Salary Range:**
   - Salaries vary significantly across agencies:
     - 💰 The Department of Environment Protection pays an average salary of **$117,500**.
     - 💰 The Taxi & Limousine Commission pays an average salary of **$105,000**.

2. **Posting Type:**
   - ✔️ Internal and external postings have similar average salary ranges, both around **$89,000**.

3. **Job Titles:**
   - Certain job titles command higher salaries. For example:
     - 🎓 `Deputy Commissioner, Technology & Innovation` has an average salary of **$210,500**.

4. **Civil Service Titles:**
   - ⭐ Civil service titles like `ADMINISTRATIVE LAW JUDGE` have high average salary levels at **$163,500**.

5. **Job Category:**
   - ⚖️ Categories like `Engineering, Architecture, & Planning` have the highest average salary of **$98,000**.

6. **Career Level:**
   - 📚 Senior and managerial roles have higher salary ranges compared to entry-level roles:
     - Senior-level and managerial roles average **$100,000**.
     - Entry-level roles average **$85,000**.

---

## Conclusion 📝

This analysis sheds light on the salary landscape of NYC job postings. The results are useful for job hunters and employers who wish to understand salary expectations and factors influencing remuneration.

---

## Future Work 🔄

- 💡 Build a prediction model to forecast salary based on job characteristics.
- 🔎 Investigate other factors affecting salary, such as location, experience, and education.
- 🌐 Conduct trend analysis of salaries over time.

---

