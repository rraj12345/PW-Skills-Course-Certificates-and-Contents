# PW Skills | Data Analytics Learning Portfolio

A documented collection of coursework, coding assignments, and learning references from PW Skills data analytics training. The repository covers the core workflow of working with relational data, querying it, applying Python-based analysis, understanding statistical measures, and communicating patterns through charts.

## Repository snapshot

| Artifact type | Count | Evidence in this repository |
|---|---:|---|
| SQL scripts | 2 | Database schema setup and query assignments |
| Jupyter notebooks | 3 | NumPy, statistics, and visualization practice |
| PDF resources | 4 | SQL assignments, Python basics, and course certificate |
| Image reference | 1 | Relational database schema |
| **Total** | **10** | **All 10 files are linked and described below** |

**Learning areas:** SQL & relational databases · Python/NumPy · Statistics · Data visualization

## Problem

Coursework files are useful only when learners and reviewers can quickly understand their purpose, prerequisites, and relationship to other materials. A flat collection of scripts, notebooks, PDFs, and diagrams can obscure the learning journey and make it harder to reproduce exercises.

## Solution

This repository organizes the coursework conceptually and provides a direct, file-level guide. It links each artifact to the skills it supports and gives a practical sequence for using the materials.

**Important scope distinction:** This is a learning archive, not a production analytics application or a single business case. The outcomes described here are learning artifacts and demonstrated practice, not commercial KPIs.

## Repository content | File-by-file guide

### 1. SQL and relational databases

**[Mavenmovies.sql](Mavenmovies.sql) — Database schema and setup**

A MySQL schema script based on the Sakila sample database, configured under the `mavenmovies` schema. It defines relational entities including actors, films, customers, stores, rentals, payments, addresses, cities, countries, and categories. Table definitions include primary keys, foreign-key relationships, indexes, and column constraints. This file is the data-model foundation for the SQL exercises.

**[sql_assignment.sql](sql_assignment.sql) — SQL query and database concepts practice**

A question-led SQL practice file. The opening exercises cover creating tables and applying constraints such as primary key, unique, check, not-null, and default. Later sections use the Maven Movies/Sakila schema for record retrieval, distinct values, filtering, pattern matching, joins, aggregate calculations, and grouping. The file also contains sections on window functions, normalization, and common table expressions (CTEs). Example analytical questions include rental counts, revenue by store, film/category performance, and customer activity.

**[PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf) — SQL assignment reference**

A PDF assignment resource retained from the coursework. Use it as a written reference alongside the SQL scripts. The exact question wording and page content are in the PDF itself.

**[SQL Assignment.pdf](SQL%20Assignment.pdf) — Additional SQL assignment reference**

A separate SQL coursework PDF. It is intentionally listed independently from `PW_SQL_Assignment.pdf`; open the document for its exact questions and material.

**[Schema.png](Schema.png) — Relational schema visual**

A visual reference for the database tables and their relationships. Use it to identify key columns and trace join paths before writing queries that combine films, actors, customers, inventory, rentals, and payments.

### 2. Python and data analysis

**[Python Basics.pdf](Python%20Basics.pdf) — Python fundamentals reference**

A PDF learning resource for Python basics. It complements the notebooks and provides a reference before moving into numerical and analytical programming. Refer to the document for its exact topic sequence.

**[Numpy Assignment.ipynb](Numpy%20Assignment.ipynb) — NumPy hands-on exercises**

A question-based notebook with extensive NumPy practice. The visible exercises cover creating arrays with integer, floating-point, and complex data types; converting data types; inspecting shape, size, dimensions, item size, and strides; creating zeros, ones, ranges, and identity matrices; converting lists to arrays; using views; concatenating and stacking arrays; indexing and slicing one-, two-, and three-dimensional arrays; reshaping and flattening; inserting and deleting values; arithmetic and string operations; and descriptive calculations such as mean, percentiles, and correlation. It is a practical introduction to array-based computation.

**[Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb) — Statistical calculations in Python**

A notebook for implementing statistical concepts using Python. It imports NumPy, Pandas, SciPy statistics, Matplotlib, Seaborn, and Python's built-in statistics module. Exercises include generating sample integer data and calculating measures such as mean, median, mode, weighted mean, and geometric mean, followed by additional statistical problem-solving. It helps connect statistical definitions with programmatic calculations.

**[Visualization.ipynb](Visualization.ipynb) — Data visualization library practice**

A notebook organized into visualization assignments for Matplotlib, Seaborn, Plotly, and Bokeh. It starts with common chart tasks such as scatter, line, and bar plots, then practices visualization using the named libraries. Use it to explore how charts can reveal distributions, comparisons, and relationships.

### 3. Certification

**[PwSkills Certification.pdf](PwSkills%20Certification.pdf) — Course credential**

The PW Skills certificate document associated with this learning archive. The PDF itself should be used for the exact credential title, dates, and issuing details.

## Approach | Learning workflow

```text
Database schema
      ↓
SQL fundamentals and query practice
      ↓
Python foundations and NumPy
      ↓
Statistical calculations
      ↓
Data visualization and communication
```

1. **Explore the schema:** Start with `Mavenmovies.sql` and `Schema.png`.
2. **Write queries:** Practice constraints, filtering, joins, aggregation, window functions, normalization, and CTEs using `sql_assignment.sql` and the PDFs.
3. **Build Python fluency:** Review `Python Basics.pdf` and complete the NumPy notebook.
4. **Calculate and interpret:** Work through the statistics notebook; explain what each statistic says about the data.
5. **Visualize:** Complete the chart exercises and choose visual forms that match the analytical question.

## Results | Quantitative inventory and qualitative outcomes

### Repository coverage

| Measure | Result |
|---|---:|
| Total files documented | **10 / 10** |
| SQL scripts | **2** |
| Jupyter notebooks | **3** |
| PDF resources | **4** |
| Schema/reference images | **1** |
| Learning domains | **4** |

### Skills practiced

- **SQL:** Relational schema reading, constraints, filtering, joins, aggregation, window functions, normalization, and CTEs.
- **Python/NumPy:** Array creation, data types, indexing, slicing, reshaping, vectorized operations, and numerical summaries.
- **Statistics:** Descriptive measures and statistical exercises using Python libraries.
- **Visualization:** Creating and comparing charts with Matplotlib, Seaborn, Plotly, and Bokeh.

The counts above are verifiable repository inventory metrics. No business impact, production usage, performance uplift, or quantified time saving is claimed because this repository contains coursework rather than a measured business deployment.

## Tools and environment

| Purpose | Tools |
|---|---|
| Database | MySQL |
| Programming | Python 3 |
| Numerical/data analysis | NumPy, Pandas, SciPy |
| Visualization | Matplotlib, Seaborn, Plotly, Bokeh |
| Notebook environment | Jupyter Notebook, JupyterLab, Google Colab |

## How to run the materials

### Run Python notebooks

Open any `.ipynb` file in Jupyter Notebook, JupyterLab, or Google Colab. Install the common dependencies:

```bash
pip install numpy pandas scipy matplotlib seaborn plotly bokeh
```

### Run SQL exercises

Use MySQL or a compatible environment. Create/load the required schema before running the assignment queries. The schema diagram is a useful companion when checking joins and foreign-key paths.

## Action | How to extend this learning archive

1. **Validate:** Re-run queries and test boundary cases, NULL handling, duplicates, and join cardinality.
2. **Interpret:** Add a short business interpretation after each important statistical result or chart.
3. **Apply:** Turn the SQL exercises into questions such as customer rental frequency, top-performing film categories, and store-level revenue.
4. **Improve:** Add chart titles, units, axis labels, and clear takeaways to visualization exercises.
5. **Build:** Use these foundations in a separate end-to-end project with a defined business problem, documented assumptions, data cleaning, analysis, validation, findings, and recommendations.

## Reproducibility and limitations

- The two SQL assignment PDFs are separate resources; their exact question lists should be read from the PDFs.
- The Python Basics PDF and certificate are linked as source documents rather than paraphrased page by page.
- Some notebooks generate random data, so numerical outputs may change between runs.
- SQL syntax and notebook behavior can vary by database engine and package version.
- These materials represent coursework and practice. They should not be interpreted as production-ready code without review and testing.
- Original files are unchanged; this README is an index and explanation layer.

## Author

**Raj Kishore Agrawal**  
[GitHub profile](https://github.com/rraj12345)
