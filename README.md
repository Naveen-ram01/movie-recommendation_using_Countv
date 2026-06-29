
# 🎬 Movie Recommendation System using CountVectorizer

## 📌 Project Overview

This project is a **Content-Based Movie Recommendation System** built using Python and Machine Learning.  
It recommends similar movies based on movie metadata such as title, genre, keywords, cast, and overview.

The system uses **CountVectorizer** to convert movie text features into numerical vectors and applies **Cosine Similarity** to find movies that are most similar to the selected movie.

---

## 🚀 Features

- Recommends similar movies based on user input
- Uses content-based filtering
- Text feature extraction using CountVectorizer
- Similarity calculation using Cosine Similarity
- Simple and beginner-friendly ML project
- Useful for AI/ML portfolio and interviews

---

## 🧠 Recommendation Approach

This project follows a **Content-Based Filtering** approach.

### Workflow

1. Load movie dataset
2. Select important features
3. Handle missing values
4. Combine selected features into one text column
5. Convert text into vectors using CountVectorizer
6. Calculate similarity using Cosine Similarity
7. Recommend top similar movies

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- CountVectorizer
- Cosine Similarity
- Jupyter Notebook

---

## 📂 Project Structure

```text
movie_recommendation_using_CountV-main/
│
├── Movie_Recommendation_System.ipynb
├── movies.csv
├── credits.csv
├── similarity.pkl
├── movie_list.pkl
├── README.md
└── requirements.txt📊 Dataset

The project uses a movie metadata dataset containing details such as:

Movie title
Genres
Keywords
Cast
Crew
Overview

Dataset commonly used: TMDB 5000 Movie Dataset

⚙️ How to Run
Clone Repository
git clone https://github.com/Naveen-ram01/movie-recommendation.git
Go to Project Folder
cd movie-recommendation/movie_recommendation_using_CountV-main
Install Dependencies
pip install -r requirements.txt
Run Notebook
jupyter notebook

Open the notebook and run all cells.

🧪 Example

If the user selects:

Avatar

The system recommends similar movies based on content similarity.

📈 Future Improvements
Add Streamlit web app
Add movie posters using TMDB API
Improve recommendations using TF-IDF
Deploy project on Hugging Face Spaces or Streamlit Cloud
Add collaborative filtering
👨‍💻 Author

Malothu Naveen
GitHub: Naveen-ram01

⭐ If you found this project useful, give it a star!
