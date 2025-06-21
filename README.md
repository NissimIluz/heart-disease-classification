# 🫀 End-to-End Heart Disease Classification

This project demonstrates a full pipeline for classifying heart disease using machine learning. It includes data loading, exploratory analysis, preprocessing, model training, and evaluation — all in a single, well-documented Jupyter notebook.

---

## 📁 Project Structure

- `end-to-end-heart-disease-classification.ipynb` — The main notebook containing the full end-to-end workflow.
- `data/` — Placeholder for data files (ignored in version control).
- `environment.yml` — Conda environment file with all required dependencies.
- `.gitignore` — Specifies files and folders to exclude from Git.
- `.vs/`, `.ipynb_checkpoints/`, `env/` — IDE metadata, notebook backups, and virtual environment folders.

---

## 🚀 Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/USERNAME/heart-disease-classification.git
cd heart-disease-project
```

### 2. Create the conda environment:
```bash
conda env create -f environment.yml
conda activate heart-disease-classification
```

If you want to create the environment inside the project folder (e.g., ./env), use the following:
```bash
conda env create -f environment.yml -p ./env
conda activate ./env
```

### 3. Launch the notebook:
```bash
jupyter notebook
```

---

## 🧠 Project Highlights

- Uses the **Heart Disease dataset** from [`sklearn.datasets`](https://scikit-learn.org/stable/datasets/toy_dataset.html)
- Performs exploratory data analysis (EDA)
- Applies preprocessing: encoding, scaling, splitting
- Trains several classifiers (e.g., Logistic Regression, Random Forest)
- Evaluates using metrics like **AUC**, **ROC curve**, **confusion matrix**
- Achieves high performance (AUC > 0.9)

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- Conda (for environment management)

---

## ⚠ Notes

- The dataset is loaded programmatically from scikit-learn, not stored in the repo
- The notebook is meant to run locally in a Conda-managed environment
- This project is for educational and demonstration purposes

---

## 👨‍💼 Author

**Nissim Iluz**  
[github.com/NissimIluz](https://github.com/NissimIluz)
