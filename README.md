Depression, Demographic Characteristics, and Healthy Habits - EDA and Hypothesis Tests

DEPRESSION AND HEALTHY HABITS

Depressive disorder represents a major public health problem and is identified as one of the main causes of illness and debilitation according to the World Health Organization (WHO). Depression results from a complex interaction of social, psychological and biological factors, and although access to diagnoses and treatments is increasing, many still lack access to adequate control of depressive symptoms.

To ensure a healthy lifestyle, the WHO recommends regular exercise, as well as the adoption of a healthy diet rich in natural foods and low in saturated fat, salt and refined sugars.

In this project, we will use data from a survey conducted annually in the United States to assess (1) the profile of individuals (adults over 18 years of age) with depressive symptoms in the US in the period 2005-2006, and (2) whether healthy eating habits diet and physical activity are associated with lower rates of depression in this population.

Objectives:
(1) Verify if the characteristics of the individuals interviewed for the research represent the real population;
(2) Verify which demographic characteristics and healthy habits are more or less correlated to the presence of symptoms of depression.
NATIONAL HEALTH AND NUTRITION EXAMINATION SURVEY (NHANES)
The National Health and Nutrition Examination Survey (NHANES) is an annual survey conducted by the Centers for Disease Control and Prevention's National Center for Health Statistics (NCHS) to assess the health and nutrition of adults and children. from United States. Data collected includes demographic, socioeconomic, dietary, and health-related issues, with the examination component containing medical, dental, physiological, and laboratory tests.

The survey examines a sample of approximately 5,000 people each year, selected from complex sampling in order to select a representative sample of the US civilian non-institutionalized population. Therefore, analyzes using this study should be performed using techniques and tools that take into account complex sampling.

In this challenge, however, we will assume that the data were obtained using a random sample of the population of interest and we will use usual techniques and analysis tools for random samples for didactic purposes.

PATIENT HEALTH QUESTIONNAIRE-9 (PHQ-9)
The Patient Health Questionnaire-9 (PHQ-9) is an instrument used to assess the degree of depression in patients.

Variables from DEMO_PHQ.csv (habits, feelings, demographic characteristics, and activities data).
Symptoms of depression - Measure range from 0 to 3 (0 = “never”, 1 = “less than one week”, 2 = “one week or more”, 3 = “almost everyday”, 7 = "refused to answer" e 9 = "doesn't know").

Questions:
1 - Low interest or pleasure in doing things; 2 - Felt down, depressed, or without perspective; 3 - Difficulty to sleep, keep sleeping, or slept more than usual; 4 - Felt tired and with low energy; 5 - Missing appetize, or ate more than usual; 6 - Felt bad with yourself, felt like failed, or that you disappointed your family, or yourself; 7 - Difficulty to concentrate; 8 - Slowly moved or spoke (to the point that other people noticed), or have been so agitated that kept walking, or moving more than usual; 9 - Thought about hurting yourself, or that would be better to be dead.

Ethnicity
1 - White non-hispanic; 2 - Black non-hispanic; 3 - Mexican-american; 4 - Others; 5 - Others hispanic.

Sex
1 - Male; 2 - Female.

Age
Level of graduation
1 - Incomplete elementary school; 2 - Incomplete high school; 3 - Complete high school; 4 - Incomplete college; 5 - Complete college or higher education; 7 - Refused to answer; 9 - Doesn't know.

Family income (US$)
1 - 0-4999; 2 - 5000-9999; 3 - 10000-14999; 4 - 15000-19999; 5 - 20000-24999; 6 - 25000-34999; 7 - 35000-44999; 8 - 45000-54999; 9 - 55000-64999; 10 - 65000-74999; 11 - Higher than 75000; 12 - Higher than 20000; 13 - Lower than 20000; 77 - Refused to answer; 99 - Doesn't know;

SEQN - index used for each individual.

Healthy Eating Index - (HEI)
The Healthy Eating Index (HEI) is a measure of diet quality based on the Dietary Guidelines for Americans. The HEI uses different food groups to calculate the score, ranging from 0 to 100, in which higher scores reflect diets closer to current dietary guidelines.

The index is composed of 13 components based on the food groups described in the dietary recommendations. Details of maximum values ​​and interpretations are described in the table below:

(https://storage.googleapis.com/tera-originals/desafio-inferencia/download.png)

Physical Activity Guidelines for Americans (PAGA)
The Physical Activity Guidelines for Americans (PAG) is issued by the U.S. Department of Health and Human Services (HHS) and has physical activity recommendations. This document is used in conjunction with the Dietary Guidelines for Americans to promote the importance of being physically active and following a healthy diet.

PAGA recommends that adults engage in at least 150 minutes of moderate-intensity aerobic activity or 75 minutes of vigorous-intensity aerobic activity weekly. From the data collected from NHANES, it is possible to calculate the number of minutes of physical activities, defined as the total weekly minutes of moderate physical activities + 2* (total minutes of vigorous aerobic activities).

Variables from PAG_HEI (ranked alimentation habits data and frequency of physical activities).
HEI uses different food groups to calculate the score, ranging from 0 to 100, where the highest score values mean that the alimentation is closer to the recommended. The index is calculated from 13 components based on food groups described in HEI diet recommendations. (food groups: vegetables, green and beans, total fruits, in natura fruits, whole grain, dairy, proteins, proteins from seafood and plants, fatty acid, sodium, refined grains, saturated fat, and sugar - "TOTAL" is the variable which receives the sum of the score for each individual).

From the collected data by NHANES, is possible to calculate the amount of minutes of physical activity, defined as the total minutes of physical activities with medium intensity + 2*(total minutes of physical activity with high intensity). The variable "ADHERENCE" classifies the quantity of exercise done in a week per individual, and is divided in 3 classes: #1 Low (< 150 min/week) - #2 Appropriate (150-300 min/week) - #3 High (> 300 min/week).

Database
Below we have the databases to be used:

https://drive.google.com/drive/folders/1N4sCFSZDXLYzccP-9t0JXGkF06wiAQS-?usp=sharing

DEMO_PHQ.csv: database containing 5334 observations from adults surveyed in NHANES 2005-2006. Below is a PDF with details of the variables: https://drive.google.com/file/d/1a4bGPp-ZY2zZlqtkF_b_E9cPwiFAUznj/view?usp=sharing

PAG_HEI.csv: database containing 9424 observations of children and adults surveyed in NHANES 2005-2006. Below is a PDF with details of the variables: https://drive.google.com/file/d/1Qc63Z0t5v7zHKUszWOQlHVCwBWG1Ps7i/view?usp=sharing
