# Cleaning-and-Preprocessing-FIFA-2021-Player-Data

## Introduction
Welcome to the GitHub repository for the Cleaning and Preprocessing FIFA 2021 Player Data project. As a data analyst, I embarked on a fascinating journey to transform a raw and messy dataset of FIFA 2021 player information into a clean and structured format, ready for analysis and visualization. This repository showcases the code, techniques, and steps I took to achieve this goal.

![f7503bfbd076bcb69f0957343c00be42da8f388d](https://github.com/S-Tanwar/Cleaning-and-Preprocessing-FIFA-2021-Player-Data-/assets/95356553/0a32b5b4-ea0c-4d65-883e-98f2f426d432)

## The Goal
The primary goal of this project was to prepare the FIFA 2021 player dataset for analysis and visualization. The dataset contained a wealth of information, including player attributes, gameplay statistics, and personal details. However, before diving into deeper insights, it was essential to address issues such as missing values, inconsistent units, and non-numeric data.

## Project Highlights
### Data Cleaning Steps
1. **Handling Missing Values**: I began by checking for missing values in the dataset using pandas. Fortunately, there were no missing values, ensuring a solid foundation for further cleaning and analysis.

2. **Dropping Unnecessary Columns**: To streamline the dataset, I removed two columns, 'photoUrl' and 'playerUrl', which contained URLs to player photos and profiles. These columns were not relevant to the analysis.

3. **Renaming Columns**: I renamed the '↓OVA' column to 'OVA' for clarity, representing the Overall Attribute of the players.

4. **Units and Conversions**: To ensure consistency, I converted units in columns such as 'Height', 'Weight', 'Value', and 'Wage'. Heights were converted to centimeters, weights to kilograms, and monetary values to euros.

5. **Cleaning Categorical Columns**: I cleaned categorical columns like 'W/F' (Weak Foot), 'SM' (Skill Moves), 'A/W' (Attack/Work Rate), and 'IR' (International Reputation). I removed special characters and converted text values to numeric format.

6. **Cleaning Numeric Columns**: Basic data cleaning was performed on numeric columns, removing extraneous characters and ensuring data accuracy.

7. **Handling 'Hits' Column**: The 'Hits' column contained 'K' to represent thousands. I converted these values to integers for consistency.

8. **Final Touches**: After transformations, I dropped additional irrelevant columns to create a focused and meaningful dataset.

### Code and Resources
The Python code used for data cleaning, transformation, and preprocessing can be found in this repository . The notebook provides detailed explanations of each step, making it easy to follow along and replicate the process.

Repository Structure
This repository is organized as follows:

readme/: Contains the detailed data cleaning and preprocessing steps.

data/: Includes the raw dataset link, fifa21_raw_data.csv, used for the project.

code/: Cantain relevant code for running this project.


## Conclusion
This GitHub repository showcases how I transformed a complex and untidy FIFA 2021 player dataset into a clean and structured format, ready for analysis. By addressing issues like missing values, inconsistent units, and non-numeric data, I created a dataset that serves as a solid foundation for exploring insightful trends and patterns.

Feel free to explore the code, dive into the Jupyter Notebook, and adapt the techniques for your own data cleaning projects. Your feedback, suggestions, and contributions are highly encouraged and appreciated.

Happy exploring and analyzing!

For a more comprehensive view of this project, you can also visit the Medium blog post associated with this project.
