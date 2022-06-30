# Data-Analysis-No_show_appointments
# Project: No-show appointments

## Table of Contents
* Introduction
* Data Wrangling
* Exploratory Data Analysis
* Conclusions

### Introduction

#### Dataset Description
This dataset collects information from 110,527 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. The dataset has 14 columns of characteristics about the patient. The columns are

● PatientId - a unique identification for each patient

● AppointmentID - a unique identification for each set appointment

● Gender - patient's gender

● ScheduledDay - the day the patient set up their appointment

● AppointmentDay - day Date of appointment

● Age - Age of the patient

● Neighbourhood - indicates the location of the hospital

● Scholarship - indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família

● Hipertension - indicates if patient is hypertensive

● Diabetes - indicates if patient has diabetes

● Alcoholism - indicates if patient consumes alcohol

● Handcap- indicates if patient is handicap

● SMS_received - indicates if patient recieves any sms

● No-show - the target, indicates is patient shows up. (‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.)

# Question(s) for Analysis
What is the parients showing-up and not showing-up percentage ?
what factors affect showing-up rate and how do they affect it ?

## Conclusions
#after analysing the data we found out that there are several factors that had higher showing up rate such as :
Gender = female
Not having a scholarship
Having hypertension
Having Diabetes
Not getting SMS
Being handicaped level 1
Being Alcoholic
Waiting from 105 to 120 days before Appointment day 9- Being 60-75 years old

## LIMITATIONS:
The analysis looked at the relation between showing-up rate and some other factor. It didn't look at how each factor affected the other.
We had to drop data (3540 row) in the cleaning process
The statistics used here are descriptive statistics, not inferential.
