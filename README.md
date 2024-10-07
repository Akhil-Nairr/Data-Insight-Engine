# Data-Insight-Engine

## Overview
**Data Insight Engine** is a web application designed to simplify and streamline the process of Exploratory Data Analysis (EDA). It provides an intuitive interface where users can easily upload datasets, perform detailed analyses, and visualize results—all without needing to write any code. Built using [Streamlit](https://streamlit.io/), this app supports advanced analytics features like PCA and correlation analysis, as well as automated report generation using popular libraries like **ydata-profiling** and **Sweetviz**.

## Key Features
- **Automated Data Cleaning**: Detect and handle missing values and encoding issues in your dataset.
- **Interactive Visualizations**: Generate a variety of plots (scatter, box, heatmap, histogram) powered by Plotly.
- **Advanced Analytics**: Execute advanced statistical analysis such as PCA (Principal Component Analysis), correlation analysis, and outlier detection.
- **Automated Reporting**: Generate comprehensive EDA reports using **ydata-profiling** and **Sweetviz** libraries with just a click.
- **Feedback Form**: Collect feedback and suggestions directly from the users of the web app.

## Live Demo
Visit the live application [here](https://analyze-your-data.herokuapp.com/).
![image](https://github.com/user-attachments/assets/68d5b037-ce97-4be6-ba52-4ef4ffd9836f)


## Getting Started

### Prerequisites
- **Python 3.8** or higher
- **Git**
- It's recommended to use a **virtual environment**.

### Installation Guide (Mac OS)
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/data-insight-engine.git
   cd data-insight-engine
2. **Create and activate a virtual environment**:
   python3 -m venv venv
   source venv/bin/activate

3. **Install the required dependencies**:
   pip install -r requirements.txt

4. **Run the application**:
   streamlit run app.py

### Project Structure

data-insight-engine/
├── app.py               # Main app code
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation
└── assets/              # Static assets (if any)


### Technologies Used
**Streamlit**: Web app framework for building interactive UIs
**Pandas**, **NumPy**, **SciPy**, **Scikit-learn**: For data analysis and manipulation
**Plotly**: For interactive visualizations
**ydata-profiling**, **Sweetviz*8: To generate automated EDA reports
**Heroku**: For deployment of the app

### How to Use the App
1. **Upload a Dataset**
Upload CSV, Excel, JSON, or Parquet files.
2. **Perform EDA**
**Univariate Analysis**: Analyze individual variables with statistics, histograms, box plots, and more.
**Bivariate Analysis**: Explore relationships between pairs of variables, including scatter plots and correlation heatmaps.
**Advanced Analysis**: Run PCA for dimensionality reduction, create new features, and handle missing values.
3. **Generate Reports**
ydata-profiling and Sweetviz are used to create comprehensive, downloadable reports with a single click.




### Requirements
Here's a list of packages used in the project:

streamlit==1.39.0
pandas==2.2.3
numpy==2.1.2
matplotlib==3.9.2
seaborn==0.13.2
plotly==5.24.1
scipy==1.14.1
scikit-learn==1.5.2
ydata-profiling==4.10.0
sweetviz==2.3.1
pydantic==2.9.2
pydantic-settings==2.5.2
chardet==5.2.0
pillow==10.4.0
requests==2.32.3





