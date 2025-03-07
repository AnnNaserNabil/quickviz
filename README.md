# 📊 fireviz - A Simple & Fast Data Visualization Library  

**fireviz** is a lightweight Python package for quick and insightful data visualizations. It allows you to generate various plots using **Matplotlib, Seaborn, Plotly, and NetworkX** with minimal effort.  



[![PyPI Downloads](https://static.pepy.tech/badge/fireviz)](https://pepy.tech/projects/fireviz)




## 🚀 Features  
✔ Supports multiple plot types: `scatter`, `bar`, `line`, `heatmap`, `pie`, `treemap`, `network`, `sankey`, and more!  
✔ Handles both **Pandas DataFrames and Series** automatically.  
✔ Built-in **Exploratory Data Analysis (EDA)** function.  
✔ Uses **Seaborn & Plotly** for professional-quality visuals.  
✔ Requires minimal configuration – just pass your data!  

---

## 📦 Installation  

```sh
pip install fireviz
```


---

## 🔥 Quick Start  

### 1️⃣ Import the package  
```python
import pandas as pd
import fireviz as fv
```

### 2️⃣ Load your dataset  
```python
df = pd.read_csv("data.csv")
```

### 3️⃣ Generate Quick Visualizations  

#### 📌 Scatter Plot  
```python
fv.plot(df, x="column1", y="column2", kind="scatter")
```

#### 📌 Histogram  
```python
fv.plot(df["column1"], kind="hist", bins=20)
```

#### 📌 Correlation Heatmap  
```python
fv.plot(df, kind="heatmap")
```

#### 📌 Treemap  
```python
fv.plot(df, x="category_column", y="value_column", kind="treemap")
```

---

## 🔍 Exploratory Data Analysis (EDA)  

The **`explore()`** function automatically generates visual summaries of your dataset.  
```python
fv.explore(df)
```
This will:  
✅ Print **dataset info, missing values, and statistics**  
✅ Plot **histograms** for numeric columns  
✅ Plot **count plots** for categorical columns  
✅ Generate a **correlation heatmap**  

---

## 📊 Supported Plot Types  

| Plot Type    | `kind` Parameter |
|-------------|----------------|
| Scatter Plot | `"scatter"` |
| Line Chart | `"line"` |
| Box Plot | `"box"` |
| Bar Chart | `"bar"` |
| Bubble Chart | `"bubble"` |
| Area Chart | `"area"` |
| Heatmap | `"heatmap"` |
| Pie Chart | `"pie"` |
| Donut Chart | `"donut"` |
| Treemap | `"treemap"` |
| Funnel Chart | `"funnel"` |
| Waterfall Chart | `"waterfall"` |
| Choropleth Map | `"choropleth"` |
| Radar Chart | `"radar"` |
| Network Graph | `"network"` |
| Sankey Diagram | `"sankey"` |
| Gantt Chart | `"gantt"` |
| Bullet Chart | `"bullet"` |
| Density Plot | `"density"` |
| Stacked Bar Chart | `"stacked_bar"` |

---

## 🛠 Requirements  
- Python 3.6+
- Pandas
- Matplotlib
- Seaborn
- Plotly
- NetworkX
- Squarify
- NumPy  

Install dependencies manually if needed:  
```sh
pip install pandas matplotlib seaborn plotly networkx squarify numpy
```

---

## 📄 License  
This project is licensed under the **MIT License**.

---

## 🤝 Contributing  
Feel free to open an issue or submit a pull request on [GitHub](https://github.com/AnnNaserNabil/quickviz).

---

## 💬 Questions & Feedback  
Got questions or feedback? Reach out to **ann.n.nabil@gmail.com*.

Happy Visualizing! 🎨📊🚀

---

Let me know if you want any modifications! 🚀
