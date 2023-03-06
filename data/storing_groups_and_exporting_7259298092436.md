# Storing Groups and Exporting
## Stored Groups


A Stored Groups is a static snapshot of data taken from a report's returned information. Stored Groups have a variety of uses within UltraCamp, ranging from filtering to large scale communication. In addition to saving report return information in the database, UltraCamp can also export returned information in Excel/CSV and PDF formats.    



## Store This Information


When you click the  **Store this information** **icon** on any standard report, you will be bring up the **Create a Stored Group**window. 


* Here you can manage the export of the report's returned information.
* The **Store this information** **icon** usually found in the upper right of a report's return information to store or export data from the report.


## 


## Create a Stored Group


1. **File Name:** By default, UltraCamp will use the report's name as the File Name for the data you are exporting, but you can modify this using the text field to the right.
	* If you are working with multiple stored groups at once, it is a good idea to name them differently for clarity. Be sure to avoid special characters in your stored group name since this can occasionally interfere with the various tools which use stored groups.


2. **Export Type:**This determines what UltraCamp does with the return information.




Stored Groups Excel File PDF

These groups are saved temporarily in UltraCamp 24 hours after midnight of the day on which the group is created. At this point the stored group expires and is wiped from the database.
* **Permanently Save** overrides the expiration.
* Once you've stored your group, you will receive a message in the window stating that the information was stored successfully. You can then safely close the window.



This will allow you to specify a different sort order than the default. The default sort order is the same order as the displayed return information.
* This export type will also permit you to specify exactly which data you wish exported by unchecking the **All Fields** checkbox and then selecting and deselecting which specific items you are looking for.
* Use the **Export** button to initiate the file download. Once the file has been exported, you may close the window.
* When you export to Excel, the file will be in a .csv format for better compatibility with various spreadsheet programs. You will find your exported file in your browsers downloads.



This format will allow you to specify a different sort order from the default as well as choose a Print Template if desired.
* Exporting to a pdf allows you to save and/or print from your computer.
* Custom Print Templates for PDF output can be created by UltraCamp programmers and attached to a specific standard report.
* UltraCamp will display the pdf in the popup window where you can download and save or print the exported file. You may then close the window.





#### 
Tip


You can also export to Excel using the **Quick Export**link at the top right of your return information. When Quick Exporting, your spreadsheet program may warn that the file extension does not match the format of the file. This is due to the way the file is auto-generated. If you receive this alert, click the option to open the file anyway. You can then re-save the file with the correct extension.



 


3. **Visible to All Users:** By checking this box, other administrators with access to reports can use this stored group. Otherwise, it is visible only to you.
4. **Permanently Save:**Prevents the stored group from being automatically removed after its expiration.


* + The resulting stored group can only be deleted manually using the **Manage link** in the Tools menu.



#### 
Tip


Clicking **Store this information**in a custom report does not bring up the same interface. Instead, this link stores the report data directly in the database, using the custom report's name as the File Name for the stored group.



 

