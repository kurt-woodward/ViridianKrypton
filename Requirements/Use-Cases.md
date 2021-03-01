# ViridianKrypton
	
##	Use Cases:
>	Given _________
	(and  _________)
	When  _________
	Then  _________
	
Given a scan file
and a users' private health information (PHI)
When a scan is created or uploaded
Then encode the PHI on the scanfile according to accepted standards
	
Given user credentials
When user logs in to the system
Then retrieve the user's profile
	
Given user preferences
When a scan file is uploaded
Then produce copies of the scan file at vaying levels of detail and anonymity
	and Store the copies in the appropriate data warehouses
	
Given an authorized access request
When requested by a user or system
Then return the correct version of the scan file
	
Given user credentials
When user logs in
Then establish end to end encryption to protect data in transit
	
Given user authorization
When user requests their account and PHI be removed
Then Completely remove their account and PHI

Given authorized access request
When data is transmitted for retail / advertising / manufacturing
Then transmit the minimum data necessary 
>(That is to say, transmit enough that a retailer can say "this item best fits the customer", but the scan model and the retailer's model of the clothing item should be joined either at the customer's device or at the scan repository. The retailer should never have direct access to the scan.)

Given enough scans
When requested by researchers or public health officials
Then provide population-level averages and other metrics

##### License
Copyright: Kurt Woodward (2021)
All rights reserved.
