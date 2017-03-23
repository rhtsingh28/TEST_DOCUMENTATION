# GET customers config 
## About
```
customers/:id/users endpoint returns configuration for a customer whose id is passed as input
Request Type : GET
```

## Request Parameters
|Parameter |Type |Required| Description|
|----------|-----|------------|------|
|Id|Long	|Yes|Id of customer for which request is made|


## Response Parameters
|Parameter |Type | Description|
|----------|-----|------------|
|Id|Long	|Id of customer for which request was made|
|allowCancelNomination|	boolean|	Returns true if cancelling nomination is enabled for the customer|
|allowCancelNominationAfterDeposit|	boolean|	Returns true if cancelling nomination after deposit is enabled for the customer|
|allowCancelScheduledECard|	boolean|	Returns true if cancelling Scheduled Ecard is enabled for the customer|
|allowCancelMonetaryECard|	boolean|	Returns true if cancelling Monetary Ecard is enabled for the customer|


# Response format
```
{ 
"id": 6971300, 
"allowCancelNomination": false, 
"allowCancelNominationAfterDeposit": false, 
"allowCancelScheduledECard": false, 
"allowCancelMonetaryECard": false 
}
```

## Status Code
|Code |Status Text | Description|
|----------|-----|------------|
|400|Bad Request	|Too many for bad input|
|401|	|	if called with an unauthorized client id|
|404|	Not Found|	if the customer does not exist|

# Thank you !
[GitHub](https://github.com/)
[Test Link](test.md)
