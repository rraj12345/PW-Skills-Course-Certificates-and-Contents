# PW Skills | Data Analytics Learning Portfolio

A structured archive of coursework, coding assignments, and reference resources completed during PW Skills data analytics training. It brings together practical work in SQL, Python, statistics, and data visualization.

## Repository at a glance

| Category | Files | Included artifacts |
|---|---:|---|
| SQL and relational databases | 5 | 2 SQL scripts, 2 assignment PDFs, 1 schema image |
| Python and analytics | 4 | 3 Jupyter/Python learning resources and 1 Python reference PDF |
| Certification | 1 | Course certificate |
| **Total** | **10** | **Code, notebooks, reference material, and credential** |

## Problem → Solution

**Problem:** Learning materials can become difficult to navigate when database scripts, notebooks, PDFs, and diagrams sit together without a clear explanation. A reviewer may see the files but not understand the learning sequence or what each artifact demonstrates.

**Solution:** This repository acts as a documented learning index. Each file has a direct link and a concise description, and the learning path connects database setup to querying, Python foundations, statistical analysis, and visualization.

> **Scope:** This is a coursework and skills-practice repository. It is not a production system, a client engagement, or a single end-to-end business analytics project.

## Repository content | File-by-file explanation

### A. SQL and relational databases

| File | What it contains | Why it is useful |
|---|---|---|
| [Mavenmovies.sql](Mavenmovies.sql) | MySQL schema and table definitions based on the Sakila sample database, including film, actor, customer, store, rental, payment, address, city, country, and category entities. Defines keys, indexes, and relational constraints. | Provides the database foundation for understanding entities and writing multi-table queries. |
| [sql_assignment.sql](sql_assignment.sql) | SQL answers and practice questions covering table creation, constraints, primary/foreign keys, filtering, LIKE/IN/BETWEEN, joins, aggregates, grouping, window functions, normalization, and CTEs. Examples use the Maven Movies/Sakila tables. | Builds query-writing skills from foundational SQL to analytical patterns. |
| [PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf) | SQL coursework assignment/reference document. | Lets learners review the written SQL assignment material alongside the code. |
| [SQL Assignment.pdf](SQL%20Assignment.pdf) | A second, separate SQL assignment/reference PDF. | Preserves another course document rather than merging distinct resources. |
| [Schema.png](Schema.png) | Diagram of the database structure and table relationships. | Helps identify join paths and key relationships before writing queries. |

### B. Python, statistics, and visualization

| File | What it contains | Why it is useful |
|---|---|---|
| [Python Basics.pdf](Python%20Basics.pdf) | Python fundamentals reference material. | Provides a starting point before working through the Python notebooks. |
| [Numpy Assignment.ipynb](Numpy%20Assignment.ipynb) | Question-based NumPy exercises: array creation and types, conversion, shape/size/dimensions, strides, array constructors, ranges, concatenation, stacking, indexing, slicing, reshaping, arithmetic, string operations, and summary calculations. | Practices efficient numerical data handling and array manipulation. |
| [Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb) | Statistical exercises implemented with NumPy, Pandas, SciPy, Matplotlib, Seaborn, and Python's statistics module. Includes descriptive-statistics tasks such as mean, median, mode, weighted mean, geometric mean, and further statistical questions. | Connects statistical concepts with calculations in Python. |
| [Visualization.ipynb](Visualization.ipynb) | Charting assignments grouped around Matplotlib, Seaborn, Plotly, and Bokeh. Includes chart exercises such as scatter, line, and bar plots. | Practices selecting and creating visual representations of data. |

### C. Certification

| File | What it contains |
|---|---|
| [PwSkills Certification.pdf](PwSkills%20Certification.pdf) | PW Skills course certificate. The PDF is the source of truth for the credential name and award details. |

## Approach | How the learning materials connect

1. **Model the data:** Read `Mavenmovies.sql` and inspect `Schema.png` to understand tables, primary keys, foreign keys, and join paths.
2. **Query the data:** Work through `sql_assignment.sql` and the SQL PDFs, progressing from constraints and filtering to joins, aggregation, window functions, normalization, and CTEs.
3. **Prepare for analysis in Python:** Review `Python Basics.pdf`, then use `Numpy Assignment.ipynb` to practice arrays and numerical operations.
4. **Apply statistics:** Use `Statistics_Assignment_PwSkills.ipynb` to calculate descriptive measures and work through statistical exercises.
5. **Communicate insights:** Use `Visualization.ipynb` to create charts and explore different Python visualization libraries.

## Results | What this repository demonstrates

- **10 documented files** across SQL, Python/analytics, and certification.
- **4 learning domains:** relational databases and SQL, Python/NumPy, statistics, and data visualization.
- **2 SQL scripts** for database setup and query practice.
- **3 notebooks** for hands-on numerical, statistical, and visualization exercises.
- **4 PDF documents** for course references, assignments, and certification.
- **1 schema image** to support relational data understanding.

These counts describe repository contents, not business performance. The work demonstrates learning and practice; it does not claim production deployment, revenue growth, time savings, or model accuracy.

## Tools and technologies

**Database:** MySQL / SQL  
**Programming and analysis:** Python 3, NumPy, Pandas, SciPy  
**Visualization:** Matplotlib, Seaborn, Plotly, Bokeh  
**Environment:** Jupyter Notebook, JupyterLab, Google Colab

## Getting started

### Python notebooks

Open a notebook in Jupyter Notebook, JupyterLab, or Google Colab. Install the commonly used packages with:

```bash
pip install numpy pandas scipy matplotlib seaborn plotly bokeh
```

### SQL exercises

Use a compatible MySQL environment. Load or create the required Maven Movies/Sakila schema before executing queries. Refer to `Schema.png` to understand the relationships used by joins.

## Action | Suggested next steps

- Re-run the SQL exercises and validate results against expected row counts and edge cases.
- Turn selected queries into business questions, for example: most-rented films, customer rental frequency, and revenue by store or category.
- Add a short interpretation to statistical outputs rather than reporting calculations alone.
- Improve visualizations with clear titles, axis labels, units, and a one-sentence insight.
- For a future portfolio project, document the dataset, business problem, assumptions, methodology, validation, findings, and recommendations.

## Notes and limitations

- The two SQL PDFs are distinct files; consult each PDF for its exact assignment questions.
- The Python Basics PDF and certificate should be opened directly for their exact contents and credential details.
- Some notebook exercises use generated or random values, so outputs can vary between runs.
- Package versions and SQL dialect differences may affect execution.
- Original coursework files are preserved; only this README is documentation.

## Author

**Raj Kishore Agrawal**  
[GitHub profile](https://github.com/rraj12345)
