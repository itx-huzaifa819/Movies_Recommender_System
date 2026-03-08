# 🎬 Movie Recommender System

A beginner-friendly **Movie Recommender System** built using Python and **Machine Learning**, deployed on **Heroku** and run with **Streamlit** for an interactive web interface.

This project recommends movies to users based on similarity and preferences, providing an easy-to-use interface.

---

## 🔹 Features
- Recommend movies based on user-selected titles.
- Uses machine learning techniques to compute similarities.
- Interactive **Streamlit** web app interface.
- Precomputed datasets (`movie_dict.pkl` and `similarity.pkl`) for fast recommendations.
- Deployed online via **Heroku**: [Click here to try](https://movie-recommnder-system-hs819-c55478a5d65f.herokuapp.com/)

---

## 🔹 Project Files Overview
| File / Folder       | Description |
|--------------------|-------------|
| `app.py`           | Main Streamlit application that runs the web interface. |
| `main.py`          | Backend Python code handling recommendation logic. |
| `movie_dict.pkl`   | Pickled dataset dictionary containing movie information. |
| `similarity.pkl`   | Precomputed similarity matrix used for recommendations. |
| `requirements.txt` | Python dependencies required to run the project. |
| `Procfile`         | Heroku deployment configuration file. |
| `setup.sh`         | Script used during Heroku deployment. |
| `.gitignore`       | Files/folders to ignore in GitHub (like virtual environments). |
| `notebooks/`       | Optional: Jupyter notebook with initial exploration and code experiments. |
| `assets/`          | Optional: screenshots or demo images. |

---

## 🔹 Installation (Local Run)
1. Clone the repository:
```bash
git clone https://github.com/itx-huzaifa819/Movie_Recommender_System.git