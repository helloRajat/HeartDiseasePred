# HeartDiseasePred

Hosted by Drivendata

Heart disease is the number one cause of death worldwide. To learn how to prevent heart disease we must first learn to reliably detect it.
This dataset is from a study of heart disease that has been open to the public for many years. The study collects various measurements on patient health and cardiovascular statistics. The patient identities anonymous.

About:
Preventing heart disease is important. Good data-driven systems for predicting heart disease can improve the entire research and prevention process, making sure that more people can live healthy lives.
In the United States, the Centers for Disease Control and Prevention is a good resource for information about heart disease. According to their website:
•	About 610,000 people die of heart disease in the United States every year–that’s 1 in every 4 deaths.
•	Heart disease is the leading cause of death for both men and women. More than half of the deaths due to heart disease in 2009 were in men.
•	Coronary heart disease (CHD) is the most common type of heart disease, killing over 370,000 people annually.
•	Every year about 735,000 Americans have a heart attack. Of these, 525,000 are a first heart attack and 210,000 happen in people who have already had a heart attack.
•	Heart disease is the leading cause of death for people of most ethnicities in the United States, including African Americans, Hispanics, and whites. For American Indians or Alaska Natives and Asians or Pacific Islanders, heart disease is second only to cancer.

```
Problem description
Your goal is to predict the binary class heart_disease_present, which represents whether or not a patient has heart disease:
•	0 represents no heart disease present
•	1 represents heart disease present
```

Dataset
There are 14 columns in the dataset, where the patient_id column is a unique and random identifier. The remaining 13 features are described in the section below

Column Description

```
slope_of_peak_exercise_st_segment (type: int): the slope of the peak exercise ST(stress test) segment, an electrocardiography read out indicating quality of blood flow to the heart. The ST segment shift relative to exercise-induced increments in heart rate, the ST/heart rate slope (ST/HR slope), has been proposed as a more accurate ECG criterion for diagnosing significant coronary artery disease (CAD).
0: Upsloping: better heart rate with excercise (uncommon)
1: Flatsloping: minimal change (typical healthy heart)
2: Downslopins: signs of unhealthy heart
thal (type: categorical): results of thallium stress test measuring blood flow to the heart, with possible values
normal,
fixed_defect (used to be defect but ok now),
reversible_defect (no proper blood movement when excercising)
resting_blood_pressure (type: int): resting blood pressure (in mm Hg) anything above 130-140 is typically cause for concern
chest_pain_type (type: int): chest pain type (4 values) Angina is a condition marked by severe pain in the chest, often also spreading to the shoulders, arms, and neck, owing to an inadequate blood supply to the heart.
1: Typical angina: chest pain related decrease blood supply to the heart
2: Atypical angina: chest pain not related to heart
3: Non-anginal pain: typically esophageal spasms (non heart related)
4: Asymptomatic: chest pain not showing signs of disease
num_major_vessels (type: int): number of major vessels (0-3) colored by flourosopy
colored vessel means the doctor can see the blood passing through
the more blood movement the better (no clots)
fasting_blood_sugar_gt_120_mg_per_dl (type: binary): fasting blood sugar > 120 mg/dl
'>126' mg/dL signals diabetes
resting_ekg_results (type: int): resting electrocardiographic results (values 0,1,2)
0: Nothing to note
1: ST-T Wave abnormality
can range from mild symptoms to severe problems
signals non-normal heart beat
2: Possible or definite left ventricular hypertrophy
Enlarged heart's main pumping chamber
serum_cholesterol_mg_per_dl (type: int): serum cholestoral in mg/dl
oldpeak_eq_st_depression (type: float): oldpeak = ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more, a measure of abnormality in electrocardiograms
sex (type: binary): 0: female, 1: male
age (type: int): age in years
max_heart_rate_achieved (type: int): maximum heart rate achieved (beats per minute)
exercise_induced_angina (type: binary): exercise-induced chest pain (0: False, 1: True)

Credit - 
https://machinelearningmastery.com/
https://stackoverflow.com/
https://kaggle.com
```


```
![](https://komarev.com/ghpvc/?username=helloRajat&label=PROFILE+VIEWS)
```
