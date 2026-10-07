# HR Analytics — Project Notes

## Data model

The project contains three tables:

### Employees
Employee master information such as employee ID, gender, age, department, job role, salary, joining date, and status.

### Attendance
Monthly working days, present days, and leave days for employees.

### Performance
Employee performance score, training hours, review date, and performance rating.

The common employee key is `Employee_ID`.

## Important measures

**Employee Count**  
Count of employees using `Employee_ID`.

**Average Salary**  
Average of the employee salary field.

**Attendance %**  
Present days divided by working days.

**Average Performance Score**  
Average performance score, grouped by department after relating performance records to employee department.

## Dashboard purpose

The report is intended to give a recruiter/HR manager a quick overview of workforce size, workforce status, compensation, attendance, and performance. Slicers allow the user to narrow the view by employee characteristics.
