# Testing

## Automated Testing
Given that the software is largely a means of either entering, editing, or moving data, automated testing was deemed a low priority, and has not been implemented. Those calculations which it performs tend to either be trivial, or subject to change due to client needs at this point in development, and therefor testing assumed values may need to be rewritten with the code it's testing, thereby defeating the purpose.

## Integration Testing
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
