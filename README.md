# Classification Bank Customer Reviews - NLP Project

## Overview
This project aims to predict customer satisfaction based on review texts, using natural language processing (NLP) and supervised classification techniques.

## Project Structure

```
├── app/              # Application source code (empty for now)
├── corpora/          # Additional corpora (NLTK multilingual stopwords) used for NLP tasks
├── data/             # Raw and processed datasets from TrustPilot (not included due to usage restrictions)
├── mlflow/           # MLflow experiment with runs
├── models/           # Saved trained models (.joblib)
├── notebooks/        # Jupyter notebooks (3 present ; "4_transformers_modeling.ipynb" coming soon)
├── scripts/          # Utility and automation scripts (empty for now)
├── .gitignore        # Git ignore rules for the repository
├── environment.yml   # Conda environment specification
├── LICENSE           # Project license (MIT)
└── README.md         # This file
```

## Setup

Create the environment with Conda using the `environment.yml` file:

```bash
conda env create -n your_env_name -f environment.yml
conda activate your_env_name
```

## Data Disclaimer
This project uses data scraped from TrustPilot. The data itself is **not included** in this repository. Please note that any use of the data is subject to TrustPilot’s terms of service. Users are responsible for complying with these terms when accessing or using TrustPilot data.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
