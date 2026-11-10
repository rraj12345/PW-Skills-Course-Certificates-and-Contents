# PW Skills | Data Analytics Learning Portfolio

A structured learning archive from PW Skills data analytics training, containing SQL scripts, Python notebooks, assignment references, a database schema image, and a course certificate. The materials document practice across the analytics workflow: understanding relational data, querying it, performing numerical and statistical analysis, and communicating patterns visually.

> **Portfolio positioning:** This repository showcases coursework and foundational practice. It is not represented as a production deployment, client project, or single end-to-end business solution.

## At a glance

| Content | Count | Repository evidence |
|---|---:|---|
| SQL scripts | **2** | Schema setup and SQL exercises |
| Jupyter notebooks | **3** | NumPy, statistics, and visualization |
| PDFs | **4** | Two SQL assignment resources, Python basics, certificate |
| Schema image | **1** | Database relationship reference |
| **Total files** | **10** | Every file has a direct link and description |
| **Learning domains** | **4** | SQL, Python/NumPy, statistics, visualization |

## Problem → Solution

**Problem:** A collection of learning files can be difficult to evaluate or reuse when each script, notebook, PDF, and diagram is presented without context. The reader needs to know what each artifact contains, what skills it demonstrates, what should be opened first, and what can be practiced next.

**Solution:** This repository provides a navigable index with file-level descriptions and a suggested learning sequence. It connects database setup to SQL practice, Python foundations, statistics, and visualization while preserving the original coursework files.

## Repository content | Detailed file guide

### SQL and relational database foundations

#### [Mavenmovies.sql](Mavenmovies.sql)
**Purpose:** Create the relational database used for Maven Movies/Sakila-style SQL practice.

**Contents:** Creates the `mavenmovies` MySQL schema and defines tables for actors, actor awards, addresses, categories, cities, countries, customers, films, and other film-rental entities. The definitions include data types, primary keys, foreign keys, indexes, and constraints.

**Use it to:** Explore how a normalized relational database is represented in SQL, inspect table dependencies, and prepare the database environment for analytical queries.

#### [sql_assignment.sql](sql_assignment.sql)
**Purpose:** Practice SQL syntax and solve database questions against the learning schema.

**Contents:** Starts with table creation and integrity constraints (primary key, unique, check, not-null, default), then covers primary/foreign-key identification, record retrieval, DISTINCT, WHERE, LIKE, IN, BETWEEN, LIMIT, joins, aggregate functions, GROUP BY, and analytical questions. Later sections cover window functions, normalization (1NF/2NF/3NF), and CTEs. Example questions include rental counts, average rental duration, revenue by store, rental counts by film category, customer spending, and top-rented films.

**Use it to:** Move from basic querying to multi-table analysis and more advanced SQL patterns. Validate queries in the database rather than treating saved answers as automatically correct.

#### [PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf)
**Purpose:** Preserve the written SQL assignment material supplied with the course.

**Contents and use:** An assignment/reference PDF associated with SQL learning. Review the document itself for exact questions and instructions, then use it alongside the SQL script for practice.

#### [SQL Assignment.pdf](SQL%20Assignment.pdf)
**Purpose:** Keep the additional SQL assignment document accessible as a separate resource.

**Contents and use:** A second SQL coursework PDF, distinct from `PW_SQL_Assignment.pdf`. Consult the PDF for its exact exercise list and use it to supplement query practice.

#### [Schema.png](Schema.png)
**Purpose:** Provide a visual map of the relational database.

**Contents and use:** Shows the database schema used by the SQL exercises. Refer to it to locate primary/foreign-key relationships and determine the correct join path across film, actor, customer, inventory, rental, payment, and related tables.

### Python and analytical programming

#### [Python Basics.pdf](Python%20Basics.pdf)
**Purpose:** Provide a reference for Python fundamentals.

**Contents and use:** A Python basics course resource that supports the programming exercises. Open the PDF for its exact topic breakdown; use it as a reference when revisiting language fundamentals in the notebooks.

#### [Numpy Assignment.ipynb](Numpy%20Assignment.ipynb)
**Purpose:** Build practical skills in numerical arrays and vectorized operations.

**Contents:** A question-led notebook covering array creation; integer, float, and complex data types; type casting; array shape, size, dimensionality, item size, and strides; zeros, ones, ranges, and identity matrices; list-to-array conversion; views; concatenation and stacking; indexing, boolean indexing, and slicing across dimensions; reshaping and flattening; insertion and deletion; element-wise arithmetic; string-array operations; and statistical summaries including mean, percentiles, and correlation.

**Use it to:** Practice how NumPy stores and manipulates numerical data efficiently, and how arrays support downstream analysis.

#### [Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb)
**Purpose:** Apply statistical concepts through Python code.

**Contents:** Imports NumPy, Pandas, SciPy statistics, Matplotlib, Seaborn, and Python's statistics module. Exercises include generating sample data and calculating descriptive measures such as mean, median, mode, weighted mean, and geometric mean, with additional statistical problem-solving.

**Use it to:** Translate statistical definitions into calculations, compare measures, and explain what a result says about a dataset. Check assumptions and interpretation when using statistical tests.

#### [Visualization.ipynb](Visualization.ipynb)
**Purpose:** Practice visual exploration and presentation of data.

**Contents:** A set of assignments grouped into Matplotlib, Seaborn, Plotly, and Bokeh sections. The notebook begins with common chart exercises, including scatter, line, and bar plots, and introduces multiple Python visualization libraries.

**Use it to:** Practice chart construction and explore how different visual forms communicate comparisons, distributions, and relationships.

### Certification

#### [PwSkills Certification.pdf](PwSkills%20Certification.pdf)
**Purpose:** Retain the course certificate with the learning materials.

**Contents and use:** The PW Skills certification document. Open the PDF for the exact certificate title, award date, and credential details; this README does not infer details that should be read from the certificate itself.

## Approach | Suggested learning sequence

```text
Mavenmovies.sql + Schema.png
          ↓
SQL assignment and query practice
          ↓
Python Basics.pdf + NumPy notebook
          ↓
Statistics notebook
          ↓
Visualization notebook
          ↓
Independent analytics project
```

1. **Understand the data:** Read the schema and identify entities, keys, and relationships.
2. **Query with intent:** Work through SQL constraints, filters, joins, aggregates, window functions, normalization, and CTEs.
3. **Prepare to analyze:** Review Python fundamentals and practice array manipulation with NumPy.
4. **Quantify patterns:** Calculate and interpret descriptive statistics; review assumptions before drawing conclusions.
5. **Communicate findings:** Select appropriate plots and write a clear takeaway for each visualization.
6. **Transfer the skills:** Apply the same workflow to a new dataset and document the business question, method, validation, and recommendation.

## Results | Measurable repository coverage

| Measure | Verified count |
|---|---:|
| Files described in this README | **10 / 10 (100%)** |
| SQL scripts | **2** |
| Notebooks | **3** |
| PDFs | **4** |
| Schema images | **1** |
| Learning domains | **4** |

**Qualitative outcomes:** The collection provides practice in relational data modeling, foundational-to-advanced SQL querying, numerical array manipulation, statistical calculations, and data visualization across several Python libraries.

**Measurement boundary:** The figures above measure repository coverage and artifact types. They do not represent business impact, model performance, production usage, revenue improvement, or time saved. No such outcome is claimed because the repository contains coursework rather than a measured business deployment.

## Tools and technologies

- **Database:** MySQL / SQL
- **Programming:** Python 3
- **Numerical and statistical analysis:** NumPy, Pandas, SciPy, Python `statistics`
- **Visualization:** Matplotlib, Seaborn, Plotly, Bokeh
- **Environment:** Jupyter Notebook, JupyterLab, Google Colab

## Getting started

### Python environment

Open a notebook in Jupyter Notebook, JupyterLab, or Google Colab. Install the libraries used across the notebooks:

```bash
pip install numpy pandas scipy matplotlib seaborn plotly bokeh
```

### SQL environment

Use MySQL or a compatible SQL environment. Create/load the required schema before running queries. Keep `Schema.png` available to check relationships and join paths.

## Action | Next steps to turn practice into stronger portfolio evidence

- **Verify:** Re-run queries and test NULL values, duplicate records, edge cases, and join cardinality.
- **Explain:** Add a brief interpretation to statistical outputs and charts; distinguish a calculated value from the conclusion it supports.
- **Extend:** Convert query exercises into clearly stated analytical questions, such as customer rental frequency, category-level demand, and store revenue.
- **Polish:** Use descriptive chart titles, axis labels, units, legends, and concise insight statements.
- **Demonstrate end-to-end work:** Build a separate project with a real dataset, business problem, data preparation, analysis, validation, findings, and recommendations.

## Reproducibility and limitations

- The SQL PDFs are separate source documents; their precise question lists and page contents should be read in the PDFs.
- The Python Basics PDF and certificate are linked as source documents; exact details remain in the files.
- Randomly generated notebook data can produce different values on different runs.
- Results can vary with Python/library versions and SQL dialect.
- Coursework examples should be reviewed and tested before reuse in a production setting.
- Original coursework files are unchanged. This README is an explanatory index only.

## Author

**Raj Kishore Agrawal** · [GitHub profile](https://github.com/rraj12345)
