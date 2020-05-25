User Case ID | User Story 505: Match customer based on RM's Profile
------------ | --------
User Story | As a RM i want to be able to be matched with customer's based on my profile so that i can provide the best experience for customers.
Goal | Successfuly match a RM with a customer based on the strengths listed on the RM's profile. These may include Language proficiency, product knowledge & expereience. 
Priority | High
Actors | <ul><li>Primary - Customers & Relationship Manager</li><li>Secondary - N/A</li></ul>
Pre-conditions | <ul><li>Customer has access to a phone</li><li>Customer has the number of the company</li><li>Their are currently relationship mangers available to take calls</li></ul>
Post-conditions | <ul><li>Customer is Matched with a Relationship Manager</li></ul>
Trigger | Customer dials the company's mobile number
Main Flow | <ul><li>Customer rings the CMC system</li><li>CMC gathers pass information on the customer & relation managers</li><li>CMC creates a match between a relationship manager & customer. </li><li>CMC redirects the customer to a relationship manger’s phone.</li></ul>
Exceptions | <ul><li>Customer hangs up the phone</li><li>CMC system is down<li/></ul>
Includes/Extends/InherIts | Extends US
Non-functional Requirements | CMC must match  a customer & relationship manager within 3 minutes

Alternate Flow 1 | Line is Busy
---------------- | ------------
Trigger | Currently all RMs are busy and unable to take calls
Step | <ul><li>CMC tells the customer that currently all the RM are busy & give an estimated wait time</li><li>Customer waits the estimated wait time</li><li>CMC redirects the phone call to the next available RM</li></ul>
Post Condtions | Customer is match with a RM
Exceptions | <ul><li>Customer does not want wait & hangs up</li></ul>


