# Eco-Tourism Analysis with Primary Data

> 📊 An in-depth analysis of traveler survey data to uncover patterns, preferences, and perceptions related to sustainable and responsible tourism.

<p align="center">
  <img alt="Language" src="https://img.shields.io/github/languages/top/jeno22ndr/Eco-Tourism-Analysis-with-primary-data?style=for-the-badge">
  <img alt="Last Commit" src="https://img.shields.io/github/last-commit/jeno22ndr/Eco-Tourism-Analysis-with-primary-data?style=for-the-badge&color=blue">
  <img alt="Repo Stars" src="https://img.shields.io/github/stars/jeno22ndr/Eco-Tourism-Analysis-with-primary-data?style=for-the-badge&color=yellow">
  <a href="https://github.com/jeno22ndr/Eco-Tourism-Analysis-with-primary-data/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/jeno22ndr/Eco-Tourism-Analysis-with-primary-data?style=for-the-badge">
  </a>
</p>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-overview">Project Overview</a></li>
    <li><a href="#objective">Objective</a></li>
    <li><a href="#key-analysis-highlights">Key Analysis Highlights</a></li>
    <li><a href="#datasets-used">Datasets Used</a></li>
    <li><a href="#tools-and-technologies">Tools and Technologies</a></li>
    <li><a href="#how-to-run-the-analysis">How to Run the Analysis</a></li>
    <li><a href="#repository-structure">Repository Structure</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

---

## Project Overview

This project delves into primary survey data collected on eco-tourism. The goal is to apply data analysis techniques to understand the key factors that influence travelers' decisions, their awareness of sustainability, and their on-trip behaviors. By transforming raw survey responses into actionable insights, this analysis aims to provide a clearer picture of the modern eco-tourist and offer data-driven recommendations for promoting responsible travel.

![Key Visualization from Analysis](./key_visualisation.png)

## Objective

The primary objectives of this analysis are to:
1.  **Identify demographic profiles** of travelers interested in eco-tourism.
2.  **Analyze key preferences** for activities, accommodations, and destinations.
3.  **Measure the level of environmental awareness** and its impact on travel choices.
4.  **Uncover behavioral patterns** that can help stakeholders promote more sustainable tourism practices.

## Key Analysis Highlights

This notebook explores several facets of the survey data, including:
* **Demographic Breakdown:** Analysis of age, gender, and location of respondents.
* **Travel Motivation:** What drives people to choose eco-tourism over conventional travel?
* **Willingness to Pay:** How much more are travelers willing to pay for sustainable options?
* **Information Sources:** Where do travelers get their information about eco-friendly travel?
* **[Add another key finding from your analysis]**

## Datasets Used

* `Book1.xlsx`: The raw, primary survey data collected from respondents.
* `synthetic_combined_data.csv`: The cleaned, processed, and potentially augmented dataset used for the final analysis in the notebook. This file is the result of the initial data processing steps.

## Tools and Technologies

* **Language:** Python 3.x
* **Libraries:**
    * **Pandas:** For data manipulation and analysis.
    * **NumPy:** For numerical operations.
    * **Matplotlib & Seaborn:** For data visualization.
    * **Scikit-learn:** For any machine learning or modeling tasks.
* **Environment:** Google Colab / Jupyter Notebook

## How to Run the Analysis

To reproduce the analysis on your local machine, follow these steps:

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/jeno22ndr/Eco-Tourism-Analysis-with-primary-data.git](https://github.com/jeno22ndr/Eco-Tourism-Analysis-with-primary-data.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Eco-Tourism-Analysis-with-primary-data
    ```
3.  **Set up a virtual environment (recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4.  **Install the required libraries.**
    *(💡 Tip: It's best practice to create a `requirements.txt` file by running `pip freeze > requirements.txt` in your terminal and committing it to the repo.)*
    ```sh
    pip install pandas numpy matplotlib seaborn jupyterlab
    ```
5.  **Launch Jupyter Notebook or Jupyter Lab:**
    ```sh
    jupyter lab
    ```
6.  **Open and run the notebook:**
    Open the `Data_Generation.ipynb` file and execute the cells.

## Repository Structure
├── Book1.xlsx                  # Raw primary survey data

├── Data_Generation.ipynb       # Jupyter Notebook with the full analysis

├── README.md                   # You are here!

└── synthetic_combined_data.csv # Processed dataset for analysis

## License

Distributed under the MIT License. See `LICENSE` file for more information. 

## Contact

Jeno - [jeno22ndr@gmail.com](mailto:jeno22ndr@gmail.com)

Project Link: [https://github.com/jeno22ndr/Eco-Tourism-Analysis-with-primary-data](https://github.com/jeno22ndr/Eco-Tourism-Analysis-with-primary-data)
