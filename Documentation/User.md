# User Manual

## **Description**

Paper Back Writer is a software written on behalf of the Book Arts Collaborative of Downtown Muncie for a Computer Science capstone project. The primary purpose of this software is to better enable a healthy and easy-to-use environment wherein certain tasks and records are easy to perform and keep respectively. Useage is very task oriented, and menu useage is minimal.

## **Features**
* Track Employee information
  * Points from events
  * Hours worked this week
  * Hours worked total
* Employees can simply enter their pin to clock in or out
* Special events can be added, and employees can confirm their attendance
  * Point worth
  * Names of the event
  * Descriptions of event (presently just for reference)
* Adding, removing, and editing of employees or events
* Cost analysis of a product
* Ability to save an archive of that product
* Ability for authorized users to grade archived products
* Recording of resources with which products can be made

# How to...

## For Students / Employees
Some tasks common for a student / employee to undertake..

### Clock In or Out
1. With the main menu open, click on **Employee Menu**

1. Click on **Clock In / Out**
1. Enter your 4-digit pin number, such as 0001
1. Press the button. A popup will confirm that you have clocked in, or out.

### Run a Cost Analysis or Make a Product
1. With the main menu open, click on **Products Menu**
1. Click on **Cost Analysis**
1. From the various resource dropdown boxes, select which resources your project will use
  a. **Other** is a manual field, just in case you're using something unexpected!
  a. The number column beside it is for archival purposes, it won't affect the cost.
  a. The cost should be the manually calculated total price here. This can be a negative value, in case of discounts.
1. Specify how much of that resource you're using (numbers only please!)
1. Hit 'Calculate'
1. If you wish to archive this product, fill in the other information and continue
1. Press **Submit**. Don't worry about pressing 'calculate' again, it'll update one final time as it saves.

### Get Points For An Event
1. With the main menu open, click on **Employee Menu**
1. Click on **Confirm Event Attendance**
1. From the dropdown on the left, pick the event you attended.
  a. This will be a short name for the event!
1. Type in your pin into the labeled box
1. Press **Confirm**
1. If you are asked for a confirmation code, a popup box will ask for it. These are given out at the event itself!

## For Employers / Staff
You may be prompted for a password to do any of these!

### Add / Modify / Remove an Employee
1. With the main menu open, click **Employee Menu**
1. Select either **Add an Employee** for an easy to use window to make it easy to add many employees at once or
1. Select **View Employees**
1. Enter the password when prompted
You may click on table headings to sort, add or remove (default values will be added on new rows), or double-click on something to modify it. Make sure you press either 'return' or deselect before saving. Notice, hours are tracked in hours:minutes, so 3:40 indicates '3 hours, and 40 minutes'. Weekly hours will even tick over automatically!

### Add / Modify / Remove an Event
1. With the main menu open, click **Employee Menu**
1. Select **Manage Events**
1. Enter the password when prompted.
Like employees, the table is fully editable. Remember, every event needs a unique 'code' and it's what students will see when using the dropdown! When holding an event, consider showing both the name and the code. The 'confirmation' cell is for a special feature that allows you to give a password for that event. Students / Employees without that password won't be able to get points. Because events are not dated, you need not enter new events for different dates, for instance weekly meetings.

### Add / Modify / Remove Resources
1. With the main menu open, click **Products Menu**
1. Select **Resources**
1. You will not be prompted for a password, this is normal.
This table allows you to add, remove, and modify resources that you would like your employees to have access to. Name / Type combinations must be unique. Resource types are a dropdown list for ease of use, but nonstandard resources will need to be added manually via 'other' information in the product itself. Don't worry about keeping old resources in the system - remove them when you're done. Archived products will just save the information as text.

### Grade a Product
1. With the main menu open, click **Products Menu**
1. Select **Browse Products**
1. Select **Enable Grading**
1. Enter the password when prompted
1. Click the 'grading' checkbox
1. Click on a row (these cannot be edited!) and select **View**
1. Write the grade in the box
1. Click **OK**.
1. The grade is saved, but the table will not visibly update until it is reloaded.
While anyone can view an archived product, they are *archived*, which means cannot be edited, but also will not be affected by changes. At present,they are archived by the ID number, which should be tracked automatically. Entering a duplicate ID to an existing one will **discard** the duplicate, not replace it. It is best to allow the system to specify its own IDs.

**Note**: You may change the 'current ID' setting in *config.properties* if you wish to reset or skip a section of ID numbers.
**Also Note**: Manual ID editing may not remain a feature.
