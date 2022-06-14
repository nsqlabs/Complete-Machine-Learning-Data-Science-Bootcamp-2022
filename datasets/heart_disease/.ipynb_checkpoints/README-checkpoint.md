This file describes the contents of the heart-disease directory.

This directory contains 4 databases concerning heart disease diagnosis.
All attributes are numeric-valued. The data was collected from the
four following locations:

 1. Cleveland Clinic Foundation (cleveland.data)
 2. Hungarian Institute of Cardiology, Budapest (hungarian.data)
 3. V.A. Medical Center, Long Beach, CA (long-beach-va.data)
 4. University Hospital, Zurich, Switzerland (switzerland.data)
 
## `heart_diseases` features explanation

- **age**
- **sex** (0 = female, 1 = male)
- **cp** cp: chest pain type -- 1: typical angina -- 2: atypical angina -- 3: non-anginal pain -- 4: asymptomatic
- trestbps) trestbps: resting blood pressure (in mm Hg on admission to the hospital)
- **chol** chol: serum cholesterol in mg/dl
- **fbs** fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- **restecg** restecg: resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- **thalach** halach: maximum heart rate achieved
- **exang** exercise induced angina (1 = yes; 0 = no)
- **oldpeak** oldpeak = ST depression induced by exercise relative to rest
- **slope** slope: the slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping
- **ca** ca: number of major vessels (0-3) colored by flourosopy
- **tha**) thaldur: duration of exercise test in minutes
- **num** (the predicted attribute) num: diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels)