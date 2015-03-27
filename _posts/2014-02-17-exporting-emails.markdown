---
layout: post
title: "Uploading a CSV List of Contacts"
status: unpublished
---

## Leveraging Data

[Building lists](/school-messenger-help/2014/02/17/customizing-recipients.html) in SchoolMessenger is possible through a variety of ways. Aspen has the ability for datasets to be downloaded as a CSV.

> A CSV, or comma separated value, is a file type used for databases to easily load up large data sets.

Getting CSV files out of Aspen is useful for when you want to build a recipient list of students who can't be grouped by the default fields (grade level, bus number, etc.), but are listed in Aspen by some other metric. 

These can be metrics such as classroom, pre-registered kindergarten parents, or rising 5th graders who've made their schedules for middle school.

Note that CSV data pulls from Aspen, but isn't automatically updated by Aspen once it's in SchoolMessenger. CSV lists are generated from your uploaded data, which therefore makes you responsible for keeping them up to date.

### Finding the data in Aspen

**Finding the Emails**

- Navigate to the student tab
- Use the filter menu to select "PreReg Kindergarten for Next Year"
- Select the Field Set icon
- Select "Emergency Contact Field Set"

**Export to Excel**

- Select the Quick Print icon
- Use "Web Page (HTML)"
- When the report displays, select Edit > Select All, Edit > Copy

**Inside of Excel**

- Paste it all into Excel
- Delete everything except for the columns that you need. This differs between use-cases, such as whether the students are in Aspen, or [not in Aspen](#not-in-aspen)
- Go to file > save as > and change the format to Windows Comma Separated (.csv)

Feel free to contact [Brenda Finkle](mailto:Brenda_Finkle@hcpss.org
) with any additional Aspen-related questions.

<!--<a id="in-aspen"></a>

## Use-Case: Sending to students with ID numbers

Let's say there's a class going on a field trip and you'd like to build a list of these kids. After downloading their sorted information from Aspen, delete every column except for the ID numbers.

Make sure the two zeros that prefix their ID numbers are still in there.

From here, you can take this one-column CSV and upload it into SchoolMessenger.

Under the "Broadcasts" tab, click on lists.

![find list](/school-messenger-help/images/select-lists.png)

Give it a title before adding contacts. The description is for administrative purposes and doesn't go along with a sent message.

![list name ids](/school-messenger-help/images/csv/list-name-ids.png)

Then, under the additional list tools menu use the "upload list" option.

![upload the list again](/school-messenger-help/images/refresh-upload-list.png)

Select "choose file" and add the CSV file you created, and choose "ID# lookup".

![contact data](/school-messenger-help/images/csv/id-lookup.png)

It will only show first and last names of students on the next screen, but once you save their information the data under the preview button will display all their contact information.

![preview button](/school-messenger-help/images/csv/preview-csv.png)

Once everything is all set, you can save list by clicking on done.

![done editing](/school-messenger-help/images/csv/save-list.png)
-->
<a id="not-in-aspen"></a>

## Use-Case: Sending to Kindergarten Pre-Registrants

Parents of new Kindergarten students are rolled over automatically into Aspen in late-July. They will be enabled for receiving messages around this time.

Until then, your school might want to get in contact with pre-registered parents for information regarding the first day of school, transitioning their children, or events they might be interested in.

### Sending with SchoolMessenger

Under the "Broadcasts" tab, click on lists.

![find list](/school-messenger-help/images/select-lists.png)

Give it a descriptive list name with a date, for example, "Pre-reg Kindergarten Parents - 1/17/15". This is to avoid confusion if you decided to upload another CSV later on.

The description is for administrative purposes and doesn't go along with a sent message.

![list name](/school-messenger-help/images/csv/list-name.png)

Then, under the additional list tools menu use the "upload list" option.

![upload the list again](/school-messenger-help/images/refresh-upload-list.png)

Select "choose file" and add the CSV file you created, then click next.

![contact data](/school-messenger-help/images/contact-data.png)

If your CSV file has, for instance, three columns (first, last, and one email), the SchoolMessenger interface should show you a first name, last name, and a third column defaulted to phone 1.

![column default](/school-messenger-help/images/column-default.png)

Change that third column to email 1. This will enable parents to get the email message.

![email one](/school-messenger-help/images/select-email-one.png)

After that, select the green "add message recipients" button to finish adding the contacts.

You can always preview the recipients by clicking on the magnifying glass icon. This is a good place to check and see if the names are lined up with an email address. 

![preview button](/school-messenger-help/images/csv/preview-csv.png)

In the preview window, clicking on the "0 phones, 1 email, 0 sms" area lets you see what's in a parent's contact field. This is a good way to always make sure that email 1 is filled out.

![checking email and sms](/school-messenger-help/images/checking-email-sms.png)

The list is now saved for you to re-use on future messages.

Once everything is all set, you can save the list by clicking on done.

![done editing](/school-messenger-help/images/csv/save-list.png)

### Using the list

When you get around to sending a new broadcast, you can always access this list from the "add message recipients" dropdown under "saved recipient lists".

![access the saved list](/school-messenger-help/images/access-saved-list.png)

## Refreshing the data

A downside for using this CSV option is keeping the data fresh. 

It's a good idea to upload a new CSV from Aspen once or twice before the late-July turnover. This keeps the list populated with the most up-to-date parents for your messages.

When you upload a new list, it completely overwrites the former list entires. Luckily, the most recent CSV should have the previously entered names along with any newly registered parents.

Under Broadcasts click on "lists". 

![find list](/school-messenger-help/images/select-lists.png)

Under lists you should find the list you uploaded as a CSV file. 

![view list](/school-messenger-help/images/viewing-uploaded-list.png)

Select "edit" to the far right.

![edit list](/school-messenger-help/images/uploaded-list-options.png)

Then, under the additional list tools menu use the "upload list" option.

![upload the list again](/school-messenger-help/images/refresh-upload-list.png)

From there you can re-upload the list from Aspen, similar to before. 

After uploading and clicking next, make sure the columns show "first name", "last name", and "email 1". Then, save the list.

![save the uploaded list](/school-messenger-help/images/save-uploaded-list.png)

To fully finish, click on done once you're back at the list overview.

![clicking on done](/school-messenger-help/images/list-done.png)

## Unsubscribing recipients

There may be some recipients who do not want to receive information.

You can always remove recipients by previewing the list.

![preview button](/school-messenger-help/images/csv/preview-csv.png)

Then, uncheck parents from the list. 

![uncheck the parents](/school-messenger-help/images/uncheck-parents.png)

Click on done after unchecking the ones you want removed, and they should be off the list.

![clicking on done](/school-messenger-help/images/list-done.png)

The downside is you'll have to delete them every time you upload a new CSV. 