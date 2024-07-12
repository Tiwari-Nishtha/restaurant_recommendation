
# Restaurant Recommendation System

## Overview

This project implements a restaurant recommendation system based on user preferences using a content-based filtering approach. The system preprocesses the dataset by handling missing values and encoding categorical variables. It then recommends restaurants that match the user's preferred criteria, such as cuisine preference, price range, location, and user ratings.

## Features

- **Data Preprocessing**: Handles missing values and encodes categorical variables.
- **Content-Based Filtering**: Recommends restaurants similar to user preferences.
- **Customizable Criteria**: Allows recommendations based on cuisine type, price range, location, and user ratings.
- **Evaluation**: Tests the recommendation quality using sample user preferences.

## Dataset

The dataset includes information about various restaurants, such as:

- Restaurant Name
- Cuisine Type
- Price Range
- Location
- User Ratings
- Ambiance
- Additional features (if any)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/restaurant-recommendation-system.git
   cd restaurant-recommendation-system
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Preprocess the Dataset**: Preprocess the dataset to handle missing values and encode categorical variables.

2. **Implement the Recommendation System**: Use the content-based filtering approach to recommend restaurants based on user preferences.

3. **Test the System**: Provide sample user preferences and evaluate the quality of recommendations.



## Evaluation

The system is evaluated by testing the recommendations against a set of sample user preferences. The quality of the recommendations can be assessed based on how well they match the user's criteria and preferences.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License. 

