# flask-app-financial-trnx

Overview
A financial transaction recording syste capable of Creating a new entry, Reading existing entries, Updating existing entries, and Deleting existing entries. The app will be able to
Implement "Create" operation to add transaction entry
Implement "Read" operation to access the list of transaction entries
Implement "Update" operation to update the details of a given transaction entry
Implement "Delete" operation to delete a transaction entry.
After completion it will function as displayed in the animation.

![image](https://github.com/user-attachments/assets/3db8b2bb-cd48-4f1c-97cd-5cee1e4b376a)

The application has three different web pages. The first one displays all the recorded transactions. This page is called Transaction Records and displays all the transactions entries created in the system. This page also gives an option to Edit and Delete the available entries. The option of adding an entry is also available on this page. The second page is Add Transaction which is used when the user chooses to add the entry on the previous page. The user adds the Date and Amount values for the new entry. The third page is Edit Transaction which is user navigated to upon clicking the edit entry option. On this page also, the date and amount are accepted as entries; however, these entries are then reflected against the ID that was being edited.

Credit: IBM Skills Network

To run the app:
- Clone the repo
- cd into the project folder
- run the following command in the terminal:
- <code>python3.11 app.py</code>
