# DataDrive2030-Early-Learning-Predictors-
Description

The Thrive by Five Index (2021) found that less than half of children attending an early learning programme (such as a preschool or creche) in South Africa start school with the right early learning foundation. There are many factors that influence whether a child Thrives by Five, such as access to a quality early learning programme, as well as poverty, gender, malnutrition, and emotional well-being. Children without a good foundation struggle to keep up at school and have a major learning disadvantage.

The Index used the Early Learning Outcomes Measure (ELOM) to assess children, and categorises their development as either “on track”, “falling behind” or “falling far behind”.

In this competition, your challenge is to use machine learning techniques to identify which early learning programme factors contribute to better learning outcomes in children, by predicting a child’s ELOM score.

This will allow DataDrive2030 to design better interventions that make optimal use of limited resources to ensure South Africa’s children are thriving.

About DataDrive2030 (datadrive2030.co.za)

Established in March 2022, DataDrive2030 is a South African based social enterprise that supports the collection and use of high quality data to drive improved child outcomes in the first 6 years of life. Our suite of early learning measurement tools accurately measure a range of developmental outcomes in young children, and provide an indication of the quality of the early learning environment in home and programme settings. Tools are digitised and designed for affordable use at scale in all official South African languages, with built-in data quality assurance mechanisms.

We aim to make these tools widely accessible, and to ensure that the information that is generated is easily understandable and most importantly, is actionable. Using data, our goal is to drive tangible improvements in early childhood development services in South Africa, by 2030.
Evaluation

The error metric for this competition is the Root Mean Squared Error.

For every row in the dataset, submission files should contain 17 columns: ID, ELM Score and the 15 top predictors.

Your submission file should look like this:

child_id       target   feature_1             feature_2   ...       
ID_AWX6YB4QO   56.999   child_score_item_15   child_score_item_7   ... 
ID_SPYK410VL   64.070   child_score_item_4    child_score_item_3   ...

Prizes

1st place: $1 500 USD

2nd place: $900 USD

3rd place: $600 USD

Note: At the end of the challenge, the top ten on the private leaderboard will receive the usual code request email.

The top ten will also need to submit their solutions to the challenge, as well as a sensitivity analysis report pipeline. The created pipeline should be able to take in some variables and output a sensitivity analysis report to show how much the top 15 variables should change independently to move the total ELOM score/target from one category to another. For example, if one of the top variables is the number of child_score_item_1, your pipeline should output how much improvement is needed independently to move a child from category yellow to green or from red to yellow for the different child age categories.

ELOM score category cut-off points:


 

