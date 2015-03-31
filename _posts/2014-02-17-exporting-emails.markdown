---
layout: post
title: "Uploading a CSV List of Contacts"
status: unpublished
---

## Leveraging Data

Building lists in SchoolMessenger is [possible through a variety of ways.](/school-messenger-help/2014/02/17/customizing-recipients.html) Aspen has the ability for datasets to be downloaded as a CSV.

> A CSV, or comma separated value, is a file type used for databases to easily load up large data sets.

Getting CSV files out of Aspen is useful for when you want to build a recipient list of students who can't be grouped by the default fields (grade level, bus number, etc.), but are listed in Aspen some other way. 

These can be Aspen data points such as being registered for AP courses, pre-registered kindergarten parents, or rising 5th graders who've made their schedules for middle school.

Note that CSV data pulls from Aspen, but isn't automatically updated by Aspen once it's in SchoolMessenger. CSV lists are generated from your uploaded data, which therefore makes you responsible for keeping them up to date.

### Getting the data in Aspen

####Finding the Emails

- Navigate to the student tab
- Use the filter menu to select a dataset (e.g., "PreReg Kindergarten for Next Year" or "Students w/AP in current year")
- Select the Field Set icon
- Select "Emergency Contact Field Set"

####Export to Excel

- Select the Quick Print icon
- Use "Web Page (HTML)"

![web page](/school-messenger-help/images/csv/print-web-page.png)

- When the report displays, select right click and go to "Select All"

![select all](/school-messenger-help/images/csv/select-all.png)

- Then, copy it

![copy](/school-messenger-help/images/csv/copy.png)

####Inside of Excel

- Before pasting into Excel, select every cell by clicking on the upper left-hand corner

![upper corner](/school-messenger-help/images/csv/upper-left-corner-all.png)

- Then, set the data-type to text, instead of general. This will allow your data to be moved over without losing anything in the cells

![text only](/school-messenger-help/images/csv/set-text-only.png)

- After setting the data type to text, paste everything into Excel. You'll be prompted with a clipboard, **be sure** to select "match destination formatting". This ensures that student ID numbers remain pre-fixed with two zeros.

![match destination](/school-messenger-help/images/csv/match-destination-formatting.png)

- Delete the columns you don't need. This differs between use-cases, such as whether the students are [active in Aspen](#in-aspen), or [not active in Aspen](#not-in-aspen)

- After your Excel file is all set, go to file > save as > and change the format to Comma Separated Value (.csv)

Feel free to contact [Brenda Finkle](mailto:Brenda_Finkle@hcpss.org
) with any additional Aspen-related questions.

<a id="in-aspen"></a>

## Use-Case: Sending to active students with ID numbers

Let's say you wanted to build of list of kids who are taking AP courses at your school. 

After downloading their sorted information from Aspen, delete every column except for the ID numbers.

- Make sure the two zeros that prefix their ID numbers are still in there.

- From here, you can take this one-column CSV and upload it into SchoolMessenger.

Start a new broadcast (if you need a refresher on sending a broadcast, check out [our documentation](/school-messenger-help/2014/02/17/quickly-send.html))

![new broadcast](/school-messenger-help/images/new-broadcast.png)

Then, click the "add message recipients..." dropdown and select "upload list"

![upload CSV broadcast](/school-messenger-help/images/csv/upload-csv-new-broadcast.png)

After uploading, select "ID# lookup" from the list of options. 

![ID lookup](/school-messenger-help/images/csv/id-lookup.png)

Choose the CSV file you created with the column of ID numbers and click "next".

![choose ID lookup](/school-messenger-help/images/csv/choose-id-lookup.png)

You'll then get a list of active students who are matched to their ID numbers. Click on "add selected recipients" to put them in as a list.

A recipient number will be generated for the students in that list, along with the defaulted name "uploaded list". 

> CSV uploads of active students should be treated as a one-off recipient list

However, if you forsee having to use this list later on, you can save the list by clicking the cloud icon and giving it a name.

![save list](/school-messenger-help/images/csv/save-list.png)

It will save after the message is sent, but this is data you're resposible for. It's only as up to date as the CSV file you feed it.

<a id="not-in-aspen"></a>

## Use-Case: Sending to Kindergarten Pre-Registrants

Parents of new Kindergarten students are rolled over automatically into Aspen in late-July. They will be enabled for receiving messages around this time.

Until then, your school might want to get in contact with them for information regarding the first day of school, transitioning their children, or events they might be interested in.

### In the Excel document

Once the data has been extracted from Aspen, delete everything except for the student's name and the first email listed. 

![email 1](/school-messenger-help/images/csv/email-one.png)

Unfortunately, with the way that the vendor has built this feature, you can only send to one of the parents that are listed as pre-registered.

### Loading into SchoolMessenger

Under the "Broadcasts" tab, click on lists.

![find list](/school-messenger-help/images/select-lists.png)

Give it a descriptive list name with a date, for example, "Pre-reg Kindergarten Parents - 1/17/15". This is to avoid confusion if you decided to refresh the CSV later on.

The description is for administrative purposes and doesn't go along with a sent message.

![list name](/school-messenger-help/images/csv/list-name.png)

Keep the targetted recipients set to the default for "both".

![target](/school-messenger-help/images/csv/target-recipients.png)

Then, under the additional list tools menu use the "upload list" option.

![upload the list again](/school-messenger-help/images/refresh-upload-list.png)

Select "contact data" and "choose file" to add the CSV file you created, then click next.

![contact data](/school-messenger-help/images/contact-data.png)

If your CSV file has, for instance, two columns (student name and one email), the SchoolMessenger interface should show you a first name column and a second column defaulted to "last name".

![column default](/school-messenger-help/images/column-default.png)

Change that last column to email 1. This will enable that parents' email to get messages.

![email one](/school-messenger-help/images/select-email-one.png)

Refresh the mapping, then save.

![mapping](/school-messenger-help/images/mapping.png)

You can always preview the recipients by clicking on the magnifying glass icon. This is a good place to check and see if the names are lined up with an email address. 

![preview button](/school-messenger-help/images/csv/preview-csv.png)

In the preview window, clicking on the "0 phones, 1 email, 0 sms" area lets you see what's in a parent's contact field. This is a good way to always make sure that email 1 is filled out.

![checking email and sms](/school-messenger-help/images/checking-email-sms.png)

The list is now ready for you to re-use on future messages.

Once everything is all set, you can save the list by clicking on done.

![done editing](/school-messenger-help/images/csv/save-uploaded-manual-list.png)

### Using the list

When you get around to sending a new broadcast, you can always access this list from the "add message recipients" dropdown under "saved recipient lists".

![access the saved list](/school-messenger-help/images/access-saved-list.png)

### Refreshing the data

A downside for using this CSV option is keeping the data fresh. 

In the case of pre-registered kindergarten parents, it's a good idea to upload a new CSV from Aspen once or twice before the late-July turnover. This keeps the list populated with the most up-to-date parents for your messages.

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