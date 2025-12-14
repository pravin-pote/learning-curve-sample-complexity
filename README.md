# learning-curve-sample-complexity
# Learning Curve & Sample Complexity Analysis

This project demonstrates how model performance changes as the amount of training data increases.  
It uses a Decision Tree classifier on a synthetic binary classification dataset to empirically study learning curves and sample complexity.

---

## 📌 Objective
- Understand how accuracy varies with training set size
- Visualize learning behavior of a bounded-complexity model
- Study generalization and data sufficiency

---

## 🧠 Key Concepts Covered
- Train–test split
- Decision Tree classifier
- Model generalization
- Learning curve
- Sample complexity
- Bias–variance tradeoff (empirical)

---

## 🛠️ Tech Stack
- Python
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📊 Methodology
1. Generate synthetic 2D classification data
2. Train a Decision Tree with fixed max depth
3. Vary training data size from 10% to 90%
4. Evaluate accuracy on unseen test data
5. Plot training size vs accuracy (learning curve)

---

## 📈 Result
The learning curve shows how accuracy improves with more data and eventually plateaus, indicating the model’s capacity limit.

---

## 📂 Files
- `learning_curve_sample_complexity.ipynb` — main notebook with code and explanations

---

## 🚀 How to Run
```bash
pip install numpy pandas matplotlib scikit-learn
