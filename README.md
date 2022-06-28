# Stroke_Prediction


The_Problem

Stroke is a medical condition that can lead death. It affects the arteries leading to and within the brain.It is the fifth cuase of death and leading cuase of disability in the United States. According to the CDC someone has stroke every 40 seconds in the US with every 4 minutes someone dies with a stroke. A stroke occurs when the blood vessel that carries oxygen and nutrients to the brain is either blockd by a clot or bursts. Since strokes are prevalent and a huge health concern, it would be helpful to develop a model that will help with predict whether someone is likely to get a stroke using parameters like age, blood glucose, hypertension, etc.

Questions:

What features are associated with stroke?
What model will best predict for a stroke based on those input features?
The Dataset:

The inputs in the data include:

1) id: unique identifier

2) gender: "Male", "Female" or "Other"

3) age: age of the patient

4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension

5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease

6) ever_married: "No" or "Yes"

7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"

8) Residence_type: "Rural" or "Urban"

9) avg_glucose_level: average glucose level in blood

10) bmi: body mass index

11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"

12) stroke: 1 if the patient had a stroke or 0 if not

Note: "Unknown" in smoking_status means that the information is unavailable for this patient


Conclusion

I used the lazy classifier to help with determining which alorgithm I wanted to use for predictions and then I used the sklearn library to run a knieghbors classifier for my model.

Since the dataset was imbalanced I decided to use F1 score( the weighted average of precision and recall as the metric. The F1 score for the alogrithm is 88%. Meaning that it correctly predicts if someone is at risk of stroke 88% of the time.

Recommnedation

This is helpful to know becuase we can use the information to design programs or projects that will help to lessen stress, help with lower blood gluocse, and establishing programs that potentially will help with hypertension and heart attack such as adding more opportunities for exercise while at work or school or throughout the day which can have tiny impacts on ones health as they age which can help with lower the chances of stroke.
