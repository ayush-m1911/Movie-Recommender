# 🎬 Movie Recommender System – Model Files

This repository contains the serialized pickle (`.pkl`) files used in the **Movie Recommender System** project.  
These files are required to load the pre-trained similarity matrix and movie data for generating recommendations.

## 📂 Files Included
- `similarity.pkl` → Stores the similarity matrix used to recommend the top 5 similar movies.  
- `movies_dict.pkl` → Contains the processed movie data used for recommendations.  
- *(Other `.pkl` files as needed)*  

## 📥 Download Model Files
Due to GitHub's file size limits, the `similarity.pkl` file is hosted on Google Drive.  
👉 [Download similarity.pkl]((https://drive.google.com/file/d/1G7dOmIgnS-JaCNgJcDaRcqEl9ZTqc71m/view?usp=sharing))  

Make sure to place the downloaded file in the same directory as your notebook or project code.  

## 🚀 Usage
Example of loading the pickle files in Python:
```python
import pickle

# Load similarity matrix
similarity = pickle.load(open("similarity.pkl", "rb"))

# Load movie data
movies_dict = pickle.load(open("movies_dict.pkl", "rb"))
