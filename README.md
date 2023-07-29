# aerofit_descriptive-stats-probability
performed descriptive stats and probability on a buisness case dataset from aerofit


## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The AeroFit Descriptive Statistics and Probability project focuses on exploring and analyzing data related to aerobics fitness exercises. This repository contains Jupyter notebooks and code for descriptive statistics and probability analysis on the AeroFit dataset.

## Objective
The main objectives of this project are:
- Perform descriptive statistics to understand the central tendencies and distributions of key variables.
- Apply probability concepts to model uncertainty and assess outcomes in the AeroFit dataset.
- Utilize data analysis techniques to gain insights into the fitness exercise patterns.

## Features
- Descriptive statistics for mean, median, mode, variance, and standard deviation.
- Probability calculations and simulations for different fitness scenarios.
- Data visualization to represent statistical results effectively.

## Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy

*(Feel free to add or modify the list of technologies based on the tools and libraries used in your project)*

## Installation
To run the AeroFit Descriptive Statistics and Probability notebooks locally, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/raghav1saboo/aerofit_descriptive-stats-probability.git
   ```

2. Navigate to the project directory:
   ```
   cd aerofit_descriptive-stats-probability
   ```

3. Install the required dependencies using the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open Jupyter Notebook to access the data analysis notebooks:
   ```
   jupyter notebook
   ```

2. In the Jupyter Notebook interface, navigate to the "notebooks" directory and open the desired notebook.

3. Run the code cells in the notebook to perform descriptive statistics and probability analysis on the AeroFit dataset.

*(If there are specific usage instructions or guidelines for your project, provide them here)*

## Dataset
Describe the AeroFit dataset used in this project. Mention its source, format, and any data preprocessing steps performed. You can also provide a link to the original dataset or mention how to obtain it.

## Notebooks
List the available Jupyter notebooks and their purposes. For example:
- `descriptive_statistics.ipynb`: Demonstrates descriptive statistics on the AeroFit dataset.
- `probability_analysis.ipynb`: Applies probability concepts to fitness exercise scenarios.

*(Add any additional notebooks relevant to your project)*

## Contributing
Contributions to this project are welcome. If you find any issues or have improvements to suggest, please feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
If you have any questions or need further assistance, you can reach me via email at [your_email@example.com](mailto:your_email@example.com).

*(Replace 'your_email@example.com' with your actual email address)*

---

You can copy and paste this template into a new file named "README.md" in the root of your "aerofit_descriptive-stats-probability" repository. Customize the content to match the specifics of your project, such as the objective, features, technologies used, dataset, notebooks, and contact details. Additionally, consider providing examples of visualizations or probability simulations from the notebooks to showcase the insights gained from the data analysis.

About Aerofit

Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.


Business Problem

The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.
Dataset

The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months. The dataset has the following features:

Dataset link: Aerofit_treadmill.csv

Product Purchased:	KP281, KP481, or KP781
Age:	In years
Gender:	Male/Female
Education:	In years
MaritalStatus:	Single or partnered
Usage:	The average number of times the customer plans to use the treadmill each week.
Income:	Annual income (in $)
Fitness:	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.
Miles:	The average number of miles the customer expects to walk/run each week
Product Portfolio:

The KP281 is an entry-level treadmill that sells for $1,500.
The KP481 is for mid-level runners that sell for $1,750.
The KP781 treadmill is having advanced features that sell for $2,500.
What good looks like?

Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset
Detect Outliers (using boxplot, “describe” method by checking the difference between mean and median)
Check if features like marital status, age have any effect on the product purchased (using countplot, histplots, boxplots etc)
Representing the marginal probability like - what percent of customers have purchased KP281, KP481, or KP781 in a table (can use pandas.crosstab here)
Check correlation among different factors using heat maps or pair plots.
With all the above steps you can answer questions like: What is the probability of a male customer buying a KP781 treadmill?
Customer Profiling - Categorization of users.
Probability- marginal, conditional probability.
Some recommendations and actionable insights, based on the inferences.
Later on, we will see more ways to do “customer segmentation”, but this case study in itself is relevant in some real-world scenarios.

