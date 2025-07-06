# Airbnb NYC Data Analysis

This project analyzes the Airbnb listings in New York City to understand the factors that influence listing prices. Using a dataset of over 50,000 listings, this analysis uses various data science techniques to model and visualize the data, uncovering key insights into the NYC short-term rental market. 🗽

## 📊 Dataset

The data for this analysis is from Kaggle's [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). This dataset includes information on listings from 2019, including:

  * **Location**: Neighborhood and borough
  * **Price**: Price per night
  * **Room Type**: Entire home/apt, private room, or shared room
  * **Reviews**: Number of reviews and reviews per month
  * **Availability**: Number of days available for booking in a year

## 🚀 Project Goals

The main goals of this project are:

  * To perform exploratory data analysis to understand the distribution of Airbnb listings and prices across NYC.
  * To identify the key factors that affect the price of a listing.
  * To build a model that can predict the price of a listing based on its features.
  * To visualize the data and findings in an accessible and informative way.

## 🛠️ Tech Stack

This project is implemented using Python in a Jupyter Notebook. The main libraries used are:

  * **Pandas**: For data manipulation and analysis.
  * **NumPy**: For numerical operations.
  * **Matplotlib & Seaborn**: For data visualization.
  * **Scikit-learn**: For machine learning and modeling.

## ⚙️ How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MatteoPedranzini/Airbnb-NYC-Data-Analysis.git
    ```
2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook "Airbnb NYC Data Analysis.ipynb"
    ```

## 📈 Key Findings

The analysis of the data revealed several key insights:

  * **Location is a major price driver**: Listings in **Manhattan** are significantly more expensive than in other boroughs.
  * **Room type matters**: **Entire homes/apartments** are the most expensive, followed by private rooms and then shared rooms.
  * **There are distinct customer clusters**: Based on price and room type, we can identify different groups of Airbnb customers.

## 🤝 Contributing

Contributions are welcome\! If you have any suggestions or find any issues, please open an issue or submit a pull request.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
