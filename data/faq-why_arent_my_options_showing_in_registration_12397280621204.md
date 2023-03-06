# FAQ: Why aren't my options showing in registration?
There are several common reasons why your options might not be showing in the registration process. Here are the most common culprits and how to identify and fix them:


 


## Reason #1: Options Aren't Scheduled


Options must be scheduled in order to show in registration. Here's how you can identify if your options are scheduled and how to add them if they are not.


**To see if your options are not scheduled, take the following steps:**


1. 1. Open the **Session Editing wizard** for the session you are testing.
	2. Proceed to the **Session Options** page in the Additional Information section.


If your options are scheduled, you should see them listed on the page. *If they aren't showing here, you will need to schedule them.*


 


#### Solution:


**Here is how to schedule missing options:**


1. 1. Open the **Session Editing wizard** for the session that is missing options.
	2. Proceed to the **Session Options** page in the Additional Information section.
	3. On the Session Options page, click **Add Options**.
	4. In the popup window, locate your missing options in the list and check their box.
	5. Click the **Add Options** button at the bottom of the popup window.


Your options should now show in the registration process.


 



#### 
 Tip


You can add a single option to multiple sessions at once using our [Schedule Options](https://help.ultracamp.com/hc/en-us/articles/7228701523988-Scheduling-Session-Options#adding-a-single-option-0-2) feature.



 


## Reason #2: Options are Full


If your options have reached capacity, they may be hidden from public view. Each option has a setting that says "Display to public when unavailable" on the Option Template. If this box is not checked, an option that reaches capacity will be hidden from view in public registration.


**Here's how to check if your options are full:**


1. 1. Go to the **Reports menu** and expand the **Rosters** section.
	2. Click [Session Options Roster](https://www.ultracamp.com/admin/Reports/sessionOptionsReport.aspx)
	3. [Optional] Check the box for the missing option and/ or the session you are investigating.
	4. In the **Report Type** dropdown menu, select **Summary**.
	5. Click the **Search** button.


Your options will be listed along with the your current capacity and enrollment. You should be able to identify any options that are full using this report.


If your options are full, you can increase the capacity or change the visibility for full options.


 


#### Solutions:


**To increase your capacity for an option, take the following steps:**


1. 1. Open the **Session Editing wizard** for your session.
	2. Proceed to the **Session Options** page in the Additional Information section.
	3. Click on the name of the Option you wish to adjust.
	4. In the popup window, enter the new **Availability Limit**.
	5. Click the **Save Option** button.


Your capacity / availability limit for this option has now been updated. You can also [Bulk Update Scheduled Session Options](https://www.ultracamp.com/admin/bulkUpdates/bulkUpdate_options.aspx) to perform this change across multiple sessions or options all at once.


 


**To change the visibility for full options, take the following steps:**


1. 1. Go to the **Settings** menu and expand the **Option Templates** section.
	2. Click [Option Templates](https://www.ultracamp.com/admin/Config/SessionOptionTemplates.aspx).
	3. Locate your option template and click on it.
	4. In the "Display Information" section, check the box to **Display to public when unavailable**.
	5. Click the **Save Option Master** button at the bottom.


Your option will now continue to be visible when full, but it will be marked as full and will not be select-able for public registration. This is a fixed setting and will therefore affect all options scheduled from this template. You can use the [Bulk Update Option Templates](https://www.ultracamp.com/admin/bulkUpdates/bulkUpdate_optionMasters.aspx) to perform this change across multiple templates at once.


 


## Reason #3: Options Aren't Visible to Public


Option templates can be set to be visible to the public, visible to admins, or both. If these settings are not enabled, options will not be displayed to the designated user.


Here is how to check the visibility settings of an option:


1. 1. Open the **Session Editing wizard** for the session you are testing.
	2. Proceed to the **Session Options** page in the Additional Information section.
	3. Click the name of the Option you wish to check.


In the pop-up window, you will find the checkboxes for "Visible to Public" and "Visible to Admin." If the box is checked, this option will be visible to the designated user group.


 


#### Solution:


**To change the visibility settings for options, take the following steps:**


1. 1. Go to the **Settings** menu and expand the **Option Templates** section.
	2. Click [Option Templates](https://www.ultracamp.com/admin/Config/SessionOptionTemplates.aspx).
	3. Locate your option template and click on it.
	4. In the "Display Information" section, check the box to make the option **Visible to Public**.
	5. [Optional but recommended] In the "Display Information" section, check the box to make the option **Visible to Admin**.
	6. Click the **Save Option Master** button at the bottom.


Your option will now show in the registration process.


 



#### 
 Tip


Option Visibility settings can be adjusted through the [Bulk Updates](https://help.ultracamp.com/hc/en-us/articles/7228698449428) tool. Since Visible to Public and Visible to Admin are flexible settings, you will want to use the tool to [Bulk Update Scheduled Options](https://www.ultracamp.com/admin/bulkUpdates/bulkUpdate_options.aspx).



 


## Reason #4: The Options Page Isn't in the Registration Process


Some options may not show in registration based on their **Option Category** settings and **Registration Page Order** settings. Evaluating these settings can be a multi-step process so follow these steps carefully:


 


#### Step 1: Determine Option Category Settings


Option Category settings determine if Options need to be added to the Registration Page Order. The key Option Category setting is **Page Display Type**.


Here is how to check the Option Category Settings:


* + Go to the **Settings** menu and expand the **Option Templates** section.
	+ Click [Option Categories](https://www.ultracamp.com/admin/Config/SessionOptionCategoriesList.aspx).
	+ Locate the category for the desired options and click the edit icon to the right.
	+ The dropdown menu for **Page Display Type** shows the selected settings.


Option Categories have three possible types of display:


* + Share page with other categories
	+ Display on its own page
	+ Collect multiple session selections on a single page


*If an Option Category is set to **Share page with other categories** or to **Display on its own page**, options must be included in the Registration Page Order.*


If the option category is set to "Collect multiple session selections on a single page," the options will always show at the end of registration regardless of page order settings.


 


#### Step 2: Determine Page Order Settings


Page Order can be set in two places:


* + On the individual Session
	+ On a Page Order Template attached to the Session Template


The simplest way to determine which Page Order approach is being used is to take the following steps:


* + Open the **Session Editing wizard** for the desired session.
	+ Go to the **Registration Page Order** page in the **Basic Setting** section.
	+ If the page displays two columns of blocks in different colors, the Page Order is controlled on this page in the session.
	+ If the page says "The session master for this session is using the page order template..." you are using a Page Order Template.


 


#### Step 3: Ensure the Options page is in the Registration Page Order


Once you've determined how the Page Order is controlled, you can ensure the Options page is included in the Registration Page Order.


**If your Page Order is set in the Session, use the following steps:**


* Open the **Session Editing wizard** for the desired session.
* Go to the **Registration Page Order** page in the **Basic Setting** section.
* If the Options is not listed in the right-hand column, click and drag it into the Registration Page Order.
* Click the Complete button to save your changes.


This session is now updated. You may have to repeat these steps for other sessions or use the Copy Session Settings wizard to copy this Page Order to other sessions.


 


**If your Page Order is set on a Page Order Template, use the following steps:**


* Open the **Session Editing wizard** for the desired session.
* Go to the **Registration Page Order** page in the **Basic Setting** section.
* Click the link in the text "To make changes to the page order template, click here."
* If the Options is not listed in the right-hand column, click and drag it into the Registration Page Order.
* Click the **Save Option Template** button.


All sessions that use this Page Order Template will now be updated to these settings.


 

