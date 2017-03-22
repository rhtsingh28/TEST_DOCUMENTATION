# GET customers config 
## About
customers/:id/users endpoint returns configuration for a customer whose id is passed as input
Request Type : GET


## Response Parameters
|Parameter |Type | Description|
|----------|-----|------------|
|Id|Long	|Id of customer for which request was made|
|allowCancelNomination|	boolean|	Returns true if cancelling nomination is enabled for the customer|
|allowCancelNominationAfterDeposit|	boolean|	Returns true if cancelling nomination after deposit is enabled for the customer|
allowCancelScheduledECard|	boolean|	Returns true if cancelling Scheduled Ecard is enabled for the customer|
allowCancelMonetaryECard|	boolean|	Returns true if cancelling Monetary Ecard is enabled for the customer|


