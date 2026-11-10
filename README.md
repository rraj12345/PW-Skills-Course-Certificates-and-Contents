# PW Skills | Data Analytics Learning Portfolio

A curated archive of coursework and practical exercises completed during PW Skills data analytics training. The repository brings SQL, Python, statistics, and visualization practice into one place.

## Repository at a glance

| Area | Files | Main content |
|---|---:|---|
| SQL and relational databases | 5 | Database schema, SQL practice, assignment references |
| Python and analytics | 4 | Python reference, NumPy, statistics, visualization |
| Certification | 1 | Course certificate |
| **Total** | **10** | **Learning resources and practice artifacts** |

## Problem

Coursework is often spread across separate scripts, notebooks, PDFs, and reference images. Without a clear index, it takes time for a learner or reviewer to understand what each file contains, how the materials connect, and where to begin.

## Solution

This repository consolidates those materials and documents each artifact. It is a learning portfolio, not a production analytics solution or a single end-to-end business case.

## File guide

### SQL and database learning

- **[Mavenmovies.sql](Mavenmovies.sql)** — MySQL setup script based on the Sakila sample database. It creates the `mavenmovies` schema and relational tables for films, actors, customers, stores, rentals, payments, addresses, locations, and categories, with keys, indexes, and relationships.
- **[sql_assignment.sql](sql_assignment.sql)** — SQL practice answers. Topics include table creation, constraints, primary and foreign keys, filtering, pattern matching, joins, aggregation, grouping, window functions, normalization, and CTEs. Example questions analyze customers, films, rentals, categories, and store revenue.
- **[PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf)** — PDF assignment/reference material for the SQL coursework. Use it to review the written exercises alongside the SQL scripts.
- **[SQL Assignment.pdf](SQL%20Assignment.pdf)** — A separate SQL assignment/reference PDF retained as a distinct course resource.
- **[Schema.png](Schema.png)** — Visual database schema reference showing tables and relationships; useful when planning joins across the Maven Movies/Sakila database.

### Python, statistics, and visualization

- **[Python Basics.pdf](Python%20Basics.pdf)** — Python fundamentals reference material that supports the notebook exercises.
- **[Numpy Assignment.ipynb](Numpy%20Assignment.ipynb)** — Question-based NumPy practice covering array creation, integer/float/complex data types, type conversion, array attributes, dimensions, strides, zeros/ones/identity arrays, ranges, concatenation, stacking, indexing, slicing, reshaping, arithmetic, string operations, and summary calculations.
- **[Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb)** — Python-based statistics exercises. The notebook uses NumPy, Pandas, SciPy, Matplotlib, Seaborn, and Python's statistics module for descriptive measures and statistical problem-solving, including central tendency and dispersion.
- **[Visualization.ipynb](Visualization.ipynb)** — Visualization assignments organized around Matplotlib, Seaborn, Plotly, and Bokeh. Exercises cover common chart forms such as scatter, line, and bar plots and practice presenting data visually.

### Certification

- **[PwSkills Certification.pdf](PwSkills%20Certification.pdf)** — PW Skills course certificate. Refer to the PDF for the exact credential details.

## Approach

1. **Understand the data model:** Start with `Mavenmovies.sql` and `Schema.png` to understand entities, keys, and relationships.
2. **Practice SQL:** Use `sql_assignment.sql` and the assignment PDFs to work through data retrieval, joins, aggregation, and analytical queries.
3. **Build Python foundations:** Review `Python Basics.pdf`, then work through the NumPy notebook.
4. **Apply statistical thinking:** Use the statistics notebook to calculate and interpret descriptive measures and statistical results.
5. **Communicate with charts:** Explore the visualization notebook and compare chart types for different analytical questions.

## Results and learning outcomes

The repository provides a set of reusable learning artifacts across **4 subject areas**: SQL, Python/NumPy, statistics, and data visualization. It demonstrates practice with relational data structures, analytical SQL patterns, numerical arrays, statistical calculations, and visual communication.

These are coursework outputs. No business KPI improvement, production deployment, or quantified commercial impact is claimed.

## Tools

MySQL | Python 3 | NumPy | Pandas | SciPy | Matplotlib | Seaborn | Plotly | Bokeh | Jupyter Notebook / Google Colab

## Run the notebooks

Open the `.ipynb` files in Jupyter Notebook, JupyterLab, or Google Colab. A starting set of dependencies is:

```bash
pip install numpy pandas scipy matplotlib seaborn plotly bokeh
```

For SQL practice, use a compatible MySQL environment and load the required schema before running queries.

## Next actions

- Re-run selected exercises with fresh test cases and verify the outputs.
- Extend SQL questions with business-style metrics such as rental frequency, customer value, and category performance.
- Add concise interpretations below statistical outputs and visualizations.
- Keep future projects in separate folders or repositories with a clear problem statement, methodology, and findings.

## Repository notes

- The PDFs are described by their role in the course; consult each document for its exact page-by-page contents.
- Results in notebooks may depend on package versions and random data generation.
- Original coursework files are retained. This README documents them; it does not change their contents.

## Author

**Raj Kishore Agrawal** · [GitHub](https://github.com/rraj12345)
