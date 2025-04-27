project-name/
│
├── .vscode/                    # VS Code settings (optional)
│   └── settings.json
│
├── data/                       # Raw and processed data
│   ├── raw/                    # Original, immutable data
│   ├── processed/              # Cleaned, transformed data
│   └── external/               # Third-party or external datasets
│
├── notebooks/                 # Jupyter notebooks
│   └── exploration.ipynb       # Example EDA notebook
│
├── src/                        # Source code for the project
│   ├── __init__.py
│   ├── data/                   # Data loading, transformation scripts
│   │   └── load_data.py
│   ├── features/               # Feature engineering scripts
│   │   └── build_features.py
│   ├── models/                 # Modeling scripts
│   │   └── train_model.py
│   └── visualization/          # Visualization scripts
│       └── plot.py
│
├── tests/                      # Unit tests
│   └── test_train_model.py
│
├── outputs/                    # Generated outputs like models, figures
│   ├── models/                 # Trained model binaries
│   └── figures/                # Generated plots
│
├── requirements.txt            # Project dependencies
├── environment.yml             # Conda environment file (optional)
├── .gitignore                  # Git ignore file
├── README.md                   # Project overview
└── setup.py                    # If packaging the project
