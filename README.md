# Alice-EMS

● The code should have relevant tests. A linting tool should be used.

● The project should be deployed in a cloud environment (GCP or AWS).

● The data should be stored in a database in that cloud environment using the learned ORM libraries. 

● API endpoint should have some level of authentication.

## Objectives
effective employee management system should include key features,
such as time and attendance management (e.g., time tracking by way of employee
timesheets), absence and leave management (e.g., time-off requests).


## Features & Capabilities:
1. Company and department Creation
- Super Admin will create a company with departments and initial employees (supervisors)
- Each department should have at least one employee ( the supervisor )

2. Employee registration and profile creation
- Every new employee will be added by the HR to the system.
- HR will assign the employee to a department.
- And email will be sent to the employee includes (username + password)
- The first sign in the employee will be requested to :
    - Change the password
    - Create a profile
3. Time & Attendance Management
- Employee can easily check in / check out
- Time should be calculated and recorded
-  send an email to the supervisor to unusual absenteeism levels of a specific employee
