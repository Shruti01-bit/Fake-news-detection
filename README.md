# Fake-news-detection
This is an AI/ML project focused on Fake News Detection. This project uses LR model trained on collected news datasets. 

##  Features

* **Binary Text Classification:** Predicts whether an input news article is fake or true.
* **Production-Ready Assets:** The project includes a pre-trained model and vectorizer for immediate use.
* **Reproducible Environment:** Uses a standard `requirements.txt` file for easy setup.
* **Simple Deployment:** Includes application code (`app`) for running the model in a prediction environment.

##  Project Structure

| File/Folder | Description |
| :--- | :--- |
| `app.ipynb` | Jupyter Notebook containing the **full ML workflow**: data loading, preprocessing, vectorization, model training, and evaluation. |
| `Fake/` & `True/` | Folders containing the raw text data used for training (labeled data). |
| `lr_model.jb` | The **trained Logistic Regression model** saved using `joblib`. |
| `vectorizer.pkl` | The **fitted text vectorizer** (e.g., TF-IDF) necessary to transform new text into a numerical format the model understands. |
| `requirements` | Lists all necessary Python packages and their specific versions. |
| `app` (or `app.py`) | The final application script for running the model to make real-time predictions. |

## Setup and Installation

Follow these steps to set up and run the project locally.

### 1. Clone the Repository
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd fake-news-detection-classifier

##2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
##3. Install Dependencies
pip install -r requirements

##Running the Project
Start the Jupyter server:jupyter notebook

