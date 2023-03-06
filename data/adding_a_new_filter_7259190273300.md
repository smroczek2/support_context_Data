# Adding a New Filter
To determine the records from which to return data fields, UltraCamp requires Filters.  The filters you place on a report determine whose information is returned in the report. Multiple filters can be combined to restrict the data returned.


By default, UltraCamp places a custom filter in every newly created report. This filter narrows the list of returned data to only individuals who are enrolled in the current calendar year. If this filter conflicts with your desired return information, you can delete it using the link to the right.



## 


## Add a Filter to This Group


1. 1. Click on the Add a filter to this group link. This will bring up the Filter Creator popup.
	2. In the Filter Creator, you can select which kind of filter you wish to add.
	3. The creator then will walk you through the next steps.


## 


## Select Filter


There are four categories of Filter that you can select from in the Filter Constructor.


* **Simple Filter**is used to perform comparisons between data fields of greater than, less than, equal to, or not equal to.
* **Exists filte**r looks for a specific ID number in the system.
	+ This includes idSession, idPerson, idAccount, a Reservation ID or even an Option Exists filters can be used to create checklist prompts for a variety of filter scenarios.
* **Custom filter**adds a blank set of parameters which you can then edit and manipulate using the Field Editor.
	+ You will need to add a Left Operand, Operator, and Right Operand in order for it to function properly. This is an advanced process and not necessary for most reports.
* **Pre-done Filters**these are the most universal and common filters and are included to make filtering simple for most reports.
	+ They include filters for all attendees in the current year, all attendees for upcoming sessions, and a prompt filter where the user can indicate via checkbox which sessions they wish to include in their report.
	+ A variety of Pre-done Filters can be added.


 



#### 
 Tip


You can add multiple filters to a single Filter Group. UltraCamp will process these filters in order from top to bottom. You can use a combination of filters to return very specific data sets.



 


## Add a New Filter Group


Multiple filter groups can be combined to create complex filter logic. 


* When two or more filter groups are added, they can be compared with either an And comparison or an Or comparison.
* UltraCamp will process all the filters in each group and then compare one group to the other.


### 


### Multiple Filter Group Example:


The desired report should collect information on boys who are 10 years old and girls who are 12 years old. 


* A single filter group would be unable to achieve this result since it is not possible for a single person to be both 10 years old and 12 years old as well as be both a boy and a girl.
* By creating two different filter groups with the "OR" condition between them the report will return anyone who meets the criteria in either filter group 1 or filter group 2.


![1570642279799-WhereGroupExample.gif](https://help.ultracamp.com/hc/article_attachments/7551224603924/1570642279799-WhereGroupExample.gif)


### 


### Filter Symbols


When working with filters, you may be required to use or at least understand a series of symbols. Below is a key to help you interpret those symbols--you can read the equivalent phrase in place of the symbol.




|  |  |
| --- | --- |
| **=** | **Equal To** |
| **>** | **Greater Than** |
| **<** | **Less Than** |
| **< >** | **Not Equal To** |


 

