The Statlog (German Credit Data) dataset is a widely used resource for evaluating credit risk modeling techniques. It comprises 1,000 instances, each representing a credit applicant, with 20 attributes detailing personal and financial information. The objective is to classify applicants as good or bad credit risks based on these attributes.

Dataset Overview:
	•	Instances: 1,000
	•	Attributes: 20 (7 numerical, 13 categorical)
	•	Target Variable: Credit risk classification (good or bad)

Attribute Information:
	1.	Status of existing checking account:
	•	… < 0 DM
	•	0 <= … < 200 DM
	•	… >= 200 DM / salary assignments for at least 1 year
	•	no checking account
	2.	Duration in month: (numeric)
	3.	Credit history:
	•	no credits taken/ all credits paid back duly
	•	all credits at this bank paid back duly
	•	existing credits paid back duly till now
	•	delay in paying off in the past
	•	critical account/ other credits existing (not at this bank)
	4.	Purpose:
	•	car (new)
	•	car (used)
	•	furniture/equipment
	•	radio/television
	•	domestic appliances
	•	repairs
	•	education
	•	retraining
	•	business
	•	others
	5.	Credit amount: (numeric)
	6.	Savings account/bonds:
	•	… < 100 DM
	•	100 <= … < 500 DM
	•	500 <= … < 1000 DM
	•	… >= 1000 DM
	•	unknown/ no savings account
	7.	Present employment since:
	•	unemployed
	•	… < 1 year
	•	1 <= … < 4 years
	•	4 <= … < 7 years
	•	… >= 7 years
	8.	Installment rate in percentage of disposable income: (numeric)
	9.	Personal status and sex:
	•	male : divorced/separated
	•	female : divorced/separated/married
	•	male : single
	•	male : married/widowed
	•	female : single
	10.	Other debtors / guarantors:
	•	none
	•	co-applicant
	•	guarantor
	11.	Present residence since: (numeric)
	12.	Property:
	•	real estate
	•	building society savings agreement/ life insurance
	•	car or other, not in attribute 6
	•	unknown / no property
	13.	Age in years: (numeric)
	14.	Other installment plans:
	•	bank
	•	stores
	•	none
	15.	Housing:
	•	rent
	•	own
	•	for free
	16.	Number of existing credits at this bank: (numeric)
	17.	Job:
	•	unemployed/ unskilled - non-resident
	•	unskilled - resident
	•	skilled employee / official
	•	management/ self-employed/ highly qualified employee/ officer
	18.	Number of people being liable to provide maintenance for: (numeric)
	19.	Telephone:
	•	none
	•	yes, registered under the customer’s name
	20.	Foreign worker:
	•	yes
	•	no

Cost Matrix:

This dataset includes a cost matrix to reflect the implications of misclassification:

Actual \ Predicted	Good (1)	Bad (2)
Good (1)	0	1
Bad (2)	5	0

Misclassifying a bad applicant as good incurs a higher cost (5) compared to misclassifying a good applicant as bad (1), emphasizing the importance of accurate predictions.

Usage:

This dataset is commonly employed for:
	•	Evaluating and comparing classification algorithms