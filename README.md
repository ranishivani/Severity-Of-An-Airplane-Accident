# Severity-Of-An-Airplane-Accident

Problem Statement: To Predict the severity of an airplane accident in order to take actions to minimize the risk associated with it.

Columns	Description

Accident_ID :	unique id assigned to each row
Accident_Type_Code : the type of accident (factor, not numeric)
Cabin_Temperature :	the last recorded temperature before the incident, measured in degrees fahrenheit
Turbulence_In_gforces	: the recorded/estimated turbulence experienced during the accident
Control_Metric :	an estimation of how much control the pilot had during the incident given the factors at play
Total_Safety_Complaints :	number of complaints from mechanics prior to the accident
Days_Since_Inspection	: how long the plane went without inspection before the incident
Safety_Score :	a measure of how safe the plane was deemed to be
Violations :	number of violations that the aircraft received during inspections
Severity : (Highly_Fatal_And_Damaging, Significant_Damage_And_Serious_Injuries, Minor_Damage_And_Injuries, Significant_Damage_And_Fatalities)	
a description (4 level factor) on the severity of the crash [Target]

What I used
Gradient Boosting Classifier: The objective of Gradient Boosting classifiers is to minimize the loss, or the difference between the actual class value of the training example and the predicted class value. 
It isn't required to understand the process for reducing the classifier's loss, but it operates similarly to gradient descent in a neural network. The Gradient Boosting Classifier depends on a loss function.
