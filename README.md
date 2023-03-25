# Analysis of Hotel Bookings

## INTRODUCTION
We analysed the hotel booking data for a given company. Our aim was to enable the company to make informed decisions about marketing, leading to increased revenue. The company has two kinds of hotel: city and resort hotels. We were provided with bookings data collected from 2015 to 2017.
To make suggestions about targeted marketing, we came up with 5 questions that were answered with the data. The questions are:
1. What is the distribution of the average daily rate for each hotel type?
2. Which hotel type is mostly booked and then occupied?
3. Which months are the hotels mostly occupied?
4. Where do most of the guests come from?
5. Are the guests usually families or individuals?
The first three questions helped with determining the hotel type to be emphasised in the marketing campaign as well as the best time to carry out the campaign while the last two questions helped determine the company’s target audience.

## IMPLEMENTATION AND EXECUTION
We created python scripts for each stage of the analysis i.e preprocessing.py, utils.py, analysis.py, and workflow.py.

Cleaning functions were defined in the **preprocessing.py**, the script was then imported into the **workflow.py** for the changes to be applied to the data.

Unlike the preprocessing, two scripts were used for the analysis. An **utils.py** which contained methods defined under a given class, each class was specific to an analysis question listed above. Then an **analysis.py** in which the classes from utils were imported and the methods applied. 

The **workflow.py** combined the processes from **preprocessing.py** and **analysis.py** to generate plots and summarised datasets which answered the analysis questions.


A detailed project report can be found in the repository.
