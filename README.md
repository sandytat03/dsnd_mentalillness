# Mental illness - potential factors we should be aware of (Data Science Nanodegree, Project 1)

## About the project

This project is a part of Udacity's Data Science Nanodegree, project 1 - aiming to help students getting familiar with and practice their skills applied to a complete Data Science process as well as effectively communicate with stakeholders.

The project includes submissions of a blog post and a Github repository.
- You can find the link to my blog post here on Medium: [Mental illness - potential factors we should be aware of](https://medium.com/@sandytat22/mental-illness-potential-factors-we-should-be-aware-of-3672a7de6515)

## Python libraries used

In my jupyter notebook, I used Python 3 and below Python libraries:
- Pandas
- Numpy
- Seaborn
- Scikit-learn
- Matplotlib

## The dataset

The dataset is from Kaggle [Unemployment and mental illness survey](https://www.kaggle.com/michaelacorley/unemployment-and-mental-illness-survey#Cleaned%20Data.xlsx), collected via a paid research survey by Michael Corley.

The original purpose of the survey was to explore the relationship between mental illness and employment status. Whereas, for my project, I focus on a slightly broader analysis taken into accoutn some other variables than just employment status.

You can find out more about his methodology directly from his contribution on Kaggle [Unemployment and mental illness survey](https://www.kaggle.com/michaelacorley/unemployment-and-mental-illness-survey#Cleaned%20Data.xlsx)

The original dataset you can download from the above Kaggle link includes 1 Excel file. I've downloaded it, done some minor change on tidying up the header of the Excel file and saved it in csv. You can find my csv file (mental_illness_survey_1.csv) in my Github depository here.

The mental_illness_survey_1.csv has 334 rows and 40 columns (variables). It has data about the survey participants':
1. Region
2. Gender
3. Age
4. Education level
5. Income
6. Employment status
7. Support received from family and government
8. Health conditions
9. Lifestyle and/or behaviour

## Summary of findings

Below are 5 main findings I discovered as the result of my analysis.
1. Employment status, age and health conditions features have quite high correlation relationship with the likelihood of one experiencing mental illness. While other features like geographic, demographic and behavioural only have a moderate level of correlation relationship with one being identified with mental illness.
2. Different level of education together with their employment status have an impact on one's mental wellbeing. In brief, people with higher education qualification seems to have higher self-expectation. This can put more pressure on them and lead to several mental health issues. However, being employed at least part-time do have some level of positive impact on one's mental wellbeing.
3. Participants who were identified with mental illness have bigger gap in their resume than those who weren't identified with mental illness.
4. Anxiety and depression are two of the most common symptoms among those are suffering from mental illness. Whereas, tiredness is popular too but it also happends to those who aren't suffering from mental illness.
5. Going through the above analysis, I built a logistic regression model that can distinguish between correctly (approx. 89.41% chance) who are likely to be suffering from mental illness, by feeding data of a set of selected features.

You can find more details of methods I used in my jupyter notebook saved in this Github repository.

## Licensing, authors and aknowledgements

I would like to acknowledge the contribution of Michael Corley for his contribution for the Unemployment and mental illness survey data.
