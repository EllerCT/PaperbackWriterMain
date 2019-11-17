# In-Line Code Documentation

## **Description**

In-line code documentation for complex aspects of the source code which contain list of files, line numbers, and comments.

## **Complex Aspects of Source Code**
### ***Update Employee***
src -> main -> java -> managers -> EmployeeManager.java -> line 43 - 52
```Java
   /**
     *  Take a given data_structures.Employee, and changes the stored employee of the same pin
     *  to match the given employee.
     * @param employee The updated employee
     */
```

### ***Change Employee PIN***
src -> main -> java -> managers -> EmployeeManager.java -> line 54 - 64
```Java
    /**
     * Take a given employee with the old pin number, and assign them a new
     * pin number.
     * @param employee The employee with the old pin number.
     * @param pin The new pin number.
     */
```

### ***Change Employee PIN***
src -> main -> java -> managers -> EmployeeManager.java -> line 66 - 86
```Java
   /**
     * Get a new instance of data_structures.Employee identical to the data_structures.Employee stored under the given
     * data_structures.PinNumber
     * @param pin The data_structures.PinNumber of the data_structures.Employee to match
     * @return New instance of the matching data_structures.Employee
     */
``` 

### ***Clock In/Out***
src -> main -> java -> UserInterfaceController.java -> line 48 - 76
``` Java
    /**
     *  Checks to see if PIN from TimeClockFrame is equal to PIN from employeeManager.
     *  Checks to see if matchingEmployee is clocked in, if clockedIn then clock out.
     *  Then if not clockedIn, clockIn the matchingEmployee.
     * @param clockFrame new instance of TimeClockFrame
     */
```

### ***On Add New Employee***
src -> main -> java -> UserInterfaceController.java -> line 93 - 114
```Java
   /**
     *  Makes new instance of the data structure Employee.
     *  Using AddEmployeeFrame, takes in the text field and set the input to employee fields.
     *  Sets clock in and out time to now
     *  Then adds the new employee to the employeeManager, then clears input fields of AddEmployeeFrame.
     * @param addEmployeeFrame instance of AddEmployeeFrame
     */
```     

## **Additional Comments**
### ***Add Employee Preference***
src -> main -> java -> UserInterfaceController.java -> line 78 - 91
```Java
    //This is being left in to demonstrate to the client.
    //If they prefer this method of entry, we'll add one for events.
    //If they prefer the table method, we'll remove this.
```   
