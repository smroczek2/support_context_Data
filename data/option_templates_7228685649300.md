# Option Templates
Option Templates are used to provide registrants additional choices within the registration process. An Option Template determines the settings for a single session option.


## 
**C****reate and Edit Option Templates**


To find where to create or edit option templates, take the following steps:


1. 1. Go to **Settings** menu and expand the **Option Templates** section.
	2. Click on [Option Templates](https://www.ultracamp.com/admin/Config/SessionOptionTemplates.aspx).


By default, UltraCamp will display your enabled options. You can also display disabled templates by unchecking the Only display enabled option templates box in the upper right. Option templates can be enabled and disabled when edited.


* An existing template will be displayed along with overview information.
* Fees are displayed to the right of the option name and broken down into Non-refundable fees, basic cost , and what is set to be collected At Registration.
* In addition to fees, the template's default Capacity will be displayed along with any restriction for Ages / Grades.
* The "Is Child" column indicates if the opportunity to select it is dependent on another "parent" option.


**To Edit an Option Template**


* Click the template name or click the pencil or edit icon to the right.


 



 


## Creating and Editing Option Templates


When you create a new option template or edit an existing one, you'll need to fill in the following required information:


1. Select an **Option Category** from the dropdown menu.
2. Enter an **Option Name**. This will display to your clients.
3. Enter an **Availability Limit**. This limits how many times this option can be chosen.
4. Fill in any optional desired fields and settings.
5. Click the **Save Option Master** button at the bottom.


Once you've saved your Option Template you will need to schedule it to a session in order for your clients to be able to interact with it. You can learn about [Scheduling Options here](https://help.ultracamp.com/hc/en-us/articles/7228701523988-Scheduling-Session-Options).


For more detailed breakdown of the different settings that can be used in each section of an Option Template, see the information below:


## Display Information Details


**Category Name**


* Select the Category Name to indicate the Category to which this option will belong.


**Sub Category**


* Within a category, a Sub Category acts as a sub-heading for an option or options. Options with the same Sub Category will be displayed together.
* Sub Categories are displayed in alpha-numeric order.
* The use of Sub Categories is optional.
* Subcategories are not designed to be lengthy but can permit up to 99 characters.


**Option Name**


* The Option Name is the actual choice your client will select.
* The Option Name will show in their shopping cart, on the Reservation Detail page, and multiple other places in the system.



#### 
 Tip


If you wish something other than the Option Name to display in custom reports, you may enter a Short Name in the text field provided. For example, this can be used to abbreviate how a report displays an option named "Adult Medium T-Shirt" to "Adult M" or just "M."



**Display**


* By default, UltraCamp displays options in alpha-numeric order.
* You can override this by setting a Display Rank within Category.
* Options with a lower rank will be displayed first and alpha-numerically within the same rank.
* For options that represent a month and day and are set up in a mm/dd format, UltraCamp can display the weekday for the current year before the description.
	+ Checking the box to **Prepend description with weekday name** will display the Option Name, the weekday for the current year, and then the description.
	+ If this option is to be selectable by clients in the registration process, check the box to **Display to public** in registration process.


**Display When Unavailable**


* When an option is no longer available for selection, UltraCamp hides it from the public view.
* You can override this setting so when this option is closed, it is still listed (but not selectable) along with other options by checking the box to **Display to public when unavailable**.
* Check the box to **Display this option on the Session Information page** along with the Session Description for any session to which this option is attached.


**Option Quantity**


* If Clients can purchase more than one of this particular option, check the box that **Clients need to specify the quantity being purchased**.
* This will add a quantity field to the left of the Option name. This field defaults to 1 but can be adjusted during option selection in the registration process.
* By default, UltraCamp only displays whether or not this option is available. However, you can Display the number of available spaces / items remaining by checking the appropriate box.
* On the option selection page in the registration, clients must select their desired options by checking the box or button to the left of the option name.
* However, by checking the **Display selected by default** box, this option will be pre-selected for them.


 


## Fees Details


**Non-refundable Fee**


* An option’s total fees are determined by the combination of the Non-refundable Fee and the Cost (less deposit).


**Cost (less deposit)**


* The amount to Collect at Registration can be adjusted here.
* This amount will be collected in addition to the fees the Session is set to collect at registration.
	+ Exception is when sessions set to “Collect all fees at registration,” in which case the fees for this option would be collected anyway, regardless of the Collect at Registration amount).


**Free to Age/Free Over Age**


* This option can be set to be Free to Age and / or Free over Age which prevents this option's fees from applying to people below or above the specified ages respectively.


**Cancellation Fee**


* A Cancellation Fee can be set to automatically apply to a client’s account should they cancel or remove this option from their reservation.
* This is in addition to any Non-refundable Fee.


**Allocation account**


* If this option’s fees need to be tracked separately from other fees, you can indicate a distinct Allocation Account for this specific option.


 


## Availability Details


**Availability Limit**


* The Availability Limit determines how many of this option are available to your clients.
* This is a required field--even if you offer an essentially unlimited number, you will still need to put something in this space. For example, you could enter 9999 as the availability limit.


**Age/Grade Restrictions**


* You can restrict the availability of this option by Age or Grade using the dropdown menu.
* If you choose to limit availability this way, you may then set Minimum and Maximum parameters in the resulting fields.
* If this option is used with group reservations, you can have UltraCamp charge the fee for this option per paying registrant.
* Check the box to enable this feature so that With group reservations, [UltraCamp will] count and charge as one per paying participant.


 


## Additional Settings Details


**Confirmation Note**


* If this option is selected, a special Confirmation Note can be included in the Confirmation Email.
* Type in this field to add the note.


**Option Documents**


* UltraCamp can also attach pdf Option Documents to the Confirmation Email if this option is selected.
* These documents must be uploaded separately (in the Settings Menu) and will attach in addition to any other Confirmation Email documents.


**Option Online Forms**


* When an Option Online Form is selected, UltraCamp will prompt the client to fill out the checked Custom Online Form.
* If this form is not otherwise added to the registration process, only those who choose this his Option Online will see the online form.
* This feature can be used for waivers connected with an optional feature—like a day rafting trip—or a financial aid request that triggers an application form.
* The selection of this option can trigger an Option Payment Plan to display in the checkout process if that payment plan is checked here.



#### 
 Tip


An example of using this feature would be with an option to apply for financial aid. The selection of this option would trigger a payment plan unique to Financial Aid applicants - perhaps a plan where they can check out without paying.



**Nest Options**


* UltraCamp can nest options from one category within options from another.
* If this option shows up only if another option is chosen first, indicate that **This option is a child** of the triggering option by checking the box to the left of the triggering option.
	+ For example, if Hot Lunch is an option for this program, selecting the Hot Lunch Option could then trigger a Sandwich, a Spaghetti, and a Pizza option. The specific meal options - Sandwich, Spaghetti, and Pizza - would each be marked as a child of the Hot Lunch option.


**Allow Cancellations or Quantity Reductions**


* By default, UltraCamp does not allow a client to cancel or reduce their option selections.
* If you want to permit this behavior, check the box to Allow cancellations or quantity reductions .


**Enable Check In/ Check Out Feature**


* By checking the box to Enable the check in / check out feature , you can use the Session Options Roster to mark the option Fulfilled.


 


## Update, Delete or Save Details


**Update All Flexible Settings**


* Once an option is saved, a checkbox to Update all flexible settings to all upcoming scheduled options to match these settings will appear.
* Changes to flexible settings on the Option Template will not normally affect options that are already scheduled.
* If you make a change to a flexible setting on the Option Template and wish to push this change to already scheduled options (for current and future sessions), check this box and click the button to save the Template.


**Delete this Master**


* Deleting an option template will remove it from all upcoming sessions as well as remove the template from the list.


**Save Option Master**


* Whether creating a new option or editing an existing one, you must click the Save Option Master button at the bottom of the page.


  
  


