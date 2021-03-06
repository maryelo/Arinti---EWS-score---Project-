# Arinti---EWS-score---Project-

## Project Todolist

- [ ] Fill in todolist (everyone)
- [ ] Divide tasks (voice meet)
- [x] Update readme with dataset info (maja)
- [ ] Rewrite readme from our perspective (who what where, how why when, approach, plans, ideas, todolist, strucutre)
- [ ] ...

## Team 

### Alex Delruelle

### Francesca Bormioli

### Maja Minnaert

### Maryame El Omari
- 4 Jan: introduction to the assesment & the dataset
         analyzing and preprocessing
- 5 Jan: Continue preproccing and visualizing certain findings
- 6 Jan: Studying Timeseries & trying out on the dataset



# Assignment description: EWS regression

*copy-pasted + now includes dataset info*

- Repository: `regression`
- Type of Challenge: `use case`
- Duration: `9 days`
- Deadline: `15/01/2020`
- Deployment strategy :
	 Github page
	 ppt (or alternative) presentation
- Team challenge : `4 people`

## Mission objectives 

- to preprocess a use case dataset
- to regress timeseries data
- to properly visualise results 


## The Mission

[M-ighty](http://www.m-ighty.com/), a healthcare tech consultancy company, has contracted [Arinti](https://arinti.ai/), an AI consultancy company to analyse an [early warning score](https://en.wikipedia.org/wiki/Early_warning_score) [database](./20200124_ews_observations) containing various data hospital patients.
Your mission is to:
- organise and preprocess the data so that it can be use for ML
- use regression analysis on the individual patients (that have enough data on them) to discover their EWS trend
- properly analyse the usability and reliability (confidence) of your models for both inter- and extrapolation
- visualise your results in an interpretable manner (proper titles, labels, units, etc)
- visualise any other interesting data about the patients 
- point out interesting insights that your models show

You can be as creative as you want with this, and use any technique you have learned. But remember, this is a use case for a real client, with real data, so the key here is:
- **presentation**
- **correctness**
- **interpretability**

### Additional dataset info

- PatientId: Unique identifier for the patient
- ObservationDate: Date of the observation
- EwsProcedure: Which EWS procedure has been used (> in your dataset, this will normally always be NEWS2.0)
- EWS_Total: Total EWS score
- SBP: Systolic Blood Pressure
- SBP_Score: Contribution of SBP parameter to total EWS score
- LOC: Level Of Consciousness
- LOC_Score: Contribution of LOC parameter to total EWS score
- SpO2: Peripheral capillary oxygen saturation (the amount of oxygen in the blood)
- SpO2_Score: Contribution of SpO2 parameter to total EWS score
- Add_O2: Is the patient receiving additional oxygen or not
- Add_O2_Score: Contribution of Add_O2 parameter to total EWS score
- HR: Heartrate
- HR_Score: Contribution of HR parameter to total EWS score
- RR: Respiratory Rate
- RR_Score: Contribution of RR parameter to total EWS score
- TEMP: Patient body temperature
- TEMP_Score: Contribution of TEMP parameter to total EWS score

### Must-have features

- regression analysis on as many patients possible
- proper regression evaluation (be careful of overfitting)
- visualisation of your regression results
- a final presentation introducing yourself as a consultancy team, and all of your visualisations and insights

### Nice-to-have features

- clustering of your obtained regression models (hint: clustering of trendlines that have similar slopes)
- clustering of other features for visualisation purposes
- deployment of your code and models (e.g. dash or streamlit)


## Deliverables

1. Publish your source code on the GitHub repository.
2. push your code at least once a day

### Steps
1. Create the repository
2. Study the request (What & Why ?)
3. analyse the [dataset](./20200124_ews_observations)
4. Regress
5. visualise
5. evaluate
6. (cluster)
7. (deploy)


## Evaluation criterias
1. Arinti thinks you're the shit

## A final note of encouragement

![You've got this!](https://media.giphy.com/media/VbzpvRC1LWGRQAvues/giphy.gif)
