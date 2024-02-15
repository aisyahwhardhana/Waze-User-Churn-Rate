# Predicting-Waze-Churn-Rate
A part of Google Advanced Data Analytics Certification Project
### Project Goal
Waze leadership has asked your data team to develop a machine learning model to predict user churn. Churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. This project focuses on monthly user churn. An accurate model will help prevent churn, improve user retention, and grow Waze's business.
### Data Dictionary
| Column Name | Type | Description |
| --- | --- | ---|
| ID | int | A sequential numbered index |
| label | obj | Binary target variable("retained" vs "churned") for if a user has churned anytime during the course of the month |
| sessions | int | The number of occurences of a user opening the app during the month |
| drives | int | An occurence of driving at least 1 km during the month |
| device | obj | The type of device a user starts a session with |
| total_sessions | float | A model estimate of the total number of sessions since a user has onboarded |
| n_days_after_onboarding | int | The number of days since a user signed up for the app |
| total_navigations_fav1 | int | Total navigations since onboarding to the user's favorite place 1 |
| total_navigations_fav_2 | int | Total navigations since onboarding to the user's favorite place 2 |
| driven_km_drives | float | Total kilometers driven during the month |
| duration_minutes_drives | float | Total duration driven in minutes during the month |
| activity_days | int | Number of days the user opens the app during the month |
| driving_days | int | Number of days the user drives at least 1 km during the month |
