# Classifying Six Figures in Malpractice Payments

## The problem:

The NPDB, the National Practitioner Data Bank, has public data avaible [here](https://www.npdb.hrsa.gov/resources/publicData.jsp) on malpratice payments. The objective of this project is to classify 
payment that are under, over, or exactly six-figure payments. 

## Solution

After trying decision tree and Logistic regression models. A tuned logistic regression model got the best accuracy at about 68%

## Recomendtions:
   - If you are a malpratice insurce company look into spending more in advertising in New York, and illinois. According to our model thoes states tend to a have higher than a six-figures malpratice settlements. You can pull funding from advertising in Puerto Rico and to advertising to dentist, since those payments tend to be smaller than six-figures according to the model. 

   - As lawyer, as you may expect, outcome is the most important factor it worth focusing on that when coming to a decision of giving a six-figure settlment or something higher or lower than that. The more server the higher the outcome (1-9).
   
## What is next
   - An EDA to fine tune the recomendtions.
   - Maybe try a regression models, but use the classifier methods since the numerical data is encoded,for example PRACTAGE, PTAGE does not give the age of the practitioner or patient respectively rather an age group they belong to. On top of that over half of the data is categorical making hard of tradional regression to work properly.

## The main points
If the read me is not enough, you can look the slides [here](https://github.com/S-boker/Classifying-six-figures-in-malpractice-payments-/blob/main/Making%20Six-figure%24%20%20From%20Your%20Malpractice%20Suit.pdf)

## The details
Checkout my [notebook](https://github.com/S-boker/Classifying-six-figures-in-malpractice-payments-/blob/main/EDA%20and%20Models-Main.ipynb) here, I am not showing the output for the uber slow cells. You are free to download the notebook and run them yourself

## How to run if you want all the details personally
If you want the raw data before the cleaning you can find it [here](https://drive.google.com/drive/folders/160Bx6ybX8fGxCib0x8aF2_SmRWrggR8H?usp=sharing)
Then you can run this [notebook](https://github.com/S-boker/Classifying-six-figures-in-malpractice-payments-/blob/main/Data%20Cleaning/Data%20Cleaning.ipynb) using that csv to get the clean data
Lastly, run this [notebook](https://github.com/S-boker/Classifying-six-figures-in-malpractice-payments-/blob/main/EDA%20and%20Models-Main.ipynb) but I recomend skipping the uber slow cells.
