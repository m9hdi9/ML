Problem Definition :

Problem Type: Classification.
Reason: The goal is to categorize patients into discrete classes (e.g., presence or absence of heart disease) rather than predicting a continuous numerical value.
Target Variable: Diagnosis (The column representing the presence of heart disease).
Problem Description: The model is expected to learn how to predict the presence of heart disease in a patient based on their physiological attributes, such as age, blood pressure, cholesterol levels, and other relevant medical indicators.

--------------------------------------------------------------------------------------------------------------------------
About Dataset :

This file describes the contents of the heart-disease directory.
This directory contains 4 databases concerning heart disease diagnosis. All attributes are numeric-valued. The data was collected from the four following locations:
1. Cleveland Clinic Foundation (cleveland.data)
2. Hungarian Institute of Cardiology, Budapest (hungarian.data)
3. V.A. Medical Center, Long Beach, CA (long-beach-va.data)
4. University Hospital, Zurich, Switzerland (switzerland.data)

Each database has the same instance format. While the databases have 76 raw attributes, only 14 of them are actually used. Thus I've taken the liberty of making 2 copies of each database: one with all the attributes and 1 with the 14 attributes actually used in past experiments.
