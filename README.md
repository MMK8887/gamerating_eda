# 🎮 Analysis of Game Ratings Data

This project performs a comprehensive **data analysis and machine learning workflow** on a game ratings dataset.  
It covers **data cleaning, exploratory data analysis (EDA), and insights** into patterns across genres and developers.  

---

## 📂 Project Structure

### Part 1: Project Setup and Data Loading
- Imported libraries: `pandas`, `seaborn`, `matplotlib`, and `scikit-learn`.
- Loaded the dataset `game_ratings.csv` into a pandas DataFrame.
- Dataset overview:
  - **101 entries**  
  - **4 columns**: `Game Name`, `Developer`, `Genre`, `Rating`

### Part 2: Data Cleaning and Preprocessing
- Checked for missing values → **None found** ✅  
- Checked for duplicate rows → **None found** ✅  
- Data is clean and ready for analysis.  

### Part 3: Exploratory Data Analysis (EDA) and Visualization
We explored the dataset through **statistical summaries and visualizations**:

#### 📊 Descriptive Statistics of Ratings
- Ratings range: **4.1 – 4.9**  
- Mean: **4.40**, Median: **4.40**, Std. Dev.: **0.175**  
- Boxplot & histogram confirm most ratings cluster around **4.3–4.6**  

#### 🎭 Genre Analysis
- **Most frequent genre**: Strategy (**17 games**)  
- Simulation (**14 games**) and Puzzle (**13 games**) follow closely.  
- **Highest avg. rating**: Sandbox & Action RPG (**4.65**)  
- **Lowest avg. rating**: Card (**4.1**)  

#### 🏆 Top and Bottom Rated Games
- **Top 5 games**:  
  - *Hades (4.9)*, *Minecraft (4.8)*, *Monument Valley (4.8)*, *The Room (4.8)*  
- **Bottom 5 games**:  
  - *Fortnite (4.1)*, *Hearthstone (4.1)*, *State of Survival (4.1)*, *Clash of Kings (4.1)*, *Forge of Empires (4.1)*  

#### 🏢 Developer Analysis
- **Supercell**: 5 games (most prolific)  
- **Electronic Arts**: 4 games  
- **Rovio Entertainment**: 3 games  
- Most developers: only **1 game** each  

---

## 📌 Key Insights
- Ratings are **consistently high**, with a slight skew towards **4.4**.  
- **Strategy** is the most common genre, but **Sandbox & Action RPG** perform best in terms of ratings.  
- Developers like **Supercell** and **Electronic Arts** dominate in terms of game count.  
- Certain genres (e.g., Card, MOBA, Battle Royale) tend to have **lower ratings**.  

---

## 🚀 Future Work
- Build **predictive models** to forecast ratings based on features.  
- Extend dataset with **user reviews, release year, and platform data**.  
- Perform **time-series analysis** of rating trends across years.  

---

## 📎 Dataset
The dataset `game_ratings.csv` contains:
- `Game Name` → Title of the game  
- `Developer` → Studio/creator of the game  
- `Genre` → Category (e.g., Strategy, RPG, Puzzle)  
- `Rating` → Average player rating (scale 1–5)  

---

## 🛠️ Tech Stack
- **Python** 🐍  
- **Pandas / NumPy** → Data handling  
- **Seaborn / Matplotlib** → Visualization  

---

## 👨‍💻 Authors
MANISH M KUMAR  

