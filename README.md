# employee-AppAssigment
This code calculates the monthly salary and deductions for an employee, and generates a payslip with the calculated values using Kotlin as a programming languaje.

The employee's information is stored as variables such as firstName, surname, gender, employeeID, etc. These values are then used to calculate various aspects of the employee's monthly pay such as the monthly salary, PRSI, PAYE, gross pay, total deductions, and net pay.

The main function presents a menu to the user, which allows the user to choose what information they want to see. The menu options include the monthly salary, PRSI, PAYE, gross pay, total deductions, net pay, or a full payslip. The menu function prompts the user to enter their selection, and the when statement in the main function implements the selected option.

The calculation of the various aspects of the employee's pay is done using functions such as getMonthlySalary, getMonthlyPRSI, getMonthlyPAYE, getGrossMonthlyPay, getTotalMonthlyDeductions, and getNetMonthlyPay. These functions make use of the values stored in the variables and other functions to perform the calculations.

Finally, the getPayslip function generates a formatted string that represents the payslip, which includes the employee's information and the calculated values for their monthly pay.

The roundTwoDecimals function is used to round the calculated values to two decimal places.
