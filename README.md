# CS536 – Web Mining: Web Structure Mining Project

## 📘 Course Information

- **Course:** CS536 – Web Mining  
- **Term:** Winter 2025  
- **Institution:** Bishop's University  
- **Project Type:** Final Project  
- **Topic:** Social Network Analysis using Web Structure Mining  

---

## 📌 Project Overview

This project applies **graph theory and web structure mining techniques** to a real-world social network dataset — a Twitter ego network. The analysis identifies influential users, detects community structures, and explores overall network properties.

Key tasks:
- Data preprocessing and graph construction
- Network analysis to identify influencers
- Community detection using modularity optimization
- Visualization of network structure and key nodes
- Interpretation of social structure and interaction patterns

---

## 📊 Dataset

- **Type:** Twitter ego network
- **Format:** Edge list (`.edges` file)
- **File:** `data/1775731.edges`
- **Description:** Represents user connections (follower/following relationships) within a Twitter ego network

---

## 🧠 Methods & Analysis

### 1. Data Preprocessing
- Load raw edge list data
- Construct an undirected graph using NetworkX
- Remove self-loops and isolated nodes

### 2. Network Analysis
- Degree Centrality
- PageRank
- Network Density
- Community Detection using greedy modularity optimization

### 3. Visualization
- Community structure visualization with color-coded communities
- Influential users highlighted by centrality scores
- Full network visualization with labeled top nodes

### 4. Key Results

| Metric | Value |
|---|---|
| Total Nodes | 46 |
| Total Edges | 423 |
| Network Density | ~0.4087 |
| Communities Detected | 3 |
| Modularity Score | 0.1823 |

Top influential node identified: **`14401912`** (highest Degree Centrality and PageRank)

---

## 🛠️ Technologies Used

- Python 3
- NetworkX
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 📂 Repository Structure

```
cs536-web-mining-structure-analysis/
├── code/
│   └── WMProject.ipynb     # Main analysis notebook
├── data/
│   ├── 1775731.edges       # Twitter ego network edge list
│   └── twitter/            # Additional Twitter data
├── docs/
│   ├── Project.pdf
│   └── Project.docx
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Jupyter or Google Colab:
   ```bash
   jupyter notebook code/WMProject.ipynb
   ```

2. Install required libraries if needed:
   ```bash
   pip install networkx matplotlib
   ```

---

## 📝 Notes

This project was developed as part of an academic course.  
The code is intended for educational and research purposes only.

## 👤 Author

**Ahmad Issa**  
Machine Learning Engineer | AI & Data Science  
[GitHub](https://github.com/issa89ai) · [LinkedIn](https://linkedin.com/in/ahmadissa)
