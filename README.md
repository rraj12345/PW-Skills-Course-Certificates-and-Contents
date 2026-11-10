# PW Skills | Data Analytics Learning Portfolio

A documented archive of coursework and hands-on exercises completed during PW Skills data analytics training. It brings together relational database work, SQL querying, Python-based numerical analysis, statistics, and data visualization.

> **Positioning:** This repository demonstrates learning and practice through course artifacts. It is not a production application, a client engagement, or a single end-to-end business analytics project.

## Repository scorecard

| Inventory metric | Count | Coverage |
|---|---:|---:|
| SQL scripts | 2 | Database setup + query practice |
| Jupyter notebooks | 3 | NumPy + statistics + visualization |
| PDF documents | 4 | SQL assignments + Python basics + certificate |
| Schema image | 1 | Relational data model reference |
| **Total documented files** | **10** | **10 / 10 linked below** |
| **Learning domains** | **4** | SQL, Python/NumPy, statistics, visualization |

## Problem

Course materials often accumulate as separate SQL files, notebooks, PDFs, and diagrams. Without a clear index, a learner or reviewer must open each item to discover its purpose, prerequisites, and relationship to the other exercises. This makes the collection harder to navigate, revisit, and evaluate.

## Solution

This repository provides a single entry point: a file-by-file guide, an explanation of the skills practiced, and a suggested learning sequence. The materials are connected into a coherent path from understanding relational data to querying, numerical analysis, statistical reasoning, and visual communication.

## Repository content | File-by-file documentation

### SQL and relational database foundations

#### [Mavenmovies.sql](Mavenmovies.sql)
**Role:** MySQL database schema and setup for Maven Movies/Sakila-style exercises.

**What is inside:** Creates the `mavenmovies` schema and defines relational tables for actors, actor awards, addresses, categories, cities, countries, customers, films, and other film-rental entities. The script specifies column types, primary keys, foreign-key relationships, indexes, and constraints.

**How to use it:** Load or inspect the schema before attempting the related SQL exercises. Study the keys and table dependencies to understand how film, customer, inventory, rental, and payment data relate.

#### [sql_assignment.sql](sql_assignment.sql)
**Role:** Question-led SQL practice, from database fundamentals to analytical querying.

**What is inside:** Table creation and constraints (primary key, unique, check, not-null, default); primary/foreign-key identification; SELECT and DISTINCT; WHERE filters; LIKE, IN, BETWEEN, and LIMIT; joins; aggregate functions and GROUP BY; and sections on window functions, normalization (1NF, 2NF, 3NF), and CTEs. The Maven Movies/Sakila exercises ask questions about actors, customers, films, rentals, categories, and store revenue.

**How to use it:** Work through the questions, run them against the matching schema, and validate results. Treat the script as a practice submission, not as a guarantee that every query is production-ready.

#### [PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf)
**Role:** Written SQL assignment/reference material from the course.

**What is inside:** A PDF resource associated with the SQL coursework. Its exact questions and page-level contents are available in the document itself.

**How to use it:** Read the assignment prompt, attempt the question, and compare your approach with the relevant SQL practice.

#### [SQL Assignment.pdf](SQL%20Assignment.pdf)
**Role:** Additional SQL assignment/reference document.

**What is inside:** A separate SQL coursework PDF, retained independently from `PW_SQL_Assignment.pdf`.

**How to use it:** Open the PDF for the precise question list and use it as a second practice/reference source.

#### [Schema.png](Schema.png)
**Role:** Visual companion to the relational SQL schema.

**What is inside:** A database schema diagram showing the tables and their relationships.

**How to use it:** Identify key columns and trace join paths before writing multi-table queries. Use it with `Mavenmovies.sql` and `sql_assignment.sql`.

### Python, statistics, and data visualization

#### [Python Basics.pdf](Python%20Basics.pdf)
**Role:** Python fundamentals reference.

**What is inside:** A PDF learning resource covering Python basics. For exact chapter and topic details, refer to the PDF itself.

**How to use it:** Use it as a reference while working through the Python notebooks or revisiting language fundamentals.

#### [Numpy Assignment.ipynb](Numpy%20Assignment.ipynb)
**Role:** Hands-on practice with NumPy arrays and numerical operations.

**What is inside:** Exercises on array creation and integer/float/complex data types; type conversion; shape, size, dimensions, item size, and strides; zeros, ones, ranges, and identity matrices; list conversion and views; concatenation and stacking; indexing, boolean indexing, and slicing across dimensions; reshaping and flattening; insertion and deletion; element-wise arithmetic; string-array tasks; and summary calculations such as mean, percentiles, and correlation.

**How to use it:** Run the notebook sequentially and experiment with array shapes and input values to understand vectorized data manipulation.

#### [Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb)
**Role:** Apply descriptive and other statistical concepts using Python.

**What is inside:** Uses NumPy, Pandas, SciPy statistics, Matplotlib, Seaborn, and Python's `statistics` module. The exercises include generated sample data and calculations such as mean, median, mode, weighted mean, and geometric mean, followed by further statistical problem-solving.

**How to use it:** Calculate the measures, compare what they describe, and explain the meaning and limitations of the results. Check the assumptions behind any inferential test before interpreting it.

#### [Visualization.ipynb](Visualization.ipynb)
**Role:** Practice data visualization with multiple Python libraries.

**What is inside:** Assignment sections for Matplotlib, Seaborn, Plotly, and Bokeh. The notebook includes common chart tasks such as scatter, line, and bar plots.

**How to use it:** Recreate the plots, compare library syntax, and choose a chart based on the question being answered rather than appearance alone.

### Certification

#### [PwSkills Certification.pdf](PwSkills%20Certification.pdf)
**Role:** Course completion credential.

**What is inside:** The PW Skills certificate document. The PDF is the authoritative source for the exact credential title, dates, and issuer details.

**How to use it:** Refer to the document when verifying course credential information.

## Approach | Learning workflow

```text
Relational schema + ER reference
            ↓
SQL fundamentals → joins → analytical SQL
            ↓
Python fundamentals → NumPy arrays
            ↓
Descriptive/statistical analysis
            ↓
Charts and visual communication
            ↓
Independent end-to-end analytics project
```

1. **Understand the model:** Inspect the schema and identify entities, keys, and relationships.
2. **Query systematically:** Progress from constraints and filtering to joins, aggregation, window functions, normalization, and CTEs.
3. **Prepare analytical data:** Review Python basics and practice array operations with NumPy.
4. **Analyze statistically:** Calculate descriptive measures and interpret what they reveal; validate assumptions for tests.
5. **Communicate visually:** Build charts that answer a specific question and write a concise takeaway.
6. **Transfer the learning:** Apply these skills to a new dataset and document the problem, method, checks, results, and recommended action.

## Results | Quantitative and qualitative evidence

### Quantitative repository measures

| Measure | Result |
|---|---:|
| Files described and linked | **10 / 10 (100%)** |
| SQL scripts | **2** |
| Python notebooks | **3** |
| PDF resources | **4** |
| Schema images | **1** |
| Distinct learning domains | **4** |

### Qualitative skills represented

- **Data modeling:** Reading a relational schema and identifying key relationships.
- **SQL analysis:** Constraints, filtering, joins, aggregation, window functions, normalization, and CTEs.
- **Numerical programming:** NumPy arrays, dimensions, indexing, reshaping, and vectorized operations.
- **Statistical reasoning:** Descriptive measures and statistical exercises in Python.
- **Data communication:** Building charts with Matplotlib, Seaborn, Plotly, and Bokeh.

**Honest measurement boundary:** The quantitative results above describe the repository inventory and documentation coverage. They are not business KPIs. No revenue uplift, efficiency gain, model accuracy, production usage, or client impact is claimed because those outcomes have not been measured in this coursework archive.

## Technology stack

| Layer | Technologies |
|---|---|
| Database | MySQL, SQL |
| Programming | Python 3 |
| Data and statistics | NumPy, Pandas, SciPy, `statistics` |
| Visualization | Matplotlib, Seaborn, Plotly, Bokeh |
| Working environment | Jupyter Notebook, JupyterLab, Google Colab |

## Getting started

### 1. Open the notebooks

Use Jupyter Notebook, JupyterLab, or Google Colab to open the `.ipynb` files.

### 2. Install Python dependencies

```bash
pip install numpy pandas scipy matplotlib seaborn plotly bokeh
```

### 3. Prepare the SQL environment

Use MySQL or a compatible environment. Load/create the Maven Movies/Sakila-style schema before executing the queries. Keep `Schema.png` open to verify table relationships and join paths.

## Action | Recommended next steps

- **Validate:** Execute the SQL questions and test NULLs, duplicates, boundary values, and join cardinality.
- **Interpret:** Explain what each important statistical result means instead of listing numbers alone.
- **Improve:** Add titles, units, labels, legends, and insight statements to charts.
- **Extend:** Create new business questions around rental frequency, film/category demand, customer activity, and store revenue.
- **Demonstrate:** Build a separate end-to-end project with a defined business problem, documented assumptions, data preparation, analysis, validation, findings, and actionable recommendations.

## Reproducibility and limitations

- The SQL assignment PDFs are distinct documents; consult each PDF for its exact questions and instructions.
- The Python Basics PDF and certificate are linked as source documents; exact chapter and credential details remain in the files.
- Randomly generated notebook data may produce different outputs on each run.
- SQL syntax and Python package behavior may vary across engine and library versions.
- Coursework code should be reviewed and tested before any production reuse.
- Original coursework files are unchanged. This README provides navigation and context only.

## Author

**Raj Kishore Agrawal**  
[GitHub profile](https://github.com/rraj12345)
