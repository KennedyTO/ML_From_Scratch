from pathlib import Path
import pandas as pd
from sklearn.model_selection import train_test_split
from Code_Part2.DecisionTree import DecisionTree

# Build a path relative to the repo root (parent of Code_Part2)
DATA_PATH = Path(__file__).resolve().parents[1] / "data" / "NFCS"/ "NFCS.csv"

# Load dataset (local file; no sklearn.datasets needed)
df = pd.read_csv(DATA_PATH)

# Basic cleaning examples
# 1) Standardize column names
df.columns = df.columns.str.strip().str.lower()

# 2) Fix dtypes (example: parse dates if present)
# df["date_col"] = pd.to_datetime(df["date_col"], errors="coerce")

# 3) Handle missing values (simple, in-place)

# 4) Drop duplicates (optional)
# df = df.drop_duplicates()

# Split (adjust target column name)
# y = df["target"]
# X = df.drop(columns=["target"])
# X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42, stratify=y)

# Example usage (adjust to your DecisionTree API)
# tree = DecisionTree(max_depth=5)
# tree.fit(X_train, y_train)
# preds = tree.predict(X_test)




