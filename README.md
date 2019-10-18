## Medical Appointment No-Shows

Can we predict who will not show for their medical appointments?

## Data Set

The data shows the demographics for 110,527 no-show medical applointments. No-show is defined as a person, who has a scheduled appointment, does not show up for that appointment. Data came from Kaggle https://www.kaggle.com/joniarroba/noshowappointments. There are 14 columns in the dataframe. The following analysis explores which factors included in this dataset, if any affect the ability of patients to keep medical appointments. 

## Summary of Findings

A description of the data is as follows:

PatientId - Identification of a patient
AppointmentID - Identification of each appointment
Gender = Male or Female
Appointment Day = The day of the appointment
Scheduled Day = The day someone called or registered the appointment, this is before appointment of course
Age
Neighbourhood = Where the appointment takes place
Scholarship = True or False
Hypertension (column name = hipertension) = True or False
Diabetes = True or False
Alcoholism = True or False
Handicap (column name = Handcap) = True or False
SMS_received = 1 or more messages sent to the patient
No-show = True or False

After reviewing the data, PatientID, AppointmentID, and Scheduled Day variables were removed from the dataset.

Analysis of the data showed that age, income level, hypertension, and day of the week are the variables that most affect a patient's ability to attend an appointment.

The data, surprisingly, shows that men and women miss appointments at about the same rate - 20.31% and 19.97%, respectively. Also, text reminders do not reduce no-shows in this population.

## Requirements
Python 

numpy

pandas

matplotlib.pyplot



