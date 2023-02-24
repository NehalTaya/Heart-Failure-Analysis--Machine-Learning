# Heart-Failure-Analysis--Machine-Learning

**BACKGROUND**

**Using the HeartFailure data, determine the factors that influence heart failure.**


**DATASET**

This data is from the University of California Irvine machine learning dataset repository.
https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records


**DATA FIELDS**

1.Age - age of the patient (years)

2.Anaemia- decrease of red blood cells or hemoglobin (boolean)

3.High blood pressure -if the patient has hypertension (boolean)

4.Creatinine phosphokinase (CPK): level of the CPK enzyme in the blood (mcg/L)

5.Diabetes -if the patient has diabetes (boolean)

6.Ejection fraction - percentage of blood leaving the heart at each contraction (percentage)

7.Platelets -platelets in the blood (kiloplatelets/mL)

8.Sex - woman or man (binary)

9.Serum creatinine -level of serum creatinine in the blood (mg/dL)

10.Serum sodium -level of serum sodium in the blood (mEq/L)

11.Smoking -if the patient smokes or not (boolean)

12.Time -follow-up period (days)

13.Death event - if the patient deceased during the follow-up period (boolean)

**DATA VALUES**

Sex - Gender of patient Male = 1, Female =0

Age - Age of patient

Diabetes - 0 = No, 1 = Yes

Anaemia - 0 = No, 1 = Yes

High_blood_pressure - 0 = No, 1 = Yes

Smoking - 0 = No, 1 = Yes

DEATH_EVENT - 0 = No, 1 = Yes

**RESULTS**

**SCATTERPLOT**

![image](https://user-images.githubusercontent.com/100436462/221019938-47bbfde0-756c-4000-a19d-9b4aa486b94d.png)


**1.We can see from the  SVM Classification Plot that irrespective of the age of the person , people with high platelet counts are more likely to survive**

![image](https://user-images.githubusercontent.com/100436462/221016507-8039fc1f-c4ad-4dd8-9eed-11015aff419e.png)

**2.The second conclusion we can draw from below classification plot is that people in the age group of 40 and 70 and with serium sodium bewteen 116-125 are not likely to survive**

![image](https://user-images.githubusercontent.com/100436462/221018540-26348904-8c9e-47c4-86c3-7662561597c0.png)

**3.The third SVM classifcation plot shows that people with creatinine_phosphokinase level between 2000 and 6000 and serum sodium level between 115 and 125 are more likely to survive**

![image](https://user-images.githubusercontent.com/100436462/221252632-9a73cce5-198b-4fe9-8a32-019bc0734b78.png)




