# Amazon Music Clustering Project

## Project Overview

This project applies Machine Learning clustering techniques on an Amazon Music dataset to group similar songs based on their audio characteristics.

The clustering process helps identify patterns among songs using features such as:

- Danceability
- Energy
- Acousticness
- Tempo
- Valence

The main objective of this project is to analyze music trends and group tracks into meaningful clusters using the K-Means Clustering algorithm.

---

## Dataset Information

- Dataset Name: `single_genre_artists.csv`
- Total Records: 95,837 songs
- Total Features: 23 columns

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Technical Tags

`Machine Learning` `K-Means Clustering` `Python`
`Pandas` `Scikit-learn` `Data Visualization`
`PCA` `Data Science` `Clustering`
`Amazon Music Dataset`

---

## Project Workflow

### 1. Data Preprocessing

- Loaded dataset using Pandas
- Explored dataset structure
- Checked for missing values
- Selected important audio features
- Standardized features using StandardScaler

### 2. Feature Selection

The following features were used for clustering:

- danceability
- energy
- acousticness
- tempo
- valence

---

## K-Means Clustering

### Elbow Method

Used the Elbow Method to determine the optimal number of clusters.

### Model Training

Applied K-Means clustering with:

- Number of Clusters (K) = 4

Cluster labels were added to the original dataset.

---

## Model Evaluation

### Silhouette Score

The clustering quality was evaluated using the Silhouette Score.

Score Obtained:

```python
0.2183
```

---

## Data Visualization

The following visualizations were created:

- PCA Scatter Plot for cluster visualization
- Bar Charts for average feature comparison
- Heatmap for cluster feature analysis
- Distribution Plots for danceability comparison

---

## Project Results

The model successfully grouped songs into 4 different clusters based on musical characteristics.

Some observations:

- Certain clusters showed high danceability and energy.
- Some clusters contained more acoustic and slower songs.
- PCA visualization clearly displayed cluster separation.

---

## Files Included

| File Name | Description |
|---|---|
| `amazon_music_clustering.ipynb` | Main project notebook |
| `clustered_music_dataset.csv` | Final dataset with cluster labels |
| `README.md` | Project documentation |

---

## Output

Final dataset was exported successfully with cluster labels added.

Example:

| Song Name | Artist | Cluster |
|---|---|---|
| La Java | Mistinguett | 2 |

---

## Future Improvements

- Add Streamlit web application
- Build recommendation system
- Add genre prediction model
- Deploy project online

---

## Author

### Ragini

Machine Learning & Data Science Project