Project Title:
     Automating Data Import and Relationship Mapping Using Import Sets & Dot Walking in ServiceNow

Team Lead
   Keerthana P
Team Members
   Varsha T
   Santhiya E
   Kalaiyarasi M
   Lavanya D

Description

This project demonstrates how to efficiently import external employee data into ServiceNow and establish proper relationships between tables using Import Sets, Transform Maps, and Dot Walking.

The system handles employee details such as Name, Email, Department, Manager, and Phone Number from external files (CSV/XLSX). The data is processed and mapped into the sys_user table while maintaining proper relationships between records.

Additionally, the Incident form is enhanced using Dot Walking, enabling automatic population of related fields like department, manager, and email when an employee is selected.

Key Features
  Import employee data from CSV/XLSX
  Use Import Sets to stage data
  Create Transform Maps for mapping
  Handle reference fields (Department, Manager)
  Enable Dot Walking for auto-fill fields
  Ensure accurate data insertion into sys_user

Technologies Used:
  ServiceNow
  Import Sets
  Transform Maps
  Dot Walking

Workflow:
  Create employee data in Google Sheets
  Download as CSV/XLSX
  Upload using Import Sets
  Create Transform Map (import_employee → sys_user)
  Map all fields including reference fields
  Run transform
  Configure Incident form using Dot Walking

Outcome
  Improved data accuracy
  Reduced manual effort
  Automated relationship mapping
  Better user experience

Conclusion

This project shows how ServiceNow can automate employee data import and maintain proper relationships across tables. Using Import Sets, Transform Maps, and Dot Walking ensures efficient and reliable data handling.
