# 📚 Simple Book Recommendation System 

This project demonstrates **how real-world recommendation systems work**, showing both content-based and collaborative/user-based approaches—all in a simple, ready-to-run Python script!

---

## 🚀 Features

- **Content-Based Filtering**: Recommends books by finding others with similar *category labels* using natural language processing (TF-IDF + cosine similarity).
- **Collaborative Filtering**: Recommends books for a user by analyzing the ratings of similar users and suggesting books with top ratings that the user hasn't rated.
- **All logic is visible and easy to follow**—great for learning or extending as a class project.

---

## 📦 Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

Install with:
`pip install pandas numpy scikit-learn`

---

## 🛠 How to Run

1. Save `recommend.py` in your folder.
2. Open terminal/command prompt in that folder.
3. Run: `python recommend.py`
4. Output will show:
- Recommended books *similar to* a given book (by content)
- Recommended books for a sample user (by user similarity)

---

## 💡 Example Output

Content-Based Recommendation for 'Python Crash Course': ['Machine Learning for Beginners', 'Deep Learning Fundamentals']
User-Based Recommendation for Charlie: ['Data Science Handbook']

---

## 🧑‍💻 What the Code Does

- **Loads a sample dataset**: 5 books, their topics, and 4 users’ ratings.
- **Content-Based**: For a book name, finds the 2 most similar books based on "Category".
- **User-Based**: For a username, finds books rated highest by a similar user (collaborative filtering).
- Prints results for both systems for you to compare!

---

## 🎓 Educational Goals

- Understand *how* platforms like Netflix, Spotify, and Amazon recommend content.
- See hands-on differences between Content-Based and Collaborative Filtering.
- Learn key concepts in data science: TF-IDF, cosine similarity, user-item matrices.

---

## 📜 License

MIT — free for education and personal experimentation.

---

**Just copy, run, and learn: this is a real-world recommendation engine broken down for bootcamp students!**
