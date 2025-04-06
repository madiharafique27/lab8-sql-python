# Lab 8 – SQL and Python: Data Preprocessing with Pandas

## Short Description  
This project demonstrates how to connect to a SQL database using Python and perform basic to advanced SQL queries using pandas and SQLAlchemy. It includes query execution, reading results into DataFrames, and applying filtering techniques in Python.

---

## Getting Started

### Prerequisites
- Python 3.x  
- `pandas`  
- `SQLAlchemy`  
- `PyMySQL`  
- Access to a MySQL database (or local instance)

### Installing

Clone the repository and navigate into it:

```bash
git clone https://github.com/yourusername/lab8-sql-python.git
cd lab8-sql-python
```

Install required packages:

```bash
pip install pandas sqlalchemy pymysql
```

---

## Running the Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook Lab8.ipynb
```

Replace the placeholder database credentials and run the cells. Example:

```python
engine = create_engine('mysql+pymysql://yourusername:yourpassword@localhost/yourdatabase')
```

> **Note**: Ensure your MySQL server is running and accessible.

---

## Deployment

This notebook is meant to be run locally with access to a MySQL database. No deployment is needed.

---

## Author

Madiha Rafique 
GitHub: [@madiharafique27](https://github.com/madiharafique27)

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgements

- Professor Omar Al-Trad: *Data 1202: Data Analytics Tools*  
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- [SQLAlchemy Documentation](https://docs.sqlalchemy.org/)  
