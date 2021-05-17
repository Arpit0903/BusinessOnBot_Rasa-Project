# BusinessOnBot_Rasa-Project
## Objective: 
Create a locally hosted covid chatbot on RASA 2.0
### Description: 
Build a rasa bot to share covid resources bases on pincode and category <br />
Proposed workflow for the bot. <br />
Take an Indian pincode as input and get the district/state name ** <br />
Show the available categories - using the apis provided <br />
( Take an input from the user on what he wants to get resources for ) You can use a simple menu based approach to take this input <br />
Example categories : "CoVID-19 Testing Lab","Free Food","Fundraisers","Hospitals and Centers" <br />
Based on these two inputs show results for the users - (use the api provided) <br />
After the flow ends - If a user says “corona help“ - prompt him asking if he wants to get them for the above given pincode if not - give him a provision to input a new pincode. <br />
Follow similar flow for category as well. 
<br />
For example ( let us say user asked for - Free Food in 600036 ) <br />
User :  corona help <br />
Bot : Do you want to get the resources for - 600036. Press yes to confirm and no to change another pincode <br />
User : no <br />
Bot : Please share the pincode <br />
User : 500081 <br />
Bot : Do you want to get “ Free Food” . Press yes to confirm and no to change <br /> 
User : Yes <br />
Bot : Show results for 500081 and Free Food <br />
