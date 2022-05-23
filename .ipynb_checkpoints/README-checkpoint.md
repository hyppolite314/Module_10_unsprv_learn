# Data Clustering and K-Means Models (Mod 10)

Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. Results are plotted. The CSV file contains the price change data of cryptocurrencies in different periods.

---

## Technologies

Required programs, libraries, systems, and overall dependencies:

Python (version 3.0 or later)
<br>
`Pathlib`
<br>
`pandas`
<br>
`%matplotlib`
<br>
`hvplot.pandas`
<br>
`from sklearn.cluster import KMeans`
<br>
`from sklearn.decomposition import PCA`
<br>
`from sklearn.preprocessing import StandardScaler`

---

## Usage / Sample

Creating Elbow Curve:

```python
# Create a dictionary with the data to plot the Elbow curve
elbow_data = {
    "kval":k,
    "inertia":inertia_val
}

# Create a DataFrame with the data to plot the Elbow curve
df_elbow_data = pd.DataFrame(elbow_data)

display(df_elbow_data)
```
---

## Contributors

Reginald Hyppolite
https://www.linkedin.com/in/reginald-hyppolite-nyc/

BIG THANKS to all the great TAs and Professor Vinicio DeSola

---

## License

N/A -- Free open.ware for a better world.