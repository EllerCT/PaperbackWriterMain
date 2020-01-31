# Testing

## Automated Testing
Since there is no point running tests over code that has not changed, the current testing suite does not run on project build.
1. Expand the **test** folder located within **src**
1. Expand the **java** folder within **test**
1. Navigate to the package, then package or class you wish to test.
	1. To run all tests, right click on the **java** folder and select **'Run All Tests'**
1. Right click on either the package or class files you wish to test, and select **Run 'class name'** from the menu.

Tests may be run individually via the class files themselves. Currently only non-trivial and pure logic clases possess automated testing.

## Manual Testing
1. Open the software, either via artifact or build.
	1. Rejoice
1. Navigate to ensure every window opens and is formatted as expected.
	1. Rejoice.
1. Create an Employee via Table
1. Create Employee via button
1. Create test event with no point worth
1. Create test event with point worth
1. Create test event with point worth and confirmation code
1. Clock an employee in
1. Have the employee attend each event, ensure that point additions save by re-opening the employee viewer.
	1. Rejoice optional
1. Have that first employee clock out
1. Remove an Employee
1. Have an employee attend an event, but fail to enter the right code. Ensure points do not get added.
1. Create a few sample resources
1. Make a sample product.
1. Save it.
1. View it.
1. Grade it.
1. Reload to ensure it saved.
	1. Rejoice optional.
1. Close program
1. Re-open program.
1. Ensure everything we did persists.
	
Additional steps as necessary should new features be added / old features be modified.
