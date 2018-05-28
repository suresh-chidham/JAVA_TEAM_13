Requirement:  Find the fraud claim for simple ailment

1) Required 100 claim data
2) Prepare 70 training data and 30 Test claim data model. All training model data are APPROVED and valid claims.
3) Give input 70 training data to TraininModel.py
	a) Group by data based on disease code.
	b) Calculate number of days hospitalization based admission date and discharge date
    c) Calculate mean of hospitalization days and Add 20% of positive deviation. It gives maximum number of allowed day for each disease code.
	d) For K means clustering, X is number of records per group and Y as number of ranking records for disease code.
	e) Draw cluster plot with different colour indicator
	f) write disease code , Allowed max number of days into result file
   
4)    Test the data using Result file
    a) Read the test data
	b) Read the  result file
	c) Pass the Disease code and hospitalized days to function. It will validate. 
	d) It will tell the claim is FRAUD or APPROVED.