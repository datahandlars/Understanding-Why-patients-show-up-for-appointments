# Understanding-why-patients-show-up-for-appointments
In this project, we hope to understand the reasons why a patient will either show up or fail to show up after booking an appointment with a doctor. We will be adopting the KaggleV2-May-2016 dataset to achieve this objective.This dataset collects information from 100,000 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. Our data of interest has 14 features and the data we want to predict (No Show) is a categorical variable, which has two outcomes: Yes or No. 

Yes in this case means that the patient did not show up, while No means that the patient showed up. Listed below are the features in the dataset;

PatientId | AppointmentID; 
Gender; 
ScheduledDay;
AppointmentDay;
Age
Neighbourhood
Scholarship
Hipertension
Diabetes
Alcoholism
Handicap
SMS_received
No-show

We try to answer this question by looking at the relationship between the No-show feature in our dataset as against these variables.

Gender: A patient can be male or female
Scholarship: This implies that a patient can be enrolled or not enrolled in Brasilian welfare program
Ailments: In this dataset, we treat features like Handicap, Hipertension, diabetes, Alcoholism as ailments. We then try to understand the impact of this feature on the outcome variable.
Test Messages: If a patient received test messages or not.

Given these variables, we hope to answer the above question by asking these sets of question;

Does a patient's gender determine if he or she will show up for an appointment?
Does Scholarship increase the the rate at which people will show up for appointment?
How do ailments such as Diabetes, Alcoholism, impact if a patient will show up for appointment or not? 
What role does information via test message play in patients showing up for appointments?
