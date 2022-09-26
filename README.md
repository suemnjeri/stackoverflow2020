# Analysis of the stackoverflow survey 2020 dataset.

 ### [Blog post on medium](https://towardsdatascience.com/this-data-answers-the-am-i-too-old-to-learn-coding-timeless-question-70deba5d294f)

## Installation
Python is required to run the code. The basic packages that come woth the Anaconda distribution are sufficient for this project. All python files are created and run in a Jupyter notebook.

## Motivation
From this dataset, I set out to answer 3 questions.
1. Can someone be too old to learn coding?
2. What are some factors that contribute to starting late to code?
3. What are some common effects of people who started coding late (from 30 years old)

## File descriptions

The complete workflow for the project is contained in the [Full CRISP-DM stackoverflow 2020.ipynb](https://github.com/suemnjeri/stackoverflow2020/blob/master/Full%20CRISP-DM%20stackoverflow%202020.ipynb) jupyter notebook.
There are also 2 .csv files in this folder. These are 'survey_results_public.csv' (the original stackoverflow dataset) and 'survey_results_public.csv' (created in Part 3 explained below) which are both used in this notebook.

For indepth EDA, cleaning, feature engineering and analysis, check out the notebooks contained in the ['Detailed workings'](https://github.com/suemnjeri/stackoverflow2020/tree/master/Detailed%20workings) folder.
The code in the 'Detailed workings' folder is contained in four notebooks from Part 1 to part 4.

These parts represent my workflow for data exploration, cleaning, analysing and visualizing the results.
- Part 1: Performed basic EDA on the full dataset. I also split the devtypes per person into their own separate columns.
- Part 2: Cleaned the dataset by removing rows where 'Age' (and other essential age related fields) were missing.
- Part 3: Added a regions/continent column and mapped countries to their regions. This is a short notebook.
- Part 4: Performed final analysis, cleaning and visualizations that are included in the medium article.

The .csv files that start with 'SO' are created in the jupyter notebooks as part of the workflow. 
The last part of each csv filename shows the part of the project that it is created in (eg -part1.csv), and this will be passed on and used in the next part notebook  (eg Part 2..).
The 'regions countries.csv' is used in 'Part 3' notebook.

The files in the ['Original stackoverflow files'](https://github.com/suemnjeri/stackoverflow2020/tree/master/Original%20stackoverflow%20files) folder were the original files downloaded from the stackoverflow website, excluding the dataset which is in the base folder.


## Findings
The results and visualizations are well documented in [this medium post](https://towardsdatascience.com/this-data-answers-the-am-i-too-old-to-learn-coding-timeless-question-70deba5d294f?sk=7c46f9ceee19d552704fbf3e28ff40ec).

## Licensing, Authors, Acknowledgements
This project was made possible because of the data provided by stackoverflow. Find the the 2020 dataset along with those from other years here [here](https://insights.stackoverflow.com/survey).
