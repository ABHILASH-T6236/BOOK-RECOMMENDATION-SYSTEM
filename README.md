# BOOK-RECOMMENDATION-SYSTEM
**Book Recommendation System**    This project builds a book recommendation system using collaborative filtering and SVD. It suggests books based on popularity, user similarity, and matrix factorization. The model is evaluated using RMSE and a confusion matrix. Built with Python, Pandas, Surprise, and Scikit-Learn.
# Book Recommendation System

## Project Overview
This project implements a **Book Recommendation System** using collaborative filtering and machine learning techniques. It suggests books based on user preferences, popularity, and similarity between users.

## Features
- **Popularity-Based Recommendations** – Suggests top-rated books.
- **User-Based Collaborative Filtering** – Uses cosine similarity to find similar users.
- **Matrix Factorization (SVD)** – Provides personalized recommendations.
- **Performance Evaluation** – Evaluates the model using RMSE and a confusion matrix.

## Technologies Used
- **Python**
- **Pandas, NumPy** – Data preprocessing and manipulation
- **Surprise** – Collaborative filtering and SVD implementation
- **Scikit-Learn** – Similarity computation and evaluation metrics
- **Matplotlib, Seaborn** – Data visualization

## Dataset
The system uses three datasets:
1. **Books.csv** – Contains book details
2. **Users.csv** – Contains user information
3. **Ratings.csv** – Contains user ratings for books

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/book-recommendation-system.git
   cd book-recommendation-system
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script:
   ```sh
   python recommendation_system.py
   ```

## Usage
- The system suggests books based on user preferences.
- Enter a **User-ID** to get personalized recommendations.
- Predict ratings for books using the trained SVD model.

## Evaluation
- RMSE is used to measure recommendation accuracy.
- A confusion matrix evaluates classification performance.

## Future Improvements
- Implement hybrid models combining content-based and collaborative filtering.
- Deploy as a web app using Flask or Streamlit.
- Enhance performance with deep learning techniques.

## Contributing
Feel free to fork the repository, create a branch, and submit a pull request for improvements.

## License
This project is open-source and available under the **MIT License**.

---

For any issues or suggestions, feel free to open an issue on GitHub!

