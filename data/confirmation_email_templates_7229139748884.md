# Confirmation Email Templates
## Confirmations Templates


Confirmation Templates (sometimes called "Confirmation Masters") control the email confirmation that is sent to a client when a reservation is completed. 


* These master templates must be connected to a Session Master in order for the designated message to be sent out.
* Updates to Confirmation Masters immediately adjust that message from that point forward but do not affect previously sent messages.


**To create or edit a Confirmation Master:**


1. 1. Go to **Settings menu.**
	2. Expand the **Communication** menu.
	3. Click on **Confirmation Templates.**
	4. Click **Create a new confirmation master**or click on the edit icon next to an existing confirmation master.


 


## Templates for confirmation emails


### Email Notification


**Name**


* The name for the Confirmation Master does not show to the public.
* Primarily used to make sure you connect the right Confirmation Master to the right Session Master/Template.


**Send Option**


* Determine how to handle multiple reservations for a single individual or prevent emails from sending at all.
* Choose Send an email for each reservation to transmit a separate email for each session for which a client registers.
* Selecting Group multiple reservations into a single email will combine all confirmation emails with the same Confirmation master into a single summary email.
* You can also turn off confirmation emails by selecting Do NOT send email confirmations.


**Mark Confirmed When Sent**


* This checkbox is selected by default.
* When checked, the Confirmation Setting on the reservation will be set to “Confirmed” when the confirmation email is sent, indicating that the primary contact has been sent communication regarding their reservation.
* Un-checking this box will deactivate automatic confirmation and require manually marking individual reservations as “Confirmed” in order use that tracking tool.


**Email Subject Line**


* You can replace the default Email Subject Line by typing your own text in the blank field.


**Send Email From**


* The originating email address can be chosen from the Send email from dropdown menu.
* These emails are generated from the My Settings wizard as well as your list of authorized users.



#### 
 Tip


Authorized users are created under Users in the Settings menu.



 **CC Field**


* Entering an email address in the CC field will generate and send a copy of the confirmation email to that address.


**Body of Email**


UltraCamp will generate automatically a large portion of the email notification. 


* You can add additional text by typing it into the Body of Email field.
* Users comfortable with HTML can use proper coding to further format their email, and if this is done, be certain to check the **This content is HTML**






#### 
 Tip


To format or add a link to the confirmation master, check the **This content is HTML**box.



 


* In the text box, add the your link using the HTML code below:


<a href="*insert your link*">*insert word or sentence*</a>


* The example below shows how to make the word UltraCamp a link.


**HTML:**Here is a link to<a href="www.ultracamp.com">UltraCamp</a>.  
**Result:**Here is a link to [UltraCamp](www.ultracamp.com).


 


### PDF Confirmation


UltraCamp can include a pdf confirmation/receipt as an attachment to the emailed confirmation. 


* The PDF is generated automatically, but additional text can be added in the Body of Confirmation field.
* Checking the box to Display Alternate Contact Info will print the contact information for the Alternate Contact in the pdf.


 


## Additional Documents


Additional Documents can be attached to the Confirmation Email. 


* Documents that are uploaded in the Settings menu will display as checkboxes here.
* Checking the box to the left of a document name will cause that document to be attached to all confirmation emails generated using this Confirmation Master.
* Preview documents by clicking the document name.
* You can also attach the Account Statement by checking the appropriate box.
