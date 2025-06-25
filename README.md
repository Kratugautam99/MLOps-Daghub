# MLOps-Dagshub

A streamlined MLOps pipeline integrating version control, model tracking, and reproducibility using **DagsHub**. Ideal for collaborative machine learning workflows and efficient experiment tracking.

## 🚀 Features

- 📦 Data and model versioning with DVC and Git  
- 🧪 Experiment tracking and reproducibility  
- 📊 Visual insights into model performance  
- 🤝 Seamless collaboration via DagsHub’s web UI  
- 🛠️ CI/CD integration for model deployment (optional extension)  

## 🔧 Tech Stack

- **Python**  
  The core programming language for building and orchestrating all components of your ML workflow—data processing, training scripts, API endpoints, and glue code for tools like DVC and MLflow.

- **DVC (Data Version Control)**  
  A Git-like system for versioning datasets, models, and pipeline stages. It helps you reproduce experiments and collaborate without storing large files in the Git repo, and enables pipeline orchestration with `dvc.yaml`.

- **Git**  
  Version control for code and lightweight files. Works in tandem with DVC to manage the code+data+model ecosystem in sync, allowing branching, reverting, and change tracking.

- **DagsHub**  
  A GitHub-integrated platform that brings Git, DVC, and experiment tracking together. Provides a UI to visualize experiments, compare runs, and store datasets and models—think of it as a collaborative MLOps dashboard.

- **MLflow**  
  An experiment tracking tool to log metrics, parameters, artifacts, and models. Lets you compare runs, register models, and optionally serve them via its model registry.

- **FastAPI**  
  A lightweight, high-performance Python web framework. Use it to serve trained models through RESTful API endpoints for real-time or batch predictions.

## 🏃 Getting Started

Clone the repo and enter the directory:

```bash
git clone https://github.com/your_username/MLOps-Daghub.git
cd MLOps-Daghub
