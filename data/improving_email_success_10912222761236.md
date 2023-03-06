# Improving Email Success
In order to provide the most reliable communication with your clients, we recommend that you implement *one* of the following two tweaks to your email setup:


* + Create at least one Email Sending Scheme.
	+ Add 'sender.ultracamp.com' to your SPF record in your email domain.


As email service providers improve security, using one of these techniques will help your emails avoid being flagged as spam or junk mail.


 


## Setting up an Email Sending Scheme


An Email Sending Scheme allows UltraCamp to send emails directly from your email server. This is the most effective way to make sure your emails are transmitted securely and reliably. *Because of the nature of these settings, it is important to work closely with your IT team when setting up and managing any email sending scheme.*


**To find where to create or manage Email Sending Schemes:**


1. Go to the **Settings** menu and expand the **Communication** section.
2. Click [Email Sending Schemes](https://www.ultracamp.com/admin/Config/EmailSendingSchemesList.aspx)


Here you can create new email sending schemes or edit existing ones.


 


#### Creating an Email Sending Scheme


In order to give UltraCamp the ability to send emails through your server, you'll need to create at least one Email Sending Scheme. To do this, take the following steps:


1. 1. Click the button **Create a new email sending scheme**.
	2. Fill in each of the fields provided.
		* The **Email Address** is the one you wish to send emails from.
		* The SMTP Host and Port, along with the IMAP Host and Port are based on the settings of your email host service.
		* The **Username** and **Password** must match permissions for your email provider.
	3. If your server necessitates the use of SSL, check the box to **Enable SSL**.
	4. [Optional but Recommended] In the **Test Connection** section, enter an email address into the **Send To** field and click the button to **Send Test Message**.
		* A notification will appear at the top of the screen, explaining if the test was successful or not.
	5. Click the **Save Scheme** button.


UltraCamp will now use these settings to send emails through your server. ***If there are any changes to the password or permissions at your service provider, these settings must be updated here as well.*** Failing to do so will prevent emails from being sent from UltraCamp using the specified address.



#### 
 Tip


For consistent communication, it is best to create an Email Sending Scheme for each email address you will use to communicate with clients.



 



#### 
 Note


Since you are now sending notifications through your email service provider, any limits on your email account will also impact the sending of emails from UltraCamp.


For example, if you are limited to a maximum number of emails sent per day, UltraCamp will no longer be able to send messages when that limit is reached. This would affect email receipts, automated reminders, confirmations, etc.



 


## Adding sender.ultracamp.com to your SPF Record


SPF is a security protocol that helps keep your email from being impersonated. Your SPF record determines which domains have permission to send emails on your behalf. Adding sender.ultracamp.com to your SPF record tells other security systems that our servers have permission to send on your behalf. This approach may not be as as effective as creating an Email Sending Scheme, but it does improve UltraCamp's ability to communicate with your clients. 


 


*Because the SPF record is part of your domain DNS record, it is important that you work with your IT team when making this kind of change.*



#### 
 Tip


If you'd like to verify that sender.ultracamp.com is already in your SPF record, you can find tools which will search this for you. Here is just one [web based tool](https://mxtoolbox.com/spf.aspx) that can be used to check for a specific SPF record.



 


## What if I just use the default settings?


UltraCamp's default behavior for communicating with your clients is to send emails from our email servers (usually from the unmonitored email: [notices@ultracamp.com](mailto:notices@ultracamp.com)) on behalf of your designated email address(es). Clients who reply to these emails will have their messages go directly to your email address.


Unfortunately with the increased security precautions email providers are taking, we are finding more and more messages using the default setup are being stopped from reaching your clients. We cannot guarantee that emails sent with the default setup will get through.


 



#### 
 Tip


No matter what email setup you decide to use, your clients can always log into their account to view any messages sent to their account through UltraCamp's **Message Center**.


