# Deep Learning Lab (B.Tech CSE - VII Semester)
### Shri Ramswaroop Memorial University (SRMU)
**Repository**: [Sumit2003-dev/DEEP-LEARNING](https://github.com/Sumit2003-dev/DEEP-LEARNING)

---

## 📖 Overview
This repository contains comprehensive, publication-ready Jupyter Notebooks (`.ipynb`) for the **Deep Learning Lab** course (B.Tech Computer Science & Engineering, 7th Semester). Each notebook includes detailed theoretical foundations, mathematical formulations with LaTeX, step-by-step modular Python implementations, diagnostic visualizations, and university viva-voce review questions.

---

## 🧪 Experiments Index

| Exp No. | Experiment Title | Description | Status |
| :---: | :--- | :--- | :---: |
| **01** | [Experiment 1.ipynb](./Experiment%201.ipynb) | **Introduction to Deep Learning & TensorFlow Setup**<br>• Core concepts: AI vs ML vs DL, representation learning, biological vs artificial neuron.<br>• Comprehensive 8-stage Deep Learning pipeline & industrial applications.<br>• Environment installation, setup, and hardware discovery (GPU/CPU) in TensorFlow.<br>• Tensor creation, shapes, ranks, and basic arithmetic verification (`tf.add`, `tf.matmul`). | ✅ Completed |
| **02** | [Experiment 2.ipynb](./Experiment%202.ipynb) | **End-to-End Machine Learning Pipeline in Python**<br>• Full ML workflow on Wisconsin Breast Cancer dataset.<br>• Exploratory Data Analysis (EDA) and distribution plotting.<br>• Data preprocessing & data leakage prevention with `StandardScaler`.<br>• Model training: Logistic Regression, SVM, Random Forest, Decision Tree.<br>• Evaluation: Confusion Matrix, Precision, Recall, F1, ROC-AUC, 5-Fold Cross-Validation.<br>• Top clinical feature importances and inference pipeline on unseen samples. | ✅ Completed |
| **03** | [Experiment 3.ipynb](./Experiment%203.ipynb) | **Perceptron & Neural Network from Scratch using NumPy**<br>• Rosenblatt's single-layer Perceptron (Heaviside step function).<br>• Convergence on linearly separable gates (AND, OR) & failure on XOR (Minsky-Papert theorem).<br>• 2-layer Multi-Layer Perceptron (MLP) built from first principles in NumPy.<br>• Xavier/He initialization, forward pass, binary cross-entropy loss.<br>• Analytical backpropagation (chain rule calculus for $d\mathbf{W}, d\mathbf{b}$).<br>• 100% convergence on XOR and non-linear `make_moons` decision boundary visualization. | ✅ Completed |
| **04** | [Experiment 4.ipynb](./Experiment%204.ipynb) | **Study & Implementation of Activation Functions**<br>• Mathematical definitions and NumPy implementations for Sigmoid, Tanh, ReLU, Leaky ReLU, and Softmax.<br>• Analytical first derivatives and comparative plots across $[-6, 6]$.<br>• Numerically stable Softmax calculation (preventing overflow).<br>• Simulation of the **Vanishing Gradient Problem** across 10 deep layers.<br>• Dying ReLU analysis and Leaky ReLU remedy.<br>• Empirical benchmark: Training identical networks on Digits dataset comparing loss and accuracy curves. | ✅ Completed |
| **05** | [Experiment 5.ipynb](./Experiment%205.ipynb) | **Implementation of Logistic Regression using TensorFlow**<br>• Mathematical formulation: linear logits, sigmoid hypothesis, convex log-loss.<br>• **Low-level TensorFlow**: Trainable parameters (`tf.Variable`), custom cross-entropy, manual gradient descent via `tf.GradientTape`.<br>• **High-level Keras**: Equivalent model via `tf.keras.Sequential` and `Dense(1, activation='sigmoid')`.<br>• Metric benchmarking: Confusion matrix heatmaps, ROC curves.<br>• 2D linear decision boundary visualization ($w_1 x_1 + w_2 x_2 + b = 0$). | ✅ Completed |
| **06+** | *Upcoming Experiments* | **Convolutional Neural Networks (CNNs), RNNs, LSTMs, and Advanced Architectures** | ⏳ *Coming Soon* |

> 📌 **Note**: Remaining syllabus experiments (CNNs, Pooling, Data Augmentation, RNNs, LSTMs, and End-to-End Deep Learning Projects) will be added soon.

---

## 🛠️ Prerequisites & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Sumit2003-dev/DEEP-LEARNING.git
cd DEEP-LEARNING
```

### 2. Set Up a Virtual Environment (Recommended)
```bash
# Windows
python -m venv dl_env
dl_env\Scripts\activate

# macOS / Linux
python3 -m venv dl_env
source dl_env/bin/activate
```

### 3. Install Dependencies
```bash
pip install tensorflow numpy matplotlib seaborn pandas scikit-learn jupyter
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
Navigate to any experiment file (e.g., `Experiment 1.ipynb`) and run the cells interactively.

---

## 📂 Notebook Structure
Every experiment notebook follows a standardized format:
1. **Academic Header & Course Metadata**
2. **Aim / Objectives**
3. **Prerequisites & Tool Requirements**
4. **Theoretical Background & Mathematical Formulations** (LaTeX equations, comparison tables, ASCII diagrams)
5. **Step-by-Step Python Implementation** (Modular, well-commented code cells)
6. **Visualizations & Output Analysis** (Matplotlib & Seaborn plots)
7. **Viva-Voce / Review Questions with Detailed Answers**
8. **Conclusion & Key Takeaways**

---

## 👤 Author
* **Sumit Kumar** ([@Sumit2003-dev](https://github.com/Sumit2003-dev))
* B.Tech Computer Science & Engineering (VII Semester)
* Shri Ramswaroop Memorial University (SRMU)
