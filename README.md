# What is Heart Attack?

-> The medical name of heart attack is “Myocardial infarction”.
-> Heart attack in short; It is the occlusion of the vessel by plaque-like lesions filled with cholesterol and fat.
-> The lesion is called abnormal conditions that occur in the organs where the disease is located.
-> As a result of the blockage, the blood flow is completely cut off and a heart attack that can lead to death occurs.

# How does a heart attack occur?

-> The heart is a powerful pump that pumps blood throughout the body 60-80 times per minute at rest.
-> While meeting the blood needs of the whole body, it also needs to be fed and taken blood.
-> These vessels that feed the heart itself are called coronary arteries.
-> Coronary insufficiency occurs when there is a disruption in the circulation of the coronary arteries.
-> The cases of coronary insufficiency vary according to the type, degree and location of the stenosis in the coronary vessels.
-> While some patients may have chest pain that occurs only during physical activity and is relieved by rest, sometimes a heart
attack may occur as a result of sudden occlusion of the vessels, starting with severe chest pain and leading to sudden death.

# Variable definitions in the Dataset

1. Age: Age of the patient
2. Sex: Sex of the patient
3. exang: exercise induced angina (1 = yes; 0 = no)
4. ca: number of major vessels (0-3)
5. cp: Chest Pain type chest pain type
     Value 1: typical angina
     Value 2: atypical angina
     Value 3: non-anginal pain
     Value 4: asymptomatic
6. trtbps: resting blood pressure (in mm Hg)
7. chol: cholestoral in mg/dl fetched via BMI sensor
8. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
9. _restecg: resting electrocardiographic results
     Value 0: normal
     Value 1: having ST-T wave abnormality (T wave inversions and/or   ST elevation or depression of > 0.05 mV)
     Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
10. thalach: maximum heart rate achieved
11. target: 0= less chance of heart attack 1= more chance of heart attack

# Basic Libraries

import numpy as np
import pandas as pd
import warnings
warnings.filterwarnings("ignore")
import matplotlib.pyplot as plt
import seaborn as sns
import missingno
