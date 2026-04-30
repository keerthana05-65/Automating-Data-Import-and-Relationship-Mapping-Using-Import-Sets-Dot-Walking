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
  1.Import employee data from CSV/XLSX
  2.Use Import Sets to stage data
  3.Create Transform Maps for mapping
  4.Handle reference fields (Department, Manager)
  5.Enable Dot Walking for auto-fill fields
  6.Ensure accurate data insertion into sys_user

Technologies Used:
  1.ServiceNow
  2.Import Sets
  3.Transform Maps
  4.Dot Walking

Workflow:
  1.Create employee data in Google Sheets
  2.Download as CSV/XLSX
  3.Upload using Import Sets
  4.Create Transform Map (import_employee → sys_user)
  5.Map all fields including reference fields
  6.Run transform
  7.Configure Incident form using Dot Walking

Outcome
  1.Improved data accuracy
  2.Reduced manual effort
  3.Automated relationship mapping
  4.Better user experience

Conclusion

This project shows how ServiceNow can automate employee data import and maintain proper relationships across tables. Using Import Sets, Transform Maps, and Dot Walking ensures efficient and reliable data handling.
