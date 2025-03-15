# Predicting-Conflict-Escalation


## Overview
This project focuses on developing a multivariable linear regression model to analyze the impact of country-level indicators on prediction errors in conflict escalation models. By leveraging UNICEF data, we aim to improve predictive accuracy and identify key factors influencing model performance.

## Project Structure
```
final-project-confidence-intervals/
│── data/                  # Contains dataset files
│   ├── country_indicators.csv
│   ├── test_predictions.csv
│
│── notebooks/             # Jupyter notebooks for analysis
│   ├── Markdown_Slides.ipynb
│
│── docs/                  # Documentation (optional)
│   ├── README.md          # Project overview
│
│── .gitignore             # Files to ignore in Git
```

## Data Description
This project uses two datasets:

- **`country_indicators.csv`**: Contains various economic and social indicators for different countries.
- **`test_predictions.csv`**: Stores test predictions for multiple machine learning models.

## How to Run
To analyze the results, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/final-project-confidence-intervals.git
   cd final-project-confidence-intervals
   ```

2. **Open the Jupyter Notebook**:
   ```sh
   jupyter notebook notebooks/Markdown_Slides.ipynb
   ```

3. **Follow the analysis** inside the notebook.

## Requirements
Install the required libraries before running the notebook:
```sh
pip install pandas numpy matplotlib jupyter
```

## Notes
- This project is for **academic purposes**.
- The dataset may contain **missing values**, so preprocessing is required.
- The confidence interval analysis is performed on merged data from multiple sources.
- The **linear regression model** helps quantify the impact of different country indicators on predictions.

## License
*No license is provided for this project.*
