# recommendation_engine_system
Built a collaborative filtering recommendation system for Netflix movies using Pandas and Scikit-Surprise. Analyzed 100M+ ratings, applied Singular Value Decomposition, and achieved personalized movie suggestions
# Netflix Movie Recommender Project

## Overview
This project is a comprehensive exploration and implementation of a recommendation system for Netflix movies, leveraging the Netflix Prize dataset. With over 100 million ratings from 480,000 users on 4,499 movies, the system utilizes collaborative filtering techniques, specifically Singular Value Decomposition (SVD), to provide personalized movie suggestions based on user preferences.

## Code Structure
- The project code is organized into several Python scripts within the `Code` directory for modularity and clarity.
- Each script addresses specific aspects of the project, such as data preprocessing, exploratory data analysis (EDA), and modeling using SVD.

## Key Components

### 1. Data Preprocessing (`preprocess_data.py`)
- The dataset underwent thorough cleaning to handle missing values, and inactive users and less-rated movies were filtered out.
- Data was organized to ensure a solid foundation for subsequent analysis.

### 2. Exploratory Data Analysis (`eda.py`)
- Extensive data visualization was performed to understand the distribution of ratings, identify patterns, and gain insights into user behavior.
- Visualizations created using Matplotlib showcased key trends in the dataset.

### 3. Matrix Factorization with SVD (`svd_model.py`)
- Applied Singular Value Decomposition (SVD) to factorize the user-item interaction matrix.
- Extracted latent features to enhance the accuracy of personalized movie recommendations.

## Model Evaluation (`evaluate_model.py`)
- Rigorous model evaluation was conducted through cross-validation, measuring Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).
- This step ensured the reliability and effectiveness of the recommendation system.

## Google Colab Notebooks
- Explore the `Google Colab Notebooks` directory for a step-by-step walkthrough of the analysis conducted in Google Colab.

## Getting Started
1. **Explore Google Colab Notebooks for detailed analysis.**
   - Open and run the notebooks in Google Colab for an interactive analysis experience.

2. **Review Python scripts for individual components.**
   - Examine the scripts within the `Code` directory to understand the implementation details.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-Surprise

## License
This project is licensed under the [MIT License](LICENSE.md).

## Project Structure
- `Code`: Organized Python scripts for preprocessing, EDA, and modeling.
- `Jupyter Notebooks`: Step-by-step analysis in interactive notebooks.
- `Data`: Link to the Netflix Prize dataset or instructions to obtain it.
- `Documentation`: Additional project reports, presentations, or related documents.

