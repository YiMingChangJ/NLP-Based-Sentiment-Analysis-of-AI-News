# RAISE-25 Competition: AI's Impact on Education, Careers, and Society

## Overview
This project was developed for the RAISE-25 competition hosted by Rutgers Bloustein MPI. The competition focuses on analyzing news headlines to explore AI's impact on education, careers, and society. The analysis involves natural language processing (NLP), data visualization, and machine learning techniques to extract meaningful insights from text data.

## Features
- **Data Collection & Cleaning**: Preprocessing of news headlines to remove noise and standardize text for analysis.
- **Exploratory Data Analysis (EDA)**: Statistical analysis and visualization of word frequencies, trends, and sentiment distributions.
- **Sentiment Analysis**: Classification of headlines into positive, negative, and neutral sentiments using NLP models.
- **Topic Modeling**: Identification of recurring themes and discussions using Latent Dirichlet Allocation (LDA) and other clustering techniques.
- **Visualization**: Graphical representation of sentiment trends, word clouds, and topic distributions.

## Technologies Used
- **Python**: Primary programming language
- **NLTK / spaCy**: Natural language processing
- **scikit-learn**: Machine learning models and text vectorization
- **Matplotlib / Seaborn / Plotly**: Data visualization
- **Pandas / NumPy**: Data manipulation and statistical analysis
- **WordCloud**: Visualization of text-based data

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/RAISE-25-Competition.git
   cd RAISE-25-Competition
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv env
   source env/bin/activate  # On macOS/Linux
   env\Scripts\activate  # On Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the analysis:
   ```sh
   python main.py
   ```

## Usage
- Modify the `config.json` file to change data sources or parameters.
- Run `notebooks/EDA.ipynb` to explore the dataset.
- Use `sentiment_analysis.py` to classify headlines based on sentiment.
- Execute `topic_modeling.py` to extract key topics from the dataset.

## Results
Key findings and visualizations are stored in the `results/` directory. These include sentiment distributions, topic word clouds, and statistical summaries.

## Contributing
Pull requests are welcome! If you have suggestions for improvements or additional features, feel free to submit an issue or fork the repository.

## Acknowledgments
- Rutgers Bloustein MPI for organizing the competition.
- Open-source NLP and data science communities for tools and resources.

---
Feel free to modify the content to match your project's structure and findings!

