# MPS Applied AI — Coursework Portfolio

Graduate coursework from the **Master of Professional Studies in Applied AI** program at **Northeastern University** (Charlotte Campus). This repository contains selected notebooks and projects spanning artificial intelligence fundamentals, machine learning, and deep learning — demonstrating end-to-end ML pipelines, search algorithms, reinforcement learning, and neural network architectures.

> **Note:** This repo focuses on coursework. For my flagship applied AI project, see [Harbor](https://github.com/MichaelZimm20/AAI6600-Mental-Health-Chatbot-XL) — an AI-powered mental health chatbot for college students, built as the AAI6600 group capstone.

---

## Repository Structure

```
.
├── AAI6600-Applied-AI/
│   └── maze_solver_development.ipynb
│
├── AAI6610-Applied-Machine-Learning/
│   ├── credit_risk_pipeline.ipynb
│   ├── credit_risk_deep_learning_pipeline.ipynb
│   ├── wine_clustering.ipynb
│   ├── mountaincar_deep_q_learning.ipynb
│   └── credit_risk_reeval_tuning.ipynb
│
├── AAI6640-Applied-Deep-Learning/
│   ├── AAI6640_A1_DL_Fundamentals.ipynb
│   ├── AAI6640_A2_MNIST_Weight_Initialization.ipynb
│   └── AAI6640_A3_Advanced_CNNs.ipynb
│
└── README.md
```

---

## AAI6600 — Applied Artificial Intelligence

Foundations of AI: search algorithms, knowledge representation, reasoning, planning, and decision-making.

| Notebook | Description |
|----------|-------------|
| **Maze Solver** | Implementation of BFS, DFS, and Greedy Best-First Search algorithms for maze solving. Includes maze parsing, path visualization, and performance comparison across all three strategies. |

---

## AAI6610 — Applied Machine Learning

End-to-end machine learning pipeline development, from supervised and unsupervised learning through reinforcement learning and model deployment.

| Notebook | Description |
|----------|-------------|
| **Credit Risk Pipeline** | Custom `CreditRiskPipeline` class training Logistic Regression, Random Forest, and LightGBM on the UCI Credit Card Default dataset (30K records). Includes preprocessing, evaluation (accuracy, ROC AUC, confusion matrix), qualitative error analysis, and model serialization via joblib. |
| **Credit Risk — Deep Learning** | Extends the Module 3 pipeline with a TensorFlow/Keras neural network. Compares deep learning performance against the three statistical models on the same credit risk dataset. |
| **Wine Clustering** | K-Means vs. Agglomerative Clustering on the UCI Wine dataset. Includes PCA-based visualization, dendrogram analysis, and evaluation with silhouette score, adjusted Rand index, and normalized mutual information. |
| **MountainCar Deep Q-Learning** | Deep Q-Network (DQN) agent using PyTorch and Gymnasium to solve the MountainCar-v1 environment. Implements experience replay, epsilon-greedy exploration, and target network updates. |
| **Credit Risk — Re-Evaluation & Tuning** | Final iteration of the credit risk pipeline across all four models (LogReg, RF, LightGBM, Neural Network). Adds balanced class weights, expanded metrics (precision, recall, F1), and hyperparameter tuning on the best-performing model. |

### Credit Risk Pipeline Progression

The credit risk project evolves across three modules, demonstrating iterative model development:

1. **Module 3** — Baseline statistical ML pipeline (3 models)
2. **Module 5** — Deep learning extension (neural network added)
3. **Module 8** — Full re-evaluation with class balancing, expanded metrics, and hyperparameter tuning

---

## AAI6640 — Applied Deep Learning

Neural network fundamentals, optimization, weight initialization, hyperparameter tuning, and convolutional architectures.

| Notebook | Description |
|----------|-------------|
| **A1 — Deep Learning Fundamentals** | Gradient descent theory, backpropagation derivation for a fully connected network (sigmoid activation, cross-entropy loss), and forward/backward pass implementation. |
| **A2 — MNIST Weight Initialization** | Comparison of Xavier vs. Kaiming initialization on MNIST using PyTorch. Analyzes the impact of initialization strategy on training convergence and classification accuracy. |
| **A3 — Advanced CNNs** | MLP and CNN hyperparameter tuning on MNIST via grid search. Explores hidden layer configurations, dropout rates, and optimizer selection. Evaluates model performance across tuning combinations. |

---

## Tech Stack

- **Languages:** Python
- **ML/DL Frameworks:** scikit-learn, LightGBM, TensorFlow/Keras, PyTorch
- **Data & Visualization:** pandas, NumPy, Matplotlib, Seaborn
- **Hyperparameter Tuning:** GridSearchCV, Optuna (Bayesian/TPE)
- **RL Environment:** Gymnasium (OpenAI)
- **Tools:** Jupyter Notebook, joblib, Gradio (deployment — separate repo)

---

## Related Repositories

| Project | Description |
|---------|-------------|
| [Harbor (AAI6600 Capstone)](https://github.com/MichaelZimm20/AAI6600-Mental-Health-Chatbot-XL) | AI-powered mental health chatbot for college students — contributed to Pipeline 1 (data processing, clustering, ML classification) |
| [Credit Risk Deployment](https://github.com/MichaelZimm20/credit-risk-deployment) | CI/CD pipeline serving the trained credit risk model via Gradio |

---

## About

**Michael Zimmerman**  
MPS Applied AI Candidate — Northeastern University (Charlotte Campus)  
BS Computer Science | IT Specialist | Full-Stack Developer

- [LinkedIn](https://linkedin.com/in/michael-zimmerman-jr-8b859169/)
- [GitHub](https://github.com/MichaelZimm20)
