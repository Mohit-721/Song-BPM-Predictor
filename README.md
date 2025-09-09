# 🎵 Song Beats Per Minute (BPM) Prediction

**Author:** Mohit Kumar  
**Date:** 2025-09-09

This project predicts the Beats Per Minute (BPM) of songs using machine learning regression models trained on engineered audio features.  
It showcases EDA, model comparison, and a reproducible ML workflow in a Colab notebook.

## 🚀 Project Highlights

- **Exploratory Data Analysis (EDA)**: Visualizes feature distributions and correlations.
- **Model Training**: Compares Linear Regression, Random Forest, and Gradient Boosting models.
- **Performance Evaluation**: Uses MAE and RMSE to compare model results.
- **Clean, organized notebook**: With detailed commentary and result visualizations.

---

## 📂 Dataset

**The full train/test files are not included in this repo due to size constraints.**

**Download the required data from this Google Drive folder:**

**[ https://drive.google.com/drive/folders/1ZfPBfVBwHc4Psumv7WZ_JudndvJqIy--?usp=sharing ]**

- Download both `train.csv` and `test.csv`
- Place them in your working directory or upload into Colab before running the notebook

---

## 📝 How to Run

1. **Clone this repository** or download the notebook.
2. **Open the notebook** in Google Colab or Jupyter.
3. **Upload/download `train.csv` and `test.csv`** into the working directory.
4. **Run all cells** from top to bottom. The notebook will generate `submission.csv` as output.

---

## 🛠️ Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

*(Installing these is easy! In Colab, they’re pre-installed. Otherwise: `pip install pandas numpy matplotlib seaborn scikit-learn`)*

---

## 📊 Output

- The notebook will create a file `submission.csv` containing BPM predictions for each test sample.

---

## 💡 Project Structure

- `bpm_prediction_notebook.ipynb` – Main workflow (EDA, modeling, results)
- `README.md` – Project introduction and instructions

---

## 🙌 Acknowledgments

Inspired by music data prediction challenges and educational ML workflows.

---

**Questions or feedback? Feel free to open an issue or submit a pull request!**
