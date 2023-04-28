# Project details
The project is dedicated to the topic of baby sleep and how it might depend on different factors. The dataset includes some demographic variables about the parents, information about gender, age, gestational age of the baby, way babies fall asleep, 10 questions from the Infant Behavior Questionnaire (scale from 1 to 6), and dependent variables - hours of night sleep and number of awakenings.
The original datasets consists of 410 entries and 64 columns. 

# Questions to answer
1. Is there any differentce between genders in sleep paterns?
2. Does sleep patterns change (improve) with months?
3. How a way to fall asleep changes with months?
4. Can way to fall asleep, gender, age group predict the sleep pattern? 
5. Is there any correlation between baby behaviors (from IBQ) and sleep patterns?

# Issues/data cleaning with the dataset
27 columns were excluded from a dataset (those columns included questions from maternal health surveys) that were not of the interest of this analysis. 
10 questions related to infant behaviors had Nan values. They were filled with KNN method (n=5).
The data was already encoded in all the columns, therefore it made it easier to perform the analysis.

# Answers
1. The analysis shows that there are no real difference between baby genders when it comes to sleep patterns;
2. However, there is an improvement in sleep pattern by months, because the sleep becomes more consolidated;
3. Way to fall asleep changes with months, but the majority of babies in the dataset fall asleep by themselves in a crib in all age groups;
4. Way to fall asleep can predict sleep patters, whereas age and gender cannot;
5. Baby behaviors have a very low correlation with sleep patterns.

# Conclusions
Therea are factors that can define sleep patterns in babies, but in many cases the sleep behavior is very individual.

# Next steps
Collecting more precise data, e.g. looking at every months of baby life from 1 to 12. Also collecting data from the same babies for every month of their life. 
Adding more features that can influence sleep patterns: e.g. start time of the night sleep session, end time of the night sleep session, number of feeding during the night.