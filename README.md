# Netflix Content Type Classifier

This project analyzes Netflix's content dataset to build a machine learning model that classifies content into **Movies** or **TV Shows** based on various features like rating, country, content age, duration, and more.

---

## Project Overview

Streaming platforms like Netflix host vast libraries of content. This project uses data analysis and machine learning to better understand and predict the type of content, providing useful insights for content recommendation, marketing, and business strategy.

---

## Project Steps

### Step 1: Load Data and Inspect
- Load the dataset and explore its basic structure, shape, and data types.

### Step 2: Check and Handle Missing Values
- Visualize missing data using heatmaps and bar charts.
- Handle missing values with strategies like filling with 'Not Available', mode, or 'Unknown'.

### Step 3: Data Preprocessing (Convert, Clean, and Extract)
- Convert date fields to datetime objects.
- Extract year and month added.
- Split duration into numeric and unit components for better analysis.

### Step 4: Exploratory Data Analysis (EDA)
- Visualize content distribution by type, release year, country, and popular genres.
- Gain insights into trends and content patterns on Netflix.

### Step 5: Feature Engineering & Transformation
- Encode categorical features.
- Create new features to improve model performance.

### Step 6: Model Building and Evaluation
- Train machine learning models (Random Forest, XGBoost) to classify content type.
- Evaluate models using accuracy, precision, recall, and confusion matrix.

### Step 7: Model Improvement and Hyperparameter Tuning
- Use GridSearchCV to optimize Random Forest hyperparameters.
- Train XGBoost classifier and analyze feature importance.

---

## Key Results

- Achieved near-perfect accuracy (~100%) on test data for classifying Netflix content type.
- Identified **duration**, **country**, **rating**, and **content age** as the most influential features for prediction.
- Visualized feature importances and confusion matrices to interpret model performance.

---

## What We Learned

- How to handle missing data strategically to preserve information.
- Importance of detailed preprocessing to prepare real-world datasets for ML.
- Techniques for exploratory data analysis to understand data patterns.
- How to build, tune, and interpret classification models using Random Forest and XGBoost.
- Insight into which content features affect classification the most.

---

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/netflix-content-type-classifier.git
    ```

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook netflix_EDA.ipynb
    ```

---

## Dataset

The Netflix dataset used in this project contains information about movies and TV shows available on Netflix, including metadata like director, cast, country, rating, and more.

---

## Technologies & Libraries Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Random Forest, GridSearchCV)
- XGBoost
- Jupyter Notebook

---

## Author

Tushar Ahlawat  
Email: tusharahlawat161@example.com  
LinkedIn: [linkedin.com/in/tusharahlawat](www.linkedin.com/in/tushar-ahlawat-26b555268)  


---

Feel free to reach out if you have any questions or want to collaborate!
