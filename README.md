# 🖊️ MNIST Digit Recognition (KNN, Colab)

This project demonstrates handwritten digit classification using the **MNIST dataset** and the **k-Nearest Neighbors (KNN)** algorithm.  
The implementation is done in a Google Colab notebook with step-by-step workflow, including data preprocessing, model training, hyperparameter tuning, predictions, and Kaggle submission.

---

## 📂 Project Contents

- **Notebook:** `Hands-On-Deployment.ipynb`
- **Submission file:** `submission.csv` (for Kaggle competition)
- **Main steps:**
  - Download and preprocess MNIST dataset
  - Train/test split
  - KNN training and hyperparameter tuning (`GridSearchCV`)
  - Predictions for test data
  - Visualization of sample digit predictions
  - Kaggle submission generation

---

## 🔍 Example Output
A preview of the Kaggle submission file (`submission.csv`):

| ImageId | Label |
|---------|-------|
| 1       | 2     |
| 2       | 0     |
| 3       | 9     |
| 4       | 4     |
| 5       | 3     |

The file contains 28,000 rows, one for each test image.

## 🏆 Kaggle Competition Performance

This project was submitted to the [Kaggle Digit Recognizer Competition](https://www.kaggle.com/c/digit-recognizer).  

- **Public Leaderboard Score:** `0.96414`  
- **Submission file:** `submission.csv`  

[![Kaggle Leaderboard](./kaggle-score.png)](https://www.kaggle.com/competitions/digit-recognizer/leaderboard)

---

## ▶️ How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the `.ipynb` file or clone this repo and open it directly.
3. Run all cells to:
   - Train the model
   - Predict MNIST digits
   - Generate `submission.csv` for Kaggle

---

## ⚙️ Requirements

The notebook uses these Python libraries (all preinstalled in Colab):

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

---

## 📊 Results

- Achieved **96.41% accuracy** (Kaggle public leaderboard).  
- Successfully generates predictions for Kaggle competition.  
- Visualizations of digit predictions included.

---

## 👨‍💻 Author

- Partha Praneeth Reddy Pocham Reddy
- parthapraneeth01@gmail.com
- www.linkedin.com/in/partha-praneeth

---

## 📜 License

This project is open-source for learning and academic purposes.  
Consider adding an open-source license (MIT recommended).
