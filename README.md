# Student_Assignment_201046038

Develop an application for student admission process using C language. Application should have following functionalities.

1. Provision to store student information like Name, program applied, mail id, registration number, entrance test rank, UG grade, admission status (allotted, rejected, waiting) etc.

2. Provision to store Program information like Program name, seats in each program, filled seats in each program etc.

3. Provision for administrator to initialize number of seats in each program.

4. Provision to allot seats based on entrance test rank. It is assumed that student provide the required information and seat allotment takes in increasing order of entrance test ranks. It should not allot seat, when UG grade is less than 5.0. If seat in requested program is available, system should allocate seat and generate registration number. Admission status of student should be changed to ‘allotted’. If UG grade is less than 5.0, status should be ‘rejected’. If seat is not available in requested program, status should be ‘waiting’. If status is ‘allotted’ then only registration number is generated.

5. Provision to count number of total applications submitted.

6. Provision to see seats filled in each program.

7. Provision to allot seats to waiting list students. Here student should provide two other program names for seat allotment. Previous data of student should be reused (like name, email etc.). This option is only for waiting list students.
