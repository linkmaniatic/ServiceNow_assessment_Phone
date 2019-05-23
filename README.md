# ServiceNow_assessment_Phone
Assignments –


1. Create a role "Phonerole"
2. Create a user "Experiment"
3. Add the role "Phonerole" to the user "Experiment".
4. Create a table "Phone" with below specifications"
  - Name -String -maxlength(100)-Mandatory
  - Model -String -maxlenght(10)-Mandatory
  - Price-Integer -maxlength(15)-Mandatory
  - OS- Choice-choicelist(Android,Windows,IOS)-Mandatory
  - Comments-String-maxlenght(200)
  - Add the default role of this table to the role "Phonerole".
 
5.Create an ACL and map it to the role :"Phonerole" so that only the field "Model" is Writeable.

1) Create an application “Demo Application” and a module “Demo module” .Create a user “Demo ITIL” and assign “itil” role to him. Check whether the application been created is visible to the user.
2) Make use of dictionary override to display by default ‘new’state  for the incident and problem table.
3) Create an import set , transform map and load the data.
4) Create an update set to capture the catalog item , variables and variable sets.
5) Create an SLA called as “Request fulfilment” on the table “Request ( sc_request)”
Duration should be 14 hours , schedule – 8 – 5 weekdays excluding holidays.
( Create this schedule prior to the SLA creation ) .
Timezone – US/ Pacific
Start condition – active to true and approval is approved
Stop condition – state is closed complete
6) Display ‘short description’ field to be read only when the form gets loaded.
7) Hide Subcategory field of the incident when category is “Inquiry / Help”.
8) Write a on load script to display an alert message box
9) Write a on change script to generate two alerts :
1) If the new priority is greater than the old priority generate an alert that’s says
The incident priority has been escalated.
2) If the old priority is greater than the new priority generate an alert that’s says
The incident priority has been decreased.
10) Write a on submit script for the following pseudo code –
When the form is submitted ,
If the priority is critical and the user does not have the admin role –
Display a confirmation box asking if the user really wants to submit a critical priority incident
If the user cancels the submission
Generate an alert asking that the incident was not submitted.
Add a field message below the urgency field
Return true or false based on the confirmation box response.
11) Restrict user to enter only past dates on Actual Start time field on incident.
12) Create a business rule that will not allow insertion of a user into sys_user until email is valid
13) Create a table called "Info" with a field called "Description". Create another table called "BackUpInfo" with a field called "Description". Create a business rule on "Info" such that whenever the records are inserted or updated in it, it is also reflected in "BackUpInfo" table.
14) Create an ACL to make “updated” field not visible to itil users.

