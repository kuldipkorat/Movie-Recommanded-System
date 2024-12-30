# 🎥 Movie Recommendation System

Welcome to the **Movie Recommendation System**! This project delivers personalized movie recommendations using a content-based filtering approach. By leveraging metadata such as genres, keywords, cast, and crew, the system identifies movies with similar features and provides tailored suggestions.

## Types of Recommendation Systems
There are three primary types of recommendation systems:
1. **Content-Based Recommendation Systems**
2. **Collaborative Recommendation Systems**
3. **Hybrid Recommendation Systems**

This project specifically implements a **content-based approach**, focusing on individual movie metadata to calculate similarities.

---

## 🚀 Project Overview
The Movie Recommendation System processes a dataset of 5,000 movies and uses a content-based filtering technique. Features from metadata fields (such as genres, keywords, cast, and crew) are combined into a single text representation. The system uses **CountVectorizer** to extract meaningful patterns from this data and calculates similarities between movies using **cosine similarity**. 

When you input a movie name, the system finds the top five most similar movies, offering recommendations that align with your preferences.

---

## 🎯 Key Features
- **Content-Based Filtering**: Generates recommendations based on movie metadata, including genres, keywords, cast, and crew.
- **Advanced Text Processing**: Metadata undergoes cleaning, parsing, and vectorization for effective similarity computations.
- **Cosine Similarity**: Ensures accurate similarity measures between movies based on their feature vectors.
- **Interactive Interface**: A user-friendly web application built with Streamlit makes the system accessible and intuitive.

---

## 🛠️ Technologies Used
The project incorporates several technologies to achieve its functionality:

- **Python**: Core language for data processing and running the recommendation engine.
- **nltk**: Used for natural language processing tasks such as stopword removal, stemming, and lemmatization.
- **Pandas**: Efficient data manipulation and cleaning.
- **Scikit-Learn**: Provides tools for vectorization (CountVectorizer) and similarity computations (cosine similarity).
- **Streamlit**: Simplifies the creation of an interactive web-based interface.


## 📝 Generating Pickle Files
This project generates two essential files during the model training process. These files store precomputed data, allowing the recommendation engine to operate efficiently:

similarity.pkl: Stores the precomputed similarity matrix.
movies.pkl: Contains processed movie data with metadata.
To create these files:

Open the movie_recommend_system.ipynb notebook.
Run the necessary cells to preprocess the data and compute the similarity matrix.
Save the output files (similarity.pkl and movies.pkl) in the project directory.
Once generated, these files will enable the recommendation system to function as expected.

## 🤝 Contributions
Contributions are always welcome! Feel free to fork the repository, open issues, or submit pull requests to enhance the project.