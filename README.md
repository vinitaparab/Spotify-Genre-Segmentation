# Spotify Songs Genre Segmentation 🎵

## 📌 Project Overview

**Spotify Songs Genre Segmentation** is a machine learning project that explores music data and groups songs based on their audio characteristics. The project uses **K-Means clustering** to identify patterns and similarities between songs using numerical audio features.

The goal is to understand how songs with similar musical characteristics can be grouped together using unsupervised machine learning techniques.

## 🎯 Objectives

- Analyze Spotify song data and explore musical characteristics.
- Perform data preprocessing and exploratory data analysis (EDA).
- Identify patterns and relationships among audio features.
- Apply K-Means clustering to group similar songs.
- Use Principal Component Analysis (PCA) to help visualize high-dimensional data.
- Evaluate clustering quality using the Silhouette Score.
- Explore song similarities using Nearest Neighbors.
- Visualize patterns across genres and playlists.

## 🛠️ Technologies & Libraries Used

- **Python** – Data analysis and machine learning.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Scikit-learn** – Machine learning, clustering, dimensionality reduction, and similarity analysis.
- **Jupyter Notebook** – Interactive development and experimentation.

## 🎼 Audio Features Analyzed

The project explores audio characteristics such as:

| Feature | Description |
|---|---|
| Danceability | Indicates how suitable a track is for dancing. |
| Energy | Represents the perceived intensity and activity of a track. |
| Loudness | Measures the overall loudness of a track. |
| Speechiness | Estimates the presence of spoken words in a track. |
| Acousticness | Indicates how likely a track is to be acoustic. |
| Instrumentalness | Estimates whether a track contains vocals. |
| Liveness | Estimates the presence of a live audience. |
| Valence | Represents the musical positivity or happiness of a track. |
| Tempo | Represents the estimated speed of a track in beats per minute (BPM). |

These features help represent the musical properties of songs numerically, making them suitable for machine learning analysis.

## ⚙️ Methodology

### 1. Data Loading and Exploration

Load the dataset and inspect its structure, columns, data types, missing values, and statistical summaries to understand the available music data.

### 2. Data Preprocessing

Prepare the relevant audio features for analysis. Depending on the dataset, this may include handling missing values, selecting numerical columns, and scaling features before clustering.

### 3. Exploratory Data Analysis (EDA)

Use visualizations to explore the distribution of audio features and investigate patterns across playlist genres and playlist names.

### 4. K-Means Clustering

Apply the K-Means algorithm to group songs based on similarities in their selected audio features. K-Means assigns songs to clusters according to their distances from cluster centroids.

### 5. Principal Component Analysis (PCA)

Use PCA to reduce the dimensionality of the feature space and help visualize patterns in the clustered data.

### 6. Silhouette Score

Use the Silhouette Score to evaluate how well-separated the resulting clusters are. A higher score generally indicates better-defined clusters, although the best clustering also depends on the data and the intended use.

### 7. Nearest Neighbors

Explore song similarity using the Nearest Neighbors algorithm to identify tracks with similar audio-feature values.

## 📊 Key Learning Outcomes

Through this project, I explored:

- Data cleaning, preprocessing, and exploratory data analysis.
- Feature selection and analysis of numerical music data.
- Unsupervised machine learning using K-Means.
- Dimensionality reduction using PCA.
- Cluster evaluation using the Silhouette Score.
- Similarity analysis using Nearest Neighbors.
- Visualization and interpretation of music data patterns.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, or use an environment such as Google Colab.

### Step 1: Clone the Repository

```bash
git clone https://github.com/vinitaparab/Spotify-Genre-Segmentation.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Spotify-Genre-Segmentation
```

### Step 3: Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Open the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project's `.ipynb` notebook and execute the cells in order.

**Note:** Ensure that the dataset is available at the file path specified in the notebook. If the dataset is not included in the repository, obtain it from the original dataset source and update the path accordingly.

## 🔮 Future Enhancements

- Experiment with different numbers of clusters and compare their quality.
- Compare K-Means with other clustering algorithms.
- Build a simple music similarity or song recommendation interface.
- Explore additional audio features to improve similarity analysis.
- Develop an interactive dashboard for exploring clusters and song characteristics.

## 👩‍💻 Author

**Vinita Parab**

BSc Information Technology Graduate | Aspiring Software Developer

GitHub: [@vinitaparab](https://github.com/vinitaparab)

---

*This project was developed to explore data analysis, unsupervised machine learning, and music similarity using Spotify audio features.*
