# Allocation Account Setup for Financial Tracking
UltraCamp offers a variety of financial reporting and tracking features, but you can get more out of these tools with Allocations Accounts. Allocation Accounts help you categorize and track how money is spent by your clients. Here is how they are intended to work:


* When payments are entered into UltraCamp, the funds are allocated toward reservations and other financial items.
* Your allocation accounts group those funds as needed for reporting.


Allocation Accounts can be assigned to every financial item in UltraCamp (except Care Pricing). This makes it possible to separate or combine income from different places, session types, or options, and that's just the beginning! Many organizations find Allocation Accounts make a convenient parallel to General Ledger accounts for bookkeeping that occurs outside UltraCamp.


 


To make the most of this powerful tool, you will consider the following steps:


* Creating Allocation Accounts.
* Defining any additional transaction types
* Adding Allocation Accounts to your financial items


## 


## Creating Allocation Accounts


To create Allocation Accounts:


1. 1. Go to the **Settings** menu and expand **Accounting**
	2. Select **Custom Allocations Accounts**
		* If you are using a **cash basis** for your accounting system, you will only need to fill in the Account Number (Cash) field.
		* If you are using an **accrual basis** for your accounting system, you will want to configure all four columns.


 


![custom_allocations.jpg](https://help.ultracamp.com/hc/article_attachments/9509919841684/custom_allocations.jpg)


*Example of Allocation Accounts configured for an accrual accounting setup.*


### 


### The 4 types of Allocations


* **Cash** - This assigned account will apply to all transactional information in the system such as payments (credits) or refunds (debits).
* **Receivables** - This assigned account will apply to sale entries that are past their due date and are unpaid.
* **Sales** - This assigned account will apply to sale entries that are due in the future.
* **Realized** - This assigned account will apply to sale entries that have reached their due date and are paid.


## 


### Default Allocation Accounts


UltraCamp has two built-in allocation accounts that you should set:


* Refund Liability Account
* Cash Account



#### 
 Note


It is important that you create a dedicated account in your Accounting system to handle Refund Liability.



### 


## Assign Allocation Accounts


Once your allocation accounts are created, assign them by going into the Settings menu and taking the following steps:


* Locate the Template or Category
* Click the Edit icon to the right
* Locate the Allocation Account dropdown menu
* Choose the desired Allocation Account
* Save your changes.


The exact location and steps will vary by template and category, but each one has a field where you can select the allocation account for that financial item. The possible areas where you can set allocation accounts include:




|  |  |
| --- | --- |
| Settings menuSession TemplatesOption CategoriesOption TemplatesActivity TemplatesFacility CategoriesFacilitiesAdd-on Fee TypesPayment PlansSeasonal FeesDonation CategoriesDonation Options | Scheduling MenuSessionsSession OptionsActivities
  |


 


When Allocation Accounts are assigned at a template level, all items scheduled from that template will default to the same allocation account. A good example of this is with Session Templates:


* + If allocation accounts are only assigned to the Session Template, all activities, options, and fees for a  session will default to the single allocation account specified in the Session Template.
	+ Activities, Options and other fees can have their own allocation account separate from the Session Template. This is done by adding an allocation account to the activity, option or fee template.
	+ Scheduled items can have their own allocation accounts as well. This includes Sessions and Options. For this individual instance, setting an allocation account on a scheduled item will override any allocation settings on the template level.


 



Tip


To minimize work, we strongly suggest setting the allocation accounts in the Settings menu.



 


### Allocation Account Interactions


To help clarify the relation between the different places allocation accounts can be collected, you can refer to the guides below:


**Session-related Allocation Accounts**


* + Allocation accounts set at the session level will apply to all settings assigned to them unless the allocation account is set at a lower level.  For example, a session option will have the same allocation account as the session unless the allocation account is changed at either the Option Category or Option Template level.


               ![1638391465462-1638391465462.png](https://help.ultracamp.com/hc/article_attachments/7380505053588/1638391465462-1638391465462.png)


**Donation Allocation Accounts**


* + Allocation accounts for donations can be set at the Donation Category and any Donation Template will inherit the category’s allocation account unless set on the Donation Template level.    ![1638391481613-1638391481613.png](https://help.ultracamp.com/hc/article_attachments/7380606319508/1638391481613-1638391481613.png)


**Facility Allocation Accounts**


* + Facilities can also have their allocation account set at the Facility Category level and the Facility Templates will inherit the allocation account unless it is set at the Facility Template as well.![1638391663389-1638391663389.png](https://help.ultracamp.com/hc/article_attachments/7380507010580/1638391663389-1638391663389.png)


**Add-On Fee Allocation Accounts**


* + For Add-On Fees, allocation accounts will be set on the fee level.


     ![1638391683628-1638391683628.png](https://help.ultracamp.com/hc/article_attachments/7380538813972/1638391683628-1638391683628.png)  
  




#### 
Remember


If an allocation account is set at a lower level, it will override allocation settings at higher levels.


