# World Bank Poverty Prediction Project

## Overview
This project analyzes World Bank household data to predict and understand poverty levels. Using machine learning and data analysis techniques, we explore the relationships between household features and poverty indicators.

## Objectives
- Analyze household characteristics and their correlation with poverty
- Build predictive models to identify poverty risk factors
- Extract meaningful insights from World Bank data
- Practice data science and machine learning workflows

## Project Structure
```
Worldbank-Project/
│
├── data/                          # Dataset files
│   ├── feature_descriptions.csv   # Descriptions of all features
│   ├── train_hh_features.csv      # Training household features
│   ├── test_hh_features.csv       # Test household features
│   ├── train_hh_gt.csv            # Training ground truth labels
│   └── train_rates_gt.csv         # Training rates ground truth
│
├── src/                           # Source code
│   └── (Python scripts and notebooks will go here)
│
├── docs/                          # Documentation
│   └── claude.md                  # AI assistant guidelines
│
├── .gitignore                     # Git ignore rules
├── requirements.txt               # Python dependencies
└── README.md                      # This file
```

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Git

### Installation
1. Clone this repository:
   ```bash
   git clone <your-repository-url>
   cd Worldbank-Project
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
(Instructions will be added as the project develops)

## Data Description
The dataset contains household-level features from World Bank surveys, including:
- Demographic information
- Economic indicators
- Infrastructure access
- Education levels
- And more (see `feature_descriptions.csv`)

## Results
(Analysis results and model performance will be documented here)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Data provided by the World Bank
- Project developed as part of data science learning