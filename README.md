# MS_BuildProjectFromSpecAndPopulateWithData



UAPIM DEMO SCRIPT CREATE

Create an API Spec

inventory-demo
- productName 
- quantity
- location

order-brossard
- customerName
- productName
- quantity






PROMPT 1 : 

Can you please create me an API spec (openapi 3.0.0 and json) with name candidate-demo API
It has 2 operations 
Get : that returns all
Post : that allow to create candidates from an array

Object should contains
- id 
- firstName
- lastName
- email
- phoneNumber
- jobTitle
- grade (values could be : associate , junior, senior, principal)
- coOptPersonEmail


Name of the file must be  slugifyed version of the API name




PROMPT 2 : 
Create me a file SLUGIFYEDVERSIONOFAPINAME_load_PATHOFTHEPOSTOPERATION.json with an json array of candidate to be sent to the POST operation.
You should inject 20 Line

