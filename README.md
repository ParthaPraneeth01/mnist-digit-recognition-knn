# 🧠 Digit Recognizer (MNIST + KNN)

This project implements a digit recognition system using the **MNIST dataset** 
and **K-Nearest Neighbors (KNN)** algorithm.  

- Framework: Google Colab  
- Dataset: MNIST (from Kaggle)  
- Model: KNN Classifier (sklearn)  
- Deployment: Kaggle Submission  

## Files
- `Hands-On-Deployment.ipynb` → Training + Evaluation
- `submission.csv` → Kaggle submission file
- `README.md` → Project description

## Sample Output

### Digit Prediction
![Prediction](screenshots/prediction.png)

### Submission File
![Submission](screenshots/submission_file.png)


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

### Sample Predictions
Digits visualized from the test set and their predictions:

![Sample Predictions](./sample-predictions.png)

---

## 🏆 Kaggle Competition Performance

This project was submitted to the [Kaggle Digit Recognizer Competition](https://www.kaggle.com/c/digit-recognizer).  

- **Public Leaderboard Score:** `0.96414`  
- **Submission file:** `submission.csv`  

![Kaggle Leaderboard](./kaggle-score.png)

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
