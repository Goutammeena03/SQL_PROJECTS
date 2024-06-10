# 📊 Restaurant Anlysis Using Yelp Dataset

Welcome to the analysis of factors influencing restaurant success using the Yelp dataset. This project aims to uncover the relationship between user engagement (reviews, tips, and check-ins) and business success metrics (review count, ratings) for restaurants.

## 📈 Project Overview

In a competitive market like the restaurant industry, understanding the factors that drive business success is crucial for stakeholders. Utilizing the Yelp dataset, this project investigates how user engagement correlates with restaurant success metrics. 

### Key Findings
- **General Trends**:
  - Out of 150k businesses, 35k are open restaurant businesses.
  - There is an increase in average reviews, check-ins, and tip counts as ratings increase from 1 to 4 stars.
  - Restaurants rated 4 stars show the highest engagement, with a decrease in engagement for ratings above 4 stars.
  
- **Correlations**:
  - User engagement across different platforms (reviews, tips, check-ins) is interconnected.
  - Higher ratings are associated with increased user engagement in reviews, tips, and check-ins.

- **Top Performing Cities**:
  - Philadelphia, Tampa, Indianapolis, and Tucson rank among the top cities with significant success scores.

- **User Reviews**:
  - Higher counts of useful, funny, and cool reviews indicate greater user engagement and satisfaction.

- **Elite Users**:
  - Elite users play a crucial role in business success. Establishing positive relationships with elite users can lead to repeat visits and loyalty.

- **Peak Hours**:
  - The busiest hours for restaurants, based on user engagement, span from 4 PM to 1 AM.

## 📊 Data Analysis

The analysis is conducted using various Python libraries for data processing and visualization. The key steps involved are:
1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Correlation Analysis
4. Visualization of Key Metrics

## 🛠️ Installation

To run this analysis locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Goutammeena03/Restaurant-Analysis-with-Yelp-Data.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Restaurant-Analysis-with-Yelp-Data
    ```
3. Create a virtual environment:
    ```bash
    python -m venv env
    ```
4. Activate the virtual environment:
    - On Windows:
      ```bash
      .\env\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source env/bin/activate
      ```
5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 📚 Usage

To perform the analysis, run the Jupyter notebooks provided in the `notebooks` directory. Each notebook covers different aspects of the analysis:
- `work.ipynb` - Data cleaning and preparation, Exploratory Data Analysis ,Correlation analysis between user engagement and success metrics, Visualizations of the key findings

## 🤝 Acknowledgements

A big thank you to Ayushi Mishra for her insightful tutorials, which were instrumental in guiding this analysis.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📫 Contact

For any questions or suggestions, please contact [Your Name](mailto:your-email@example.com).

