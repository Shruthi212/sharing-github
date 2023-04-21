# sharing-github

## API-Exchange Rates

API source- https://exchangeratesapi.io/
This Python code retrieves exchange rates data for a specified time period using the API endpoint provided by apilayer.com-ExchangeRate. It then formats the retrieved data and exports it to an Excel file named Exchange_Rates.xlsx.

### Usage
Replace the API key value in the headers dictionary with a valid API key for apilayer.com.
Specify the desired start date for the exchange rates data in the start_date parameter of the url variable.
Run the Python script to retrieve and format the data.
The formatted data will be exported to an Excel file named Exchange_Rates.xlsx.


## CompanyXYZ Claims Data Processing
### Output
Year: The underwriting year of the policy
DevelopmentMonth: The development month of the claim
LossIncurredRatio: The loss incurred ratio for the given year and development month
LineOfBusiness: The line of business associated with the claim
DWCreatedDate: The date the data was processed
DWCreatedBy: The name of the person who processed the data
Currency: The currency used for the loss incurred ratio
CompanyName: The name of the company (in this case, CompanyXYZ)
The DataFrame is saved to a variable called gl_np_stat and can be used for further analysis or visualization.
