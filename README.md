# ✋ Finger Counting using Classical Machine Learning

This mini-project tackles a computer-vision task: **identifying the number of fingers held up in front of a camera** using fundamental, classical ML algorithms.

The goal is to explain and teach the **pros and cons of learning algorithms** such as **Decision Trees, Random Forests, Support Vector Machines**, and more, by applying them to the same problem and comparing their behavior.

This repository is part of the course **Foundations of Modern Machine Learning (FMML)**, offered by **iHub, IIIT Hyderabad**.

---

## 🎯 Objectives

- Understand how images can be turned into features for ML models
- Apply classical algorithms to a real image-classification problem
- Compare the strengths and weaknesses of each algorithm
- Learn how to evaluate and improve models (accuracy, overfitting, generalization)

## 🧠 Algorithms Covered

| Algorithm | What it teaches |
|---|---|
| **Decision Trees** | Interpretable rules, tendency to overfit |
| **Random Forests** | Ensemble learning, reducing variance |
| **Support Vector Machines (SVM)** | Margins, kernels, high-dimensional data |
| **Others** | Additional baseline models for comparison |

## 📂 Repository Structure

```
├── Module notebooks (.ipynb)    # Labs covering concepts step by step
├── Project notebooks (.ipynb)   # Finger-counting mini-project
└── README.md
```

## 🛠️ Tech Stack

- **Language:** Python 3
- **Libraries:** NumPy, pandas, Matplotlib, scikit-learn, OpenCV (for image handling)
- **Environment:** Google Colab / Jupyter Notebook

## 🚀 Getting Started

### Run on Google Colab (recommended)
1. Open any `.ipynb` file from this repository.
2. Click **"Open in Colab"** or upload it at [colab.research.google.com](https://colab.research.google.com).
3. Run the cells in order (`Runtime → Run all`).

### Run locally
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
pip install numpy pandas matplotlib scikit-learn opencv-python jupyter
jupyter notebook
```

## 🔄 Project Workflow

1. **Data collection:** images of hands showing 0–5 fingers
2. **Preprocessing:** resizing, grayscale conversion, normalization
3. **Feature extraction:** converting images into numerical features
4. **Model training:** Decision Tree, Random Forest, SVM, etc.
5. **Evaluation:** accuracy, confusion matrix, comparison across models
6. **Analysis:** discussing pros and cons of each algorithm

## 📊 Results

_Add your model accuracies and comparison table or charts here._

| Model | Accuracy |
|---|---|
| Decision Tree | – |
| Random Forest | – |
| SVM | – |

## 🔮 Future Improvements

- Real-time finger counting using a webcam
- Try deep learning (CNNs) and compare with classical methods
- Improve robustness to lighting and background changes

## 🙏 Acknowledgements

Part of the **Foundations of Modern Machine Learning** course by **iHub, IIIT Hyderabad**. Thanks to the course instructors and teaching staff.

## 👤 Author

**Rishanth Midde**
- GitHub: [Rishuu68](https://github.com/Rishuu68)
- LinkedIn: [rishanth-midde](https://linkedin.com/in/rishanth-midde)
