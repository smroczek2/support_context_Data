# Simple Discount Templates
Simple Discounts Templates handle a wide variety of discount scenarios from early registration to staff and giveaway discount codes.  Simple Discounts:


* Provide you with a manageable library of re-usable discounts
* Can be added to specific events (and exclude other events)
* Can be triggered by a code
* Can be applied or adjusted administratively at any point after registration


Find Simple Discount Templates by following these steps:


1. Open the **Settings** menu
2. Expand the **Discount Templates** section
3. Click [Simple Discount Templates](https://www.ultracamp.com/admin/Config/DiscountMastersList.aspx)





## 


## Creating and Editing a Simple Discount Template


To create a new Simple Discount Template or edit an existing Simple Discount Template, take the following steps:


1. 1. Click on the **Create a New Discount Template** button or the **Edit** icon to the right of an existing template
	2. Enter the Appropriate **Basic Information**
		* Enter a **Discount Name**
		* Enter a **Default Amount**
		* Select the **Default Amount Type**
		* Check **Enabled**
	3. Select the desired **Behavior** settings
	4. [Optional] Set discount **Limits**
	5. Click the **Save Discount** button



#### 
 Note


Once your discount is saved you will need to schedule the discount in order to connect it to the appropriate session(s). You can learn about [adding your discount to sessions here](https://help.ultracamp.com/hc/en-us/articles/7228585742100-Adding-a-Simple-Discount).



## 


## Watch Video: Creating Simple Discount Templates



## 


## Simple Discount Terms and Settings


Below is a detailed explanation of each setting for a simple discount:


### Basic Information


Several of these settings are required. Enter optional information as desired:


* The **Discount Name** is required will appear to the client in several places, including the cart and reservation detail.
* [Optional] A **Description** will appear to the public on the **Discounts** page in the registration page and on the registration information page.
* [Optional] Enter a question for clients to answer in the **Question Prompt**.
* [Optional] If using a Question Prompt, you can also indicate a set of **Pre-Determined Answers** for the client to select from. Separate each answer option from the next with a comma.
* This master template can be set to be *either* a percentage- *or* a dollar amount-based discount.  A **Default Amount** must be entered, but the exact numbers can be adjusted on a session by session basis. The type of discount (dollar or percentage) cannot be tailored per session.
* [Optional] Select an **Allocation Account** from the dropdown list for financial tracking
* Verify that the **Enabled** box is checked (Unchecking it will prevent the discount from being scheduled for new sessions but doesn't unschedule it or affect sessions to which this discount has already been added.)


### Behavior


Select the desired discount **Behavior**by checking and unchecking the appropriate boxes:


* **Allow the public to alter the default value of this discount** lets clients choose their own discount amount during registration (although your default amount will show in the text field).
* The **If value is a percentage, recalculate value if modifications to the reservation are made** setting determines whether the original discount amount changes when the reservation fees are modified.  This only works for percentage-based discounts.
* For group-based sessions, UltraCamp **can apply this discount for each participant**, so that a reservation with 3 participants would receive the discount amount multiplied by 3.  This only affects group reservations and discounts that are a dollar amount.
* If the custom discount is to be publicly available for clients to select, it should be marked **visible to the public in the registration process.**
* If the custom discount should be visible on the administrative side of the registration process, it should be marked **visible in the admin registration process**.
* If you wish clients to be able to see the amount of the discount before they get to the cart page, check the box to make the **value of the discount visible in the registration process.**
* If you indicate that **this discount should be selected by default**, the client won’t need to select the discount in order to apply for it—it will be applied for automatically.
* UltraCamp can **automatically approve discounts when they are applied for** by a client.  Otherwise, an administrator on your staff must go in and review and approve the discount.
* Choosing to **display information about this discount on the session information page** will cause the discount details to show along with the Session Description, dates, and other specifics.


### Limits


Limits are an advanced setting and should be used with caution. They put permanent boundaries on who and how much this discount template can be redeemed for. You will be able to limit *when* a simple discount is open when you schedule it.


* A simple discount can be limited by an  **Age/Grade Restriction** so it only displays for and applies to individuals falling within the specified range.
* A **Maximum amount per season** can be used to limit how much is given away by this discount.  When this dollar amount is reached, the discount will no longer be able to be claimed.
* You can also restrict how many time this discount can be claimed by setting the **Maximum claims per season**.
* Setting a **Distinct Code Claim Limit** will set a maximum on the number of times a single discount Code can be claimed.


  
  



## Discount / Coupon Codes


A discount can be claimed via a discount code or codes.  A discount must be saved before you can add codes.  Once added, codes will abide by the **Behavior** and **Limits** settings specified on the discount.


To add a code, take the following steps:


1. Click “Add a new code.”
2. In the resulting popup window, you can enter a single **Code** or, by checking the **Add Multiple Codes** box, enter several codes at once.  Codes are case sensitive.
3. Select the Code Type.  There are four different **Code Types**:
	* A **Single Use** code can be used only once in the system.
	* A **One per person** code can be redeemed once for each individual who uses the code.
	* A **One per account** code can only be redeemed once in any given account.
	* A **Multiple Use** code can be redeemed once for each reservation, regardless of the number of reservations or individuals using the code.
4. [Optional] Enter a **Maximum Total Value** to set an upper limit for the total amount of money which can be given away by the discount code.  Once this limit is reached, codes will no longer be redeemable.
5. [Optional] Enter a **Maximum Number of Claims**to limit the number of times this code can be redeemed.  Once this limit is reached, the code will no longer be redeemable.
6. Click **Save Discount Code** to add the code.


Added Codes are immediately functional and can be redeemed on the cart page by clients prior to checkout.  


Discount code restrictions count across seasons and therefore can affect and restrict the redemption of a discount in subsequent seasons.  In other words, a Single Use code could only be used once ever in the system.  For this reason, it is typically recommended that old codes be deleted from the template to avoid confusion. 


## 


## Example Simple Discounts


Since simple discounts cover a variety of scenarios, here are some example discounts and their settings:


### Early Registration Discount


This discount automatically give clients a discount if they register prior to a certain date (which is set when the discount is added to a session).


* **Discount Name:**Early Registration Discount
* **Description:**Sign up early to receive $50 off your registration!
* **Default Value:**50 Dollars
* **Enabled:**Checked
* **This discount should be visible to the public in the registration process:**Checked
* **This discount should be selected by default:**Checked
* **Automatically approve discounts when they are applied for:**Checked
* **Display information about this discount on the session information page:**Checked


### Worthy Camper Scholarship Discount


With the following setup, a client applies for a 10% discount which is then reviewed and either approved and denied by an administrator. The applicant will be allowed to check out at the discounted price, but their account will show a balance until it is approved.


* **Discount Name:**Worthy Camper Discount
* **Description:**Check the box to the left to apply for our Worthy Camper Discount. Your request will be reviewed and you’ll be notified regarding your application by March 1st.
* **Default Value:** 10 Percent
* **Enabled:** Checked
* **If value is a percentage, recalculate value if modifications to the reservation are made:**Checked
* **This discount should be visible to the public in the registration process:**Checked
* **This discount should be visible in the admin registration process:**Checked
* **The value of the discount should be visible in the registration process:**Checked


### Faculty Discount


With this setup, faculty may register for an event and enter a code to attend the event for free. This is a hidden discount.


* **Discount Name:**Faculty Discount
* **Default Value:**100 Percent
* **Enabled:**Checked
* **If value is a percentage, recalculate value if modifications to the reservation are made:**Checked
* **This discount should be visible in the admin registration process:**Check
* **Automatically approve discounts when they are applied for:**Checked
* Save the discount and select it from the dropdown menu, then click the **Add a new code** Use the following code settings:
	+ **Code:**faculty123
	+ **Code Type:**Multiple Use
	+ **Maximum Value / Code Type:**0
	+ **Maximum Total Value:**0
	+ **Maximum Number of Claims:**0


### Administrative Discount


These settings create a discount that is only visible to administrators and relies is approved on a case by case basis using **Manage Discounts**on an individual account.


* **Discount Name:**Administrative Discount
* **Default Value:**0 Dollars
* **Enabled:**Checked
* **Automatically approve discounts when they are applied for:**Checked
