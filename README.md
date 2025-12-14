# PySpark Examples (Minimal)

Small collection of PySpark notebooks for learning DataFrames and RDDs.

Prerequisites
- Python 3.8+
- Java 8 or 11
- Install `pyspark` and `jupyterlab`

Quick setup (Windows)

```powershell
python -m venv .venv
.venv\Scripts\activate
pip install --upgrade pip
pip install pyspark jupyterlab
```

Run notebooks

```powershell
jupyter lab
```

Run a script with Spark

```powershell
spark-submit my_script.py
```

Files
- `DataFrames_Basics.ipynb` — basic DataFrame examples
- `DataFrames_Medium.ipynb` — intermediate examples
- `DataFrames_Complex.ipynb` — advanced examples
- `Rdd.ipynb` — RDD examples

Add data
- Put CSV/Parquet files in a `data/` folder and read with `spark.read`.

That's it — simple and ready. Update this file if you want a `requirements.txt` or example data.