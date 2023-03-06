# Custom Online Form - Basic Settings
## Custom Online Forms


Custom Online Forms are used to gather information about your clients. Custom Online Form data is attached to individuals or accounts. You can [add Custom Online Forms to the registration process](https://help.ultracamp.com/hc/en-us/articles/10556700559380) or link people to the forms directly. You can even have a third party fill out data on a form and have that information attach to an individual or account. 


When creating a custom online form, you will use the My Forms wizard to:


* Determine form behavior on the Basic Settings page.
* Specify how a form is marked Complete.
* [Optional] Set up form-specific automated email notifications.
* Add text and questions to communicate and collect information.


  
  



## My Forms Wizard


The My Forms wizard primarily uses 4 pages to set up your form. Each page is detailed below. Expand the "Details" section to review the more advanced setup options on that page.


To access the My Forms Wizard:


* Go to **Settings**
* Expand **Systems/Management**
* Click on **My Forms**


  
  



## Basic Information


On the Basic Information page, you must address the following settings:


* **Specify the Form Name:** This will be used to identify the form to your clients as well as in your reporting.
* **Choose if the form will be For Individual or Account:**Your selection determines if the form data will be attached to individual people or to the account in general.
* **The Form Type defaults to Standard:** Completed by the Account Holder, but you can change this to Third Party Reference Form for situations where you want the information to be filled out by someone outside the account (like for a staff application reference).


  
  



## Basic Information Page Details


#### **Basic Information**


* **Form name:** Enter the name you wish to identify the form by
* **Category:**Categories are used to group forms. Enter text to create a new category or select one from the dropdown menu to use an existing category.
* **Form Description:** Descriptive text entered here will only ever appear beneath the Form Name in the Document Center on the public side.
* **For Individual or Account:** Use the dropdown to select whether the data for the form attaches to an *Individual* or the entire *Account*. Selecting Account will cause the form to display under the Primary Contact, as well as on the Account Detail page.
* **Contains Medical Information:** Checking this box will restrict access to those with the appropriate Medical user access.
* **Form Type:***Standard - Completed by account holder*is the default and used for most forms.
	+ Selecting Third Party Invite will change the behavior of the form.
	+ Instead of the account holder filling out the form directly, they will instead complete an "Invite" page which includes the email address of the Third Party.
	+ When the invite is completed, the form will be sent to the specified email address or "Third Party" who can then fill out the form. The form is then saved on the original individual's account.
	+ The Third Party does NOT need to have an account in UltraCamp to fill out the details.


#### **Visibility**


* **Allow the public to access this form outside the registration process:**
	+ This lets a person see, review, and edit the form after they first access it.
* **Allow the public to access this form from the document center:**
	+ This lets a person see, review, and edit a form directly without encountering it first via a link or registration.
* **Completed third-party forms are private and should not be visible to the public:**
	+ This only shows for Form Type: Third Party Invite.
	+ Checking this box will keep the Third Party's answer hidden from the account holder.


  
  



#### **Restrictions**


* **Age Restrictions**can be set for the form if it is set to attach to an Individual.
	+ UltraCamp will check the Individual's age at the time the form would be filled out to see if they should be given access.
	+ Individuals who are not currently within the set Age or Grade limits will not see the form.
* **Allow an "On File" option:** lets an admin designate that they have a hard copy of the data for reporting purposes. This does not put any data into UltraCamp.


#### **Expiration Settings**


The expiration settings determine how long UltraCamp considers form data to be up to date. 


* Set the **Expiration Type**to one of the following:
	+ **Each Season:**(the default) marks form data out of date at the end of the season in which they complete the form.
	+ **Never Expires:** means UltraCamp never marks form data as out of date.
	+ **Always New:**means UltraCamp never marks form data as out of date but saves each completion or edit of the form as a new dataset.
	+ **After X Days:**allows your organization to specify a specific number of days before UltraCamp marks form data as out of date.
* An **Expiration Grace Period** can be used to extend the time a form is considered up to date in UltraCamp.
* Setting the form to **Display only once per season** will prevent the form from showing up in subsequent registrations during the same season. It can still be accessed from the Document Center.


#### **Due Date Settings**


* Due date settings can put an alert on an account for Required Forms as designated on a session.


 


## Completion Acknowledgment


Use the Completion Acknowledgement page to specify how a form is identified as finished or up to date. You must address these settings for your form to function properly.


* For the **Completion Acknowledgement Type**, your choice will determine if a client can skip required fields and save their progress (*Ask if the form is complete*) or has to fill out all required fields before saving their progress (the other two options).
* **Signature Collection** can generate a certificate of authenticity by taking the clients chosen signature, IP address and time stamp if you choose Electronic Signature.


## Completion Acknowledgment Page Details


For the **Completion Acknowledgment Type**, choose:


* *Do not ask if the form is complete* if you just want a "Next" button to appear at the bottom of the page. Clients must fill out all required fields in order to proceed to the next page in the registration process.
* *Ask if the form is complete* to permit clients to say the form is complete if they have filled out all required fields or that they'll finish it later (and skip any required fields). If they choose to fill the form out later, they will be able to continue with the registration process. You can customize the text for both options in the text fields provided.
* *Require clients to attest that the form is complete* forces clients to fill out required fields and acknowledge that they are finished before proceeding to the next page. You can customize the acknowledgment text in the field provided.


For **Signature Collection** choose one:


* *None* -- No signature will be required.
* *Collect Electronic Signature* - This will require clients to agree to and choose an online signature. UltraCamp will then generate certificate of authenticity with their signature, time-stamp, and IP address. A copy of this certificate will be saved on the account as a pdf which preserves the form and answers as they were at the time of signature.
* *Hard Copy* - This will email the client a copy of their answers for them to print out and sign. They can then return this signed copy to your organization.


 


## Notifications


This page should really only be used in situation where the form is not part of a registration process or if you need someone to review each form as it is submitted.


You can designate notifications To Clients on this page when they first complete the form and/or when they update it. You can also designate notifications To Staff for the same.


  
  



## Notifications Page Details


#### **To Clients**


This section sets up notifications that go to the account holder for the form. Custom messaging can be added to these notifications.


* The box to **Send email confirmation to clients upon completion** will trigger an email to the Primary Contact the first time a form is completed.
* The box to **Send email confirmation to clients upon update** will trigger an email to the Primary Contact any time they update or mark the form as complete.


#### 


#### **To Staff**


This section sets up notifications to send to a designated admin user.


* The dropdown menu for **Send notifications when updates are made to a completed forms** will trigger an email to the selected staff member whenever a client modifies a form that was previously marked Complete.
* The dropdown menu for **Send notifications when updates are made to all forms** will trigger an email to the selected staff member any time the form is updated and its data is saved.


 


## Layout


The **Layout**page is where you add text and questions to communicate and collect data. Once added, text and questions can be re-ordered by dragging the desired block up or down the page. Click the **Complete**button to save changes on the Layout page to your database.


* Use the **Add existing questions** feature to pull a Custom Question from your library of templates into the form.
* Use the **Add a new question**feature to create a new Custom Question Template and drop it into the form.
* Use the **Add text** feature and select a Display Style to create Headings, Subheadings, and Directions blocks of text.



#### 
 Note


If you close the Layout page or navigate away from it without clicking the **Complete**button, your changes will not be saved to your database! Custom Question Templates will go into your library, but they will not appear on the form unless you add them again. Text is lost.


If you are going to be making multiple changes or building a form of any length, check the box at the bottom to **Stay on this page** and then click the **Complete**button often to make sure your work isn't lost!



 


## Layout Page Details


#### **Add existing questions**


Click this link to see a list of existing Custom Question Templates. In the pop-up box you can:


* Check the box to the left of any template you wish to add.
* Click the **Add Questions** button at the bottom to connect selected templates to the layout.


A Custom Question Template can only exist once on a single form but can be used on multiple forms (each will have its own stored set of answers).  
  
  



#### **Add a new question**


Click this link to create a Custom Question Template from scratch and automatically add it to your layout. In the pop-up box you will address the following settings:


* **Question Name** -- Title used for reporting on data collected through this question.
* **Question Asked** -- The prompt visible to your clients when addressing the question.
* **Question Type**-- Sets the question style.
	+ *Textbox Single Line* is for short answers and can have a set **Maximum Length**.
	+ *Textbox Multiple Line* is for longer answers and can have a set **Maximum Length**.
	+ *Checkbox* is so that clients can answer this question by either checking the box or not checking the box.
	+ *Checkbox List - Vertical Display* permits clients to select multiple answers or none from a vertical list of **Answer Options**, which you provide via a comma separated list.
	+ *Checkbox List - Horizontal Display* permits clients to select multiple answers or none from a horizontal list of **Answer Options**, which you provide via a comma separated list.
	+ *Radio button List - Horizontal Display* permits clients to a single answers from a horizontal list of **Answer Options**, which you provide via a comma separated list.
	+ *Radio button List - Vertical Display* permits clients to a single answers from a vertical list of **Answer Options**, which you provide via a comma separated list.
	+ *Dropdown List* prompts clients to a select single answers from a dropdown list of **Answer Options**, which you provide via a comma separated list.
	+ *Select List*prompts clients to select a single answer from a scrolling textbox list of **Answer Options**, which you provide via a comma separated list. Clients can select more than one answer by holding the Ctrl or Shift key and clicking additional answer options.
* **Layout Type** -- positions the question and answer fields based on your layout preference.
* **Answer Validation** - Used only for textbox questions to require the answer be either *Date*or *Numeric*in format.
* **Display** -- sets who can see the question on the form.
* **Require** -- prevents users from marking the form as done without addressing the question. In most scenarios, a question should only be required on the Public Side.


Click the **Complete**button to save your Custom Question Template and add it to the layout.  
  
  



#### **Add Text**


Click this link to add a block of text to your layout. In the popup window you can:


* Enter **Text** into the large textbox by typing or pasting from another document.
* Set the **Display Style**using the dropdown menu. Each display style has a different look:
	+ *Heading* is bold and larger font and displayed in a dark gray bar for emphasis.
	+ *Sub-Heading* is bold and in a lighter gray bar.
	+ *Directions* text will display as normal based on the font and color settings chosen on your public side.


Use the Save >> button to add the text to your layout.  
  
  



#### **Edit and Delete**


Text and Custom Question Templates that are added to the Layout page can be edited by clicking the Edit link to the right of the block.


Text and Custom Question blocks can be moved by clicking on the block and dragging it up or down (although this process can be a bit fussy).


Text and Custom Question blocks can be removed by using the **X** icon to the right of the block.


 


#### **Form Data and Editing**


Here are some important notes about editing existing Custom Online Forms:


* All responses to Custom Question Templates are stored in a specific table in the database. If a question is removed from a form, all data related to that question is wiped from the table and lost.
* UltraCamp only saves the most recent response to a question on a form, writing over previous answers unless the form Expiration is set to "Always New." In this case, custom reports only return the most recent response data.
* Changing the question prompt does not affect stored answers on a Custom Question.


 



#### 
 Note


If you want to learn how to add your form to the registration process, check out our article on [Setting your Registration Page Order.](https://help.ultracamp.com/hc/en-us/articles/10556700559380)


