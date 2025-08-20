A complete data analysis and machine learning for game ratings data 🎮
This project performs a comprehensive data analysis and machine learning workflow on a game ratings dataset. It covers data cleaning, exploratory data analysis (EDA), and building a predictive model to understand and predict game ratings based on various features.

Project Structure
Part 1: Project Setup and Data Loading: The necessary libraries like pandas, seaborn, matplotlib.pyplot, and scikit-learn are imported. The game_ratings.csv dataset is loaded into a pandas DataFrame. The initial DataFrame information is printed, showing 101 entries and 4 columns: Game Name, Developer, Genre, and Rating.

Part 2: Data Cleaning and Preprocessing: The dataset is checked for missing values and duplicates. The output confirms there are no missing values or duplicate rows, indicating a clean dataset ready for analysis.

Part 3: Exploratory Data Analysis (EDA) and Visualization: This section focuses on understanding the data through statistical summaries and visualizations.

A descriptive summary of the Rating column is provided. The ratings range from 4.10 to 4.90, with a mean of 4.40.

A histogram visualizes the distribution of ratings, showing that most games in the dataset are highly rated, with a peak around 4.4.

A bar chart displays the number of games per genre, highlighting Action and Adventure as the most frequent genres.

Another bar chart shows the average rating per genre, revealing that Role-Playing games have the highest average rating in this dataset.

Part 4: Feature Engineering for Machine Learning: Categorical variables (Genre and Developer) are converted into a numerical format using one-hot encoding. This process creates a new feature set with 103 columns, which is necessary for training the machine learning model.

Part 5: Model Building and Evaluation:

Data Split: The data is split into training (80 samples) and testing (21 samples) sets to train and evaluate the model's performance on unseen data.

Model Training: A RandomForestRegressor is initialized and trained on the training data.

Model Evaluation: The model's performance is measured using Mean Absolute Error (MAE) and R-squared (R²). The MAE is 0.14, meaning the average prediction is off by 0.14 points. The R-squared value is 0.09, which is a low score, suggesting that the selected features (Genre and Developer) do not effectively predict the game's rating, and the model only explains 9% of the variance in ratings.