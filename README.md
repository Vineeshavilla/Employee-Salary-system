# Employee Salary Calculation System
## Overview:
This project is a Python-based employee salary calculation system that collects employee information and calculates their monthly earnings, deductions, and net pay. The system factors in components such as basic salary, HRA, medical allowance, conveyance, LTA, special allowance, and income tax, considering the employee's CTC (Cost to Company) and LOP (Loss of Pay) days.

## Features:
**Employee Information Collection:** Collects basic employee details such as name, ID, department, and bank account.<br>
**HR Information:** Collects salary-related details including CTC, LOP days, and worked days.<br>
**Earnings Calculation:** Computes monthly components like basic salary, HRA, medical, conveyance, LTA, and special allowance based on CTC.<br>
**Income Tax Calculation:** Calculates income tax based on applicable tax slabs.<br>
**Net Salary Calculation:** Computes the net pay after accounting for tax and loss of pay days.<br>
**Report Generation:** Displays a detailed report of the employee's salary breakdown and net earnings.<br>

## Functions:
**Employee_Info():** Gathers employee details.<br>
**Employee_HR_Info():** Gathers HR-related details like CTC and LOP days.<br>
**calc_earnings(ctc):** Calculates salary components based on CTC.<br>
**calc_income_tax(tax_slab):** Calculates income tax based on Indian tax slabs.<br>
**calc_salary(ctc, lop, tax):** Computes the final monthly salary after deductions.<br>
**display_report(emp_input, salary, net_pay):** Displays the employee's detailed salary report.
