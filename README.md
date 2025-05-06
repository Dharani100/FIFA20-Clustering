⚽ FIFA 20 Player Clustering Project
📌 Project Overview
This project focuses on analyzing and clustering FIFA 20 players based on their attributes. Using unsupervised machine learning techniques, we grouped similar players and extracted insights that can help understand skill distribution, player value, and team planning.

📁 Dataset Overview
Source: Kaggle - FIFA 20 Complete Player Dataset

Records: 18,278 players

Features: 55 attributes including:

Name, Age, Nationality, Overall, Potential, Value, Wage, Preferred Foot, Work Rate, Skill Moves, Position, etc.

🎯 Objectives
Understand player characteristics and roles

Cluster players into groups based on similarity

Visualize player clusters to identify key patterns

Answer key questions such as:

Which features are important for clustering?

Which cluster contains top-rated or young talent?

How do wage and market value relate to clusters?

🔧 Tools & Technologies
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Techniques:

KMeans Clustering

Elbow Method

Principal Component Analysis (PCA)

Label Encoding

Data Normalization

📊 Project Workflow
Data Cleaning & Preprocessing

Handling missing values

Label encoding categorical columns

Scaling features

Exploratory Data Analysis

Visualizing distributions and correlations

Understanding relationships among key features

Clustering

Applied KMeans algorithm

Used Elbow Method to determine the optimal number of clusters

Applied PCA for dimensionality reduction

Visualization

Clustered player data using 2D plots

Highlighted characteristics of each cluster

📌 Key Insights
Clusters clearly separate players based on Overall rating, Value, and Age.

One cluster includes most high-value young players with strong growth potential.

Clustering helps scouts and clubs to group players beyond simple positions.

🧠 Skills Applied
Unsupervised Machine Learning

Feature Engineering

Data Normalization

Clustering Evaluation

PCA for visualization

📂 Folder Structure
bash
Copy
Edit
FIFA20-Clustering/
├── fifa20.csv                 # Raw dataset
├── FIFA20_Clustering.ipynb    # Jupyter notebook with code           # Output cluster visualization
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies
✅ Conclusion
This project demonstrates how machine learning can be applied to sports analytics to uncover insights from complex datasets. Clustering can guide recruitment, scouting, and game strategy planning.
