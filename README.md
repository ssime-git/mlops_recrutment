# MLOps Internship Assessment

This repository contains a guided machine learning workflow on the [UCI Wine dataset](https://archive.ics.uci.edu/ml/datasets/wine). The notebook walks through exploratory data analysis, model training, evaluation, and artifact persistence. Candidates are expected to extend the work by serving the trained model via FastAPI and packaging the solution in Docker.

## Contents
- `data/wine.csv` – raw dataset downloaded from UCI.
- `notebooks/ml_workflow.ipynb` – the end-to-end ML workflow to review and execute.
- `requirements.txt` – Python dependencies needed to run the notebook and prepare for the API task.

## Getting Started
1. Create and activate a Python 3.9+ virtual environment.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch JupyterLab or Jupyter Notebook:
   ```bash
   jupyter lab
   ```
4. Open `notebooks/ml_workflow.ipynb`, execute the cells, and review the workflow.

## Next Steps for Candidates
- Build a FastAPI application that loads `artifacts/wine_classifier.joblib` and exposes an inference endpoint.
- Add automated tests for the API (for example, with `pytest`).
- Create a `Dockerfile` to containerize the API with all required assets.
- Document how to build and run the container, run tests, and call the API.

Good luck!
