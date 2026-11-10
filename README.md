# PW Skills | Data Analytics Coursework & Practice Portfolio

A structured archive of data analytics coursework completed during PW Skills training. This repository brings together SQL exercises, relational database references, Python and NumPy practice, statistical analysis, visualization notebooks, course PDFs, and a completion certificate.

> **Scope:** This is a learning and coursework repository. It demonstrates practice across core analytics topics; it is not presented as a production application or a measured client/business project.

## At a glance

| Asset type | Count | What it represents |
|---|---:|---|
| SQL files | 2 | SQL assignment work and a Maven Movies schema/setup file |
| Jupyter notebooks | 3 | NumPy, statistics, and visualization exercises |
| PDF documents | 4 | SQL coursework, Python basics, and course certificate |
| Schema image | 1 | Relational database structure reference |
| **Learning files indexed** | **10** | **All repository learning assets listed below** |

**Main learning areas:** SQL and relational databases • Python and NumPy • Statistics • Data visualization.

## Why this repository exists

Coursework is often scattered across scripts, notebooks, PDFs, and diagrams. Without context, a reviewer has to open each file to understand what it teaches, how it connects to other materials, and where to begin. This README acts as a guided index: it explains the purpose, topics, practical use, and limitations of every file.

## Repository contents — detailed file guide

### 1. SQL and relational database practice

#### [Mavenmovies.sql](Mavenmovies.sql)

**Purpose:** Intended SQL setup/schema resource for the Maven Movies (Sakila-style film-rental) database exercises.

**How it fits into the learning path:** A relational schema is the foundation for understanding entities, primary keys, foreign keys, and the joins used in the SQL assignment. The related exercises refer to entities such as actors, films, categories, customers, inventory, rentals, payments, staff, and stores.

**How to use it:** Before attempting the Maven Movies queries, use a valid copy of the schema to create the database and tables in MySQL Workbench or another compatible MySQL environment. Then inspect the relationships and test each query against the actual table structure.

**Repository note:** The current tracked file appears to be empty (zero text returned by the repository file reader). Therefore, it is listed for completeness, but it currently does not provide executable schema statements. The README does not claim otherwise. Add the original SQL setup script if you want this file to be runnable.

#### [sql_assignment.sql](sql_assignment.sql)

**Purpose:** Main SQL practice file containing written answers and query examples from the coursework.

**What it covers:**

- **DDL and table design:** Creating tables and defining columns, data types, primary keys, and constraints.
- **Constraints and integrity:** PRIMARY KEY, FOREIGN KEY, UNIQUE, CHECK, NOT NULL, and DEFAULT; adding and dropping constraints with ALTER TABLE.
- **Retrieval and filtering:** SELECT, DISTINCT, WHERE, LIKE, IN, BETWEEN, and LIMIT.
- **Joins:** Combining student/class, order/product/customer, and Maven Movies tables using join conditions.
- **Aggregation:** COUNT, AVG, SUM, grouping records, and summarizing rentals and revenue.
- **Maven Movies/Sakila analysis:** Identifying primary and foreign keys, retrieving actors and customers, filtering films, and exploring rentals, categories, and store revenue.
- **Further SQL concepts represented in the assignment:** Window functions, normalization concepts, and common table expressions (CTEs).

**How to use it:** Read one question at a time, predict the expected result, execute the query, and verify the output. For join questions, check whether the join key is correct and whether the result duplicates rows. For aggregate questions, verify the grouping level before trusting the total.

**Learning outcome:** Practice translating a business-style question into SQL, retrieving records, combining related tables, and summarizing data.

#### [PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf)

**Purpose:** PDF-based SQL assignment/reference supplied with the coursework.

**How to use it:** Treat the PDF as the assignment prompt and the SQL script as a place to review or practice query solutions. Read the question wording carefully, identify the required output, map the relevant tables and columns, and then write and test the query.

**Important distinction:** This is a separate file from SQL Assignment.pdf; both are retained in the repository and should not be treated as duplicates without comparing their contents.

#### [SQL Assignment.pdf](SQL%20Assignment.pdf)

**Purpose:** A second SQL assignment document retained separately from PW_SQL_Assignment.pdf.

**How to use it:** Open the PDF to review its original questions and instructions. Attempt each problem independently before consulting the SQL script or other notes. Use it as an additional practice/reference source rather than assuming it contains the same questions as the other PDF.

**Repository note:** The current tracked file appears empty to the repository file reader. It is linked here so the inventory is complete, but it may need to be re-uploaded if it is also blank when opened on GitHub.

#### [Schema.png](Schema.png)

**Purpose:** Visual reference for the Maven Movies/Sakila-style relational database.

**What it helps explain:** A schema/ER diagram makes it easier to see which tables represent entities, which columns act as keys, and how tables connect. This is particularly useful when a question requires data from multiple tables.

**How to use it:**

1. Locate the table that contains the information requested by the question.
2. Identify its primary key and the foreign key in the related table.
3. Trace the relationship path before writing the JOIN.
4. Check whether the relationship is one-to-one, one-to-many, or many-to-many.
5. Compare the query output row count with the expected level of detail.

**Learning outcome:** Better understanding of relational modeling and more reliable multi-table SQL queries.

### 2. Python and numerical computing

#### [Python Basics.pdf](Python%20Basics.pdf)

**Purpose:** Course reference material for learning or revising Python fundamentals.

**How it supports the other files:** Python fundamentals provide the programming foundation for the NumPy, statistics, and visualization notebooks. Concepts such as variables, data types, operators, conditions, loops, functions, and collections are commonly needed when completing these exercises.

**How to use it:** Keep the PDF as a reference while running the notebooks. When a notebook cell uses a Python construct you do not recognize, revisit the relevant concept, then reproduce the example with a small input of your own.

**Note:** The PDF is the source of truth for its exact chapter list and wording; this README does not invent page-level contents.

#### [Numpy Assignment.ipynb](Numpy%20Assignment.ipynb)

**Purpose:** Hands-on notebook for practicing NumPy arrays and numerical operations. It contains a large sequence of question-led exercises (206 notebook cells in the current file).

**Topics represented in the exercises:**

- **Array creation and data types:** Integer, floating-point, and complex arrays; checking dtype; converting between data types.
- **Array attributes:** Shape, size, number of dimensions, item size, total memory size, and strides.
- **Creating numeric sequences and matrices:** zeros, ones, arange, linspace, logarithmic sequences, and identity matrices.
- **Array conversion and memory behaviour:** Converting lists to arrays, understanding views and copies, and checking whether changes affect the original array.
- **Combining arrays:** Concatenation, horizontal/vertical stacking, splitting, insertion, and deletion.
- **Indexing and filtering:** Positive/negative indexing, multidimensional indexing, slicing, boolean masks, and selecting values using index arrays.
- **Reshaping and flattening:** Changing array dimensions and converting multidimensional arrays into one-dimensional arrays.
- **Vectorized calculations:** Element-wise addition, subtraction, multiplication, division, and exponentiation.
- **String arrays:** Searching for substrings, extracting or replacing text, concatenating strings, and measuring string lengths.
- **Statistical and mathematical operations:** Mean, variance, standard deviation, percentiles, correlation, sorting, and matrix multiplication.

**How to use it:** Open the notebook in Jupyter or Google Colab and run cells in order. Read the question before running the solution, try to solve it independently, and test the function with a different array. Pay particular attention to array shape compatibility when combining arrays or performing element-wise operations.

**Learning outcome:** Build confidence in efficient array-based computation and data manipulation, which are useful foundations for data cleaning and analysis.

### 3. Statistics and analytical reasoning

#### [Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb)

**Purpose:** Notebook of Python-based statistical exercises using generated data and example datasets.

**Libraries used in the notebook:** NumPy, Pandas, SciPy statistics, Matplotlib, Seaborn, Python's built-in statistics module, and supporting Python utilities.

**Topics represented:**

- **Descriptive statistics:** Mean, median, mode, weighted mean, geometric mean, harmonic mean, and trimmed mean.
- **Spread and variability:** Range, variance, standard deviation, interquartile range (IQR), quartile deviation, coefficient of variation, mean absolute deviation, and coefficient of dispersion.
- **Distribution analysis:** Frequency distributions, Gaussian/normal curves, kernel density estimates (KDE), and distribution visualizations.
- **Probability concepts:** Discrete random variables, expected value, variance, random sampling, and examples involving binomial, Poisson, normal, and exponential distributions.
- **Relationships between variables:** Covariance, Pearson correlation, skewness, and scatter-plot interpretation using the Seaborn tips dataset.
- **Inferential statistics and hypothesis testing:** Exercises involving t-statistics and p-values, including examples framed around website conversion, click-through rates, clinical/trial comparisons, education outcomes, salary comparisons, product quality, and customer satisfaction.
- **Before/after and group comparisons:** Exercises that ask whether observed differences are statistically meaningful.

**How to use it:** First identify the variable and the question being asked. Choose a suitable statistical measure, calculate it, and explain what it means in context. For hypothesis-testing exercises, state the null and alternative hypotheses, identify the test assumptions, interpret the p-value against a chosen significance level, and avoid treating statistical significance as proof of practical importance.

**Important caution:** Some notebook sections generate random data, so numerical outputs can change between runs unless a random seed is fixed. Statistical conclusions should be interpreted in light of sample size, assumptions, and data quality.

**Learning outcome:** Develop the ability to summarize data, understand distributions, measure relationships, and interpret basic statistical tests.

### 4. Data visualization and storytelling

#### [Visualization.ipynb](Visualization.ipynb)

**Purpose:** Practical notebook demonstrating data visualization with four Python visualization libraries. The notebook currently contains 42 cells.

**Library-by-library coverage:**

- **Matplotlib:** Scatter plots to examine relationships, line plots to show trends, bar charts to compare categories, and histograms to inspect distributions.
- **Seaborn:** Scatter plots, distribution plots, categorical bar charts, box plots, and heatmaps for correlation patterns.
- **Plotly:** Interactive/advanced visualization exercises, including 3D scatter plots, violin plots, heatmaps, 3D surface plots, and bubble charts.
- **Bokeh:** Interactive plotting exercises such as sine-wave line charts, scatter plots with marker attributes, and categorical bar charts.

**How to use it:** Run each section and observe how the same data can be communicated in different ways. Select the chart based on the analytical purpose: comparison, trend, distribution, relationship, composition, or multidimensional exploration. Add clear titles, axis labels, units, legends, and a short written takeaway when adapting a chart for a report.

**Learning outcome:** Practice selecting and building charts and communicating patterns visually, rather than relying only on tables of numbers.

### 5. Course credential

#### [PwSkills Certification.pdf](PwSkills%20Certification.pdf)

**Purpose:** Certificate document associated with the PW Skills learning program.

**How to use it:** Refer to the original PDF when confirming the exact certificate title, issuer, completion date, or other credential details. It can serve as supporting evidence of course completion alongside the practical exercises in this repository.

**Important:** The certificate is a credential artifact; it is not a substitute for demonstrating the skills through executable work or project outcomes.

## Suggested learning sequence

~~~text
Python Basics.pdf ──────────────────────┐
                                       ↓
Schema.png → Maven Movies SQL → SQL assignment
                                       ↓
                         NumPy Assignment
                                       ↓
                     Statistics Assignment
                                       ↓
                      Visualization Notebook
                                       ↓
                  Independent analytics project
~~~

1. **Start with foundations:** Review Python basics and relational database concepts.
2. **Understand the data model:** Study Schema.png and the database setup requirements.
3. **Practice SQL:** Work through DDL, constraints, filtering, joins, aggregation, and analytical queries.
4. **Practice numerical computing:** Complete the NumPy exercises and test array operations with new inputs.
5. **Build statistical thinking:** Select appropriate measures and explain their meaning and assumptions.
6. **Communicate findings:** Use visualizations to answer a clear question and write a concise insight.
7. **Apply independently:** Use a new dataset to build a separate project with a defined problem, reproducible steps, validated results, and recommended actions.

## Skills represented

| Area | Practice represented in this repository |
|---|---|
| SQL | DDL, constraints, filtering, joins, aggregation, relational keys, CTE/window-function concepts |
| Python | Fundamentals used across notebook exercises |
| NumPy | Arrays, data types, indexing, reshaping, vectorized operations, numerical summaries |
| Statistics | Descriptive measures, distributions, correlation, probability, hypothesis testing |
| Visualization | Matplotlib, Seaborn, Plotly, Bokeh |
| Analytical communication | Choosing suitable methods and explaining results |

## Quantitative and qualitative evidence

**Quantitative inventory:** 10 learning assets are indexed in this README: 2 SQL files, 3 notebooks, 4 PDFs, and 1 schema image. The NumPy notebook contains 206 cells, the statistics notebook 87 cells, and the visualization notebook 42 cells (notebook cell counts include code/markdown cells and are not a measure of completed skill proficiency).

**Qualitative evidence:** The coursework provides examples of working with relational data, writing SQL queries, manipulating arrays, calculating statistical measures, exploring probability and hypothesis tests, and creating visualizations with multiple libraries.

**Measurement boundary:** These are repository and coursework measures, not business KPIs. No revenue growth, cost reduction, time savings, model accuracy, production deployment, or client impact is claimed because those outcomes are not measured by these files.

## Tools and environment

- **Database:** MySQL / MySQL Workbench (for the Maven Movies-style SQL exercises)
- **Language:** Python 3
- **Notebook environments:** Jupyter Notebook, JupyterLab, Google Colab
- **Data and statistics:** NumPy, Pandas, SciPy, Python statistics
- **Visualization:** Matplotlib, Seaborn, Plotly, Bokeh

### Python setup

Install the commonly used notebook libraries:

~~~bash
pip install numpy pandas scipy matplotlib seaborn plotly bokeh
~~~

Then open the relevant .ipynb file in Jupyter or upload it to Google Colab.

## Recommended next actions

- Restore the missing/empty SQL assets if the original schema and second SQL PDF are available.
- Execute SQL statements against the intended database and verify table names, join keys, result counts, and edge cases.
- Re-run notebook cells from a clean kernel and resolve any version-related warnings or deprecated APIs.
- Add short interpretations below important statistical outputs and visualizations.
- Build a separate end-to-end portfolio project that demonstrates the complete cycle: **Problem → Data → Approach → Validation → Result → Business Action**.

## Repository limitations and accuracy notes

- Mavenmovies.sql and SQL Assignment.pdf currently appear empty when read from the repository; their descriptions above explicitly reflect that limitation.
- The exact page-level contents of the PDF resources should be checked in the original documents.
- Randomly generated datasets may produce different results on different runs.
- Package versions and SQL dialects can affect compatibility.
- Coursework examples should be reviewed and tested before reuse in a production environment.
- This README documents the existing assets; it does not claim that missing or empty files contain working code.

## Author

**Raj Kishore Agrawal**  
[GitHub profile](https://github.com/rraj12345)
