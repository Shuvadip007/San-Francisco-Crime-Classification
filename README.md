# San Francisco Crime Classification

## Overview
From 1934 to 1963, San Francisco was infamous for housing some of the world's most notorious criminals on the inescapable island of Alcatraz.

Today, the city is known more for its tech scene than its criminal past. But, with rising wealth inequality, housing shortages, and a proliferation of expensive digital toys riding BART to work, there is no scarcity of crime in the city by the bay.

From Sunset to SOMA, and Marina to Excelsior, this dataset provides nearly 12 years of crime reports from across all of San Francisco's neighborhoods. Given time and location, the goal is to predict the category of crime that occurred.

We're also encouraging exploration of the dataset visually. What can we learn about the city through visualizations like the Top Crimes Map?

## Dataset
- **Source:** The dataset consists of historical crime reports in San Francisco.
- **Features:** Includes timestamp (`Dates`), location coordinates (`X`, `Y`), and crime category (`Category`).
- **Preprocessing:** Handling missing values, removing duplicates, and filtering out incorrect location data.

## Installation
To run this project, install the necessary Python libraries:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sf-crime-classification.git
   ```
2. Navigate to the project folder:
   ```bash
   cd sf-crime-classification
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook San_Francisco_Crime_Classification.ipynb
   ```

## Machine Learning Approach
- **Model Used:** Logistic Regression
- **Preprocessing:** Standard scaling, ordinal encoding
- **Pipeline:** Using `sklearn.pipeline` for data transformation and model training
- **Evaluation:** Model performance analysis through accuracy and classification metrics

## Results & Insights
- The dataset contains multiple crime categories, with some occurring more frequently than others.
- Location coordinates play a crucial role in classification, helping to identify crime-prone areas.
- Logistic regression provides an initial baseline model, and further improvements can be made using advanced ML techniques.

## Contributing
Feel free to open issues or submit pull requests to improve this project.

## License
This project is open-source and available under the [MIT License](LICENSE).

