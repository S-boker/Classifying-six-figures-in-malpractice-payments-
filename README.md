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
If the read me is not enough, you can look at Making Six-figure$  From Your Malpractice Suit.pdf

## How to run if you want all the details
If you want the raw data before the cleaning you can find it [here](https://drive.google.com/drive/folders/160Bx6ybX8fGxCib0x8aF2_SmRWrggR8H?usp=sharing)
Then you can run the notebook Data Cleaning\Data Cleaning.ipynb using that csv to get the NPDB2401_Modern_Malpractice_Clean.csv
Lastly, you cna run EDA and Models-Main.ipynb
