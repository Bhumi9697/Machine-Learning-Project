# Flight Delay Prediction Project

This project aims to predict flight arrival times into Syracuse (SYR) from four different cities and categorize them as early, on-time, delayed, or severely delayed up to four days in advance. It utilizes historical flight data and incorporates weather forecasts as one of the factors affecting flight delays.

## Table of Contents

- [Project Overview](#project-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Preprocessing](#preprocessing)
- [Results and Discussions](#results-and-discussions)
- [Conclusion](#conclusion)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The primary objective of this project is to build a predictive model for flight arrival times into SYR. The project includes the following phases:

- **Exploratory Data Analysis:** We collected and cleaned historical flight data from "https://www.transtats.bts.gov/ontime/" to prepare it for analysis.

- **Preprocessing:** We performed data preprocessing, including feature extraction and merging weather data to enhance our dataset's quality.

- **Model Selection:** We tested various machine learning algorithms, with the Random Forest Regressor emerging as the most effective model for predicting flight delays.

## Exploratory Data Analysis

The EDA phase involved data collection, cleaning, and initial analysis. We focused on understanding the dataset's structure and identifying missing values.

## Preprocessing

In the preprocessing phase, we prepared the data for modeling. This included data cleaning, feature engineering, and the incorporation of weather data.

## Results and Discussions

We compared various machine learning models and found that the Random Forest Regressor outperformed others, achieving an R-Squared score of 0.83 and a Mean Absolute Error (MAE) of 40.39.

## Conclusion

Our project demonstrates the effectiveness of combining historical flight data with weather forecasts to predict flight delays accurately. The Random Forest Regressor model provides valuable insights into the likelihood of flight delays.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries listed in the `requirements.txt` file.
3. Run the Jupyter notebooks in the `notebooks` directory to reproduce the analysis and model training.

## Contributing

We welcome contributions from the open-source community. If you'd like to contribute, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
