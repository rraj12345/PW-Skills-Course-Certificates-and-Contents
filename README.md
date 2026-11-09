# PW Skills – Data Analytics Learning Portfolio

A collection of coursework, practice assignments, and learning resources completed during data analytics training with PW Skills. This repository brings together SQL, Python, statistics, and data visualization exercises.

> **Repository purpose:** A learning and practice portfolio. These files document coursework and hands-on exercises; they are not presented as one end-to-end business project.

## Repository contents

| Area | Files | What you will find |
|---|---:|---|
| SQL | 5 | Sakila/Maven Movies database, SQL scripts, assignment PDFs, and schema reference |
| Python & data analysis | 4 | NumPy, statistics, data visualization notebooks, and Python reference material |
| Certification | 1 | PW Skills course certificate |

## File-by-file guide

### 1. SQL and database learning

#### [Mavenmovies.sql](Mavenmovies.sql)
A MySQL database setup script based on the **Sakila sample database**, used in the Maven Movies learning exercises. It creates the `mavenmovies` schema and defines the relational database structure, including tables such as actors, films, customers, stores, rentals, payments, addresses, cities, countries, and categories. It also includes primary keys, foreign keys, indexes, and relationships between tables. Use it to understand how a multi-table relational database is structured before writing analytical queries.

#### [sql_assignment.sql](sql_assignment.sql)
A collection of SQL assignment answers and query exercises. It begins with table creation and data-integrity constraints (such as primary key, unique, check, not-null, and default constraints), then moves into joins between tables, aggregation, filtering, sorting, and querying the Maven Movies/Sakila schema. The script includes practice questions around actors, customers, films, rentals, inventory, payments, categories, and stores. It is useful for revising SQL syntax and practicing how to translate business-style questions into queries.

#### [PW_SQL_Assignment.pdf](PW_SQL_Assignment.pdf)
A PDF copy of SQL assignment material from the PW Skills coursework. It serves as the written assignment/reference counterpart to the SQL practice files and can be used to review the questions and compare them with the SQL exercises in this repository.

#### [SQL Assignment.pdf](SQL%20Assignment.pdf)
An additional SQL assignment/reference PDF. It is kept separately because it is a distinct course document from `PW_SQL_Assignment.pdf`. Refer to it for the written SQL exercises and course material associated with the database practice.

#### [Schema.png](Schema.png)
A visual database schema reference for the relational database exercises. It helps identify tables, key columns, and the relationships used when writing joins. Keep it open alongside `Mavenmovies.sql` and `sql_assignment.sql` when tracing how entities such as films, actors, customers, inventory, rentals, and payments connect.

### 2. Python, statistics, and visualization

#### [Numpy Assignment.ipynb](Numpy%20Assignment.ipynb)
A Jupyter Notebook containing question-based practice in **NumPy**. The exercises introduce array creation and data types (integer, float, and complex), type conversion, and array properties such as shape, size, and data type. The notebook continues with common array operations and manipulation tasks. It is suitable for practicing numerical data handling and understanding how NumPy arrays differ from standard Python lists.

#### [Statistics_Assignment_PwSkills.ipynb](Statistics_Assignment_PwSkills.ipynb)
A Jupyter Notebook focused on statistical concepts and their implementation in Python. It includes exercises on generating sample data and calculating measures such as mean, median, mode, weighted mean, and geometric mean, along with further statistical analysis tasks. The notebook uses libraries including NumPy, Pandas, SciPy, Matplotlib, and Seaborn. It provides practice connecting statistical definitions with calculations and Python code.

#### [Visualization.ipynb](Visualization.ipynb)
A Jupyter Notebook containing data visualization exercises, beginning with Matplotlib and chart creation (including scatter plots) and extending into visualization with Python plotting libraries. The exercises demonstrate how to represent relationships, distributions, and patterns in data visually. It is useful for practicing chart selection, plotting syntax, and communicating observations from datasets.

#### [Python Basics.pdf](Python%20Basics.pdf)
A PDF learning resource for Python fundamentals. It complements the Python notebooks by providing a reference for core language concepts before moving into numerical computing, statistics, and visualization.

### 3. Certificate

#### [PwSkills Certification.pdf](PwSkills%20Certification.pdf)
The PW Skills course certificate document associated with the learning material in this repository. It is included as supporting evidence of course completion; consult the PDF itself for the exact certificate details.

## Topics covered

- **SQL and relational databases:** Schema creation, primary and foreign keys, constraints, joins, filtering, aggregation, and analytical queries.
- **Python fundamentals:** Core Python concepts and notebook-based programming practice.
- **NumPy:** Arrays, data types, array attributes, conversion, and numerical operations.
- **Statistics:** Measures of central tendency and other statistical exercises using Python libraries.
- **Data visualization:** Creating plots to explore and communicate patterns in data.

## Tools and libraries

- MySQL / SQL
- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy

## How to use

1. Browse the SQL scripts and PDFs to review database concepts and assignment questions.
2. Open the `.ipynb` notebooks in Jupyter Notebook, JupyterLab, or Google Colab.
3. Install the libraries required by the notebooks before running the cells. A typical starting point is:

   ```bash
   pip install numpy pandas matplotlib seaborn scipy
   ```

4. For the Maven Movies SQL exercises, create or load the required schema in a compatible MySQL environment. Use `Schema.png` to understand table relationships before running joins.

## Notes

- This repository is an archive of learning exercises, course references, and certification material.
- PDF descriptions above identify the documents by their repository role; consult each PDF for its exact question-by-question contents.
- Notebook outputs and library behavior may vary with Python and package versions.
- The original assignment files are preserved. This README is documentation only; it does not change the contents of the SQL scripts, notebooks, PDFs, or image.

## Author

**Raj Kishore Agrawal**

[GitHub profile](https://github.com/rraj12345)
