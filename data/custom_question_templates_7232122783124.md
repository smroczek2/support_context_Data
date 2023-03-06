# Custom Question Templates
Custom Question Templates control the behavior and data collection of custom questions. Once created, they need to be scheduled somewhere in order to be seen and addressed by clients. This is most often done through [Custom Online Forms](https://help.ultracamp.com/hc/en-us/articles/7231482555284), but it can also be done by [scheduling the question](https://help.ultracamp.com/hc/en-us/articles/7232125986836) to a specific page.   


**To make or edit Custom Question Templates:**


1. 1. In the **Settings** menu, expand the **Custom Questions** section.
	2. Click [Custom Question Templates](https://www.ultracamp.com/admin/Config/CustomQuestionsList.aspx).


Here you can create new questions or review and edit existing ones. If a Custom Question Template is attached to an online form, it can also be edited on the Layout page of the My Forms wizard.


 


#### Watch a Video about Custom Question Templates:



## 
Creating and Editing Custom Question Templates


To create or edit a custom question, take the following steps:


1. 1. Click **Create a new custom question** or click the **edit** icon to the right of an existing one.
	2. Enter the **Question Name**.
	3. Enter the **Question Asked**.
	4. Designate the desired question settings.
	5. Click the **Save Question button**.


Once you save your question, it will be displayed alpha-numerically in the list of existing custom questions.


You can delete or disable an existing question by clicking the X to the right of the listed question.


 


## Custom Question Settings and Details


Below is a detailed breakdown of each of the settings found on a Custom Question Template:





 


#### Question Name


The **Question Name** is used for identifying the question in reporting and in building forms. 


Each question should have a unique question name. Clients rarely see the question name, but it does show up as the default header for columns in the report builder.


 


#### Question Asked


The **Question Asked** is the question prompt your client will see (if the question is public).



#### 
 Note


It is not recommended to use HTML in a Custom Question template. It can interfere with printing and retrieving question answers when reporting.



 


#### Question Type


The **Question Type** adjusts the way the question presents and collects information. Indicate the Question Type by selecting an option from the dropdown.


* + **Text box Single Line:** Questions provide a single line field for clients to enter a text answer very much like the Question Name field on this page.
	+ **Text box Multiple Line:** Questions provide a text field for clients to enter a larger amount of text. The Question Asked field on this page is an example of a Multiple Line question.
	+ **Checkbox:** A Checkbox question places a single checkbox next to the Question Asked. Clients answer this question by either checking the box or not checking the box.
	+ **Checkbox List - Vertical Display:** Question type presents a series of answer options with checkboxes in a vertical list. Clients may select one or more or none of the options.
	+ **Checkbox List - Horizontal Display:** Question type presents a series of answer options with checkboxes horizontally and in columns if there are enough answer options. Clients may select one or more or none of the options.
	+ **Radio button List - Horizontal Display:** Question also presents a series of answer options horizontally and in columns if there are enough answer options. However, in this case the client may only select only one answer option.
	+ **Radio button List - Vertical Display:** Question presents its answer options one above the next. The client may only select one answer option.



#### 
 Tip


Custom Questions can be used to force clients to agree to specified terms or conditions. A Radio button Question Type with a single answer option that is required is a good way to make this happen.



* + **Dropdown List:** Displays answer options in a dropdown menu. Clients can select one answer option. The Question Type on this page is an example of a dropdown List.
	+ **Select List:** features a scrolling series of answer options. Clients usually select one answer but may use the Ctrl or Shift key to select multiple answer options at once.


#### 


#### Number of Columns:


Radio button and checkbox list question types can have their answer options displayed in a **Number of Columns**.


Use the dropdown menu to indicate how many columns in which to display the provided answer options.


 


#### Layout Type:


The question and its answer field/options can be arranged visually on the page using a **Layout Type**. 


The question can be displayed to the left with its answer field or options to the right, or the question can be displayed above the answer field or options.


 


#### Answer Options


This only shows when a question type indicates the client should choose from one or more responses provided for them, use the Answer Options field to create these responses. If you are not using a text box question type or the simple checkbox question type, you must enter at least one answer option.


* + Answer options should be typed in a comma separated list. Each comma indicates a new Answer Option.
	+ Do not use the Enter key (or hard return) when entering answers.


 


#### Answer Validation


This optional setting is designed only for text box question types. It verifies that the client's answer is either in numeric or date format. 


We recommend this feature be used sparingly if it is used at all.


 


#### Display


A custom question's display restricts who sees that question once it has been scheduled. 


* + Check the box to display on the **Public Side** to permit clients to address the question.
	+ Check the box to display on the **Admin Side** to show this question to admin users.
	+ If the box for **Adults** is checked, this question can apply to biographical information and reservations for individuals identified as adults in the system. If this box is not checked, this question will display for children and related reservations.


 


#### Require


Requiring a question, prevents the user from proceeding past this question without making a response--either an answer option must be selected or one must be typed in. 


* *In most scenarios, a question should only be required only on the Public Side, if it is required at all.*
* There are some scenarios where requiring a question be answered on the Admin Side can be a useful tool to make sure that your team members don't omit information in a registration or form.


 


#### Save Question


When creating or editing a custom question master, remember to click the Save Question button to upload any changes to your database. 


Whenever a question is saved, all instances of that question are also automatically updated throughout your database.


 



#### 
 Note


Changing a question after clients have already answered does not immediately change their answer, which is stored in a special table in the database. The next time clients see that question, however, they will be prompted to use the new answer settings and will write over their old answer.



 

