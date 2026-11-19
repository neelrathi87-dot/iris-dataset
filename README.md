# Iris Dataset

The classic **Iris Flower Dataset** by Ronald Fisher (1936).

## 📄 File
- [`iris.csv`](iris.csv) — 150 rows × 5 columns

## 📊 Columns

| Column | Description |
|---|---|
| `sepal length (cm)` | Sepal length in centimetres |
| `sepal width (cm)` | Sepal width in centimetres |
| `petal length (cm)` | Petal length in centimetres |
| `petal width (cm)` | Petal width in centimetres |
| `species` | Flower species: setosa, versicolor, virginica |

## 🔗 Usage in Python

```python
import pandas as pd
df = pd.read_csv("iris.csv")
print(df.head())
```

## 📈 Dataset Info
- **150 rows** (50 per species)
- **3 classes:** Iris-setosa, Iris-versicolor, Iris-virginica
- **Source:** UCI Machine Learning Repository
