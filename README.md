# Fake News Detection

This project is focused on identifying whether a news article is **Fake** or **Real** using Python and machine learning techniques. It utilizes datasets of news articles and employs data preprocessing, visualization, and machine learning algorithms to classify articles effectively.

The project starts with data loading and exploration, where datasets named `Fake.csv` and `True.csv` are analyzed. These datasets contain fake and true news articles, respectively. Using libraries like `pandas` and `numpy`, the data is preprocessed to handle inconsistencies, remove irrelevant information, and prepare it for analysis. Visualization tools like `seaborn` and `matplotlib` are used to understand the distribution of the data, such as the count of fake versus real news articles.

The classification task is performed using Scikit-learn, which includes splitting the dataset into training and testing subsets, building a machine learning model, and evaluating it. Metrics like accuracy and classification reports are used to measure performance. The project aims to provide an easy-to-follow workflow that starts with raw data and ends with actionable insights.

To run this project, you need the following Python libraries installed:
- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `seaborn` and `matplotlib` for visualization.
- `scikit-learn` for machine learning.

Start by cloning the repository and setting up the environment:
1. Clone the repository using `git clone https://github.com/kaustubhk134/Fake_News_Detection_ML.git` and navigate into it.
2. Install the required libraries with `pip install -r requirements.txt`.
3. Place the `Fake.csv` and `True.csv` datasets in the project directory.

To execute the project:
1. Open the `Fake_News_Detection.ipynb` file in Jupyter Notebook.
2. Execute each cell to:
   - Load and preprocess the data.
   - Visualize the fake and real news distribution.
   - Train a classification model and evaluate its performance.

This project is a comprehensive pipeline for detecting fake news and includes all steps from data preparation to result visualization. It also provides useful insights into the challenges of dealing with textual data and the effectiveness of machine learning in classification tasks.

Feel free to fork my repository and contribute to the project. This project is licensed under the MIT License.
