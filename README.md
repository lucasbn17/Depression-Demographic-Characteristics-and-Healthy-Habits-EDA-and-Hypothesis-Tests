# Depression-Demographic-Characteristics-and-Healthy-Habits---EDA-and-Statistical-Inference
EDA and Statistical Inference using dataset from the National Health and Nutrition Examination Survey (NHANES) conducted by the National Center for Health Statistics (NCHS) and by the Centers for Disease Control - CDC.

Medium article: https://medium.com/@lucasbn17/some-other-ways-of-doing-hypothesis-tests-for-a-statistical-inference-on-python-than-using-the-c4c502543cd3

Variables from DEMO_PHQ.csv (habits, feelings, demographic characteristics, and activities data).
Symptoms of depression - Measure range from 0 to 3 (0 = “never”, 1 = “less than one week”, 2 = “one week or more”, 3 = “almost everyday”, 7 = "refused to answer" e 9 = "doesn't know").
Questions:
####1 - Low interest or pleasure in doing things; ####2 - Felt down, depressed, or without perspective; ####3 - Difficulty to sleep, keep sleeping, or slept more than usual; ####4 - Felt tired and with low energy; ####5 - Missing appetize, or ate more than usual; ####6 - Felt bad with yourself, felt like failed, or that you disappointed your family, or yourself; ####7 - Difficulty to concentrate; ####8 - Slowly moved or spoke (to the point that other people noticed), or have been so agitated that kept walking, or moving more than usual; ####9 - Thought about hurting yourself, or that would be better to be dead.

Ethnicity
1 - White non-hispanic;
2 - Black non-hispanic;
3 - Mexican-american;
4 - Others;
5 - Others hispanic.

Sex
1 - Male;
2 - Female.

Age
Level of graduation
1 - Incomplete elementary school;
2 - Incomplete high school;
3 - Complete high school;
4 - Incomplete college;
5 - Complete college or higher education;
7 - Refused to answer;
9 - Doesn't know.

Family income (US$)
1 - 0-4999; 2 - 5000-9999; 3 - 10000-14999; 4 - 15000-19999; 5 - 20000-24999; 6 - 25000-34999; 7 - 35000-44999; 8 - 45000-54999; 9 - 55000-64999; 10 - 65000-74999; 11 - Higher than 75000; 12 - Higher than 20000; 13 - Lower than 20000; 77 - Refused to answer; 99 - Doesn't know;

SEQN - index used for each individual.
Variables from PAG_HEI (ranked alimentation habits data and frequency of physical activities).
HEI uses different food groups to calculate the score, ranging from 0 to 100, where the highest score values mean that the alimentation is closer to the recommended.
The index is calculated from 13 components based on food groups described in HEI diet recommendations. Details of the maximum values and interpretations are described below. (food groups: vegetables, green and beans, total fruits, in natura fruits, whole grain, dairy, proteins, proteins from seafood and plants, fatty acid, sodium, refined grains, saturated fat, and sugar - "TOTAL" is the variable which receives the sum of the score for each individual).
PAG recommends that adults practice at least 150 min of aerobic activities with medium intensity or 75 minutes of aerobic activities with high intensity per week.
From the collected data by NHANES, is possible to calculate the amount of minutes of physical activity, defined as the total minutes of physical activities with medium intensity + 2*(total minutes of physical activity with high intensity). The variable "ADHERENCE" classifies the quantity of exercise done in a week per individual, and is divided in 3 classes: #1 Low (< 150 min/week) - #2 Appropriate (150-300 min/week) - #3 High (> 300 min/week).¶
