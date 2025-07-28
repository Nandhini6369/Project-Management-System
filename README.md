Project Management System

This is a custom Project Management System built on the Frappe framework. It includes modules for managing projects, assigning tasks, tracking timesheets, and generating payslips with automated email notifications.

Key Features:

Project Creation
- Admin can create and assign new **Project documents**.
- Upon assignment, selected members automatically receive email notifications with project details.

Task Assignment
- Admin or manager can create Tasks under specific projects.
- Tasks are assigned to individual members.
- Once a task is created, an email is sent to the assigned user with task information.

Timesheet Management
- Assigned users fill out Timesheets to track their work on assigned tasks.
- Timesheets record task progress, time spent, and descriptions.
- All task progress is documented under the Timesheet doctype.

Payslip Generation
- Payslips are generated based on the timesheets submitted by users.
- Generated Payslips are emailed to users in PDF format.

Sample screenshots of my Project :

this my project doctype
<img width="1919" height="956" alt="image" src="https://github.com/user-attachments/assets/3f75c5ac-d743-48e7-8dc8-5c6d13e30724" />

<img width="1919" height="956" alt="image" src="https://github.com/user-attachments/assets/a464c034-765d-401e-9df4-1eac336899f5" />

the email is sended to the Assigned project members
<img width="1614" height="140" alt="image" src="https://github.com/user-attachments/assets/de7e123e-2a74-45bd-a933-edeb05626177" />

this is my task doctype 

<img width="1918" height="917" alt="image" src="https://github.com/user-attachments/assets/ae649a36-63a6-4e1f-97ae-ac69e290bacb" />

this is my timesheet preview 
<img width="1918" height="917" alt="image" src="https://github.com/user-attachments/assets/f6ecea7e-bf3a-4220-b740-58ac28637452" />

this is my payslip preview
<img width="1918" height="917" alt="image" src="https://github.com/user-attachments/assets/c7e206d8-493c-469d-a4bb-69d0cc4944fc" />

The Payslip has been sent to the user in pdf Format
<img width="1878" height="882" alt="image" src="https://github.com/user-attachments/assets/165665d7-1230-4751-802b-dfce4b8ba0e5" />


Tech used:
- Frappe Framework
- Python
- JavaScript
- HTML & Jinja (for email/print templates)
- PDF Generation (via Print Formats)
