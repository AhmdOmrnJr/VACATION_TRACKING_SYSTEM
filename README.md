# VACATION_TRACKING_SYSTEM
VACATION TRACKING SYSTEM

key features:
 
■ Implements a flexible rules-based system for validating and verifying leave 
time requests.

■ Enables manager approval (optional).

■ Provides access to requests for the previous calendar year, and allows 
requests to be made up to a year and a half in the future.

■ Uses e-mail notification to request manager approval and notify employees 
of request status changes.

■ Uses existing hardware and middleware.

■ Is implemented as an extension to the existing intranet portal system, and 
uses the portal’s single-sign-on mechanisms for all authentication.

■ Keeps activity logs for all transactions.

■ Enables the HR and system administration personnel to override all actions 
restricted by rules, with logging of those overrides.

■ Allows managers to directly award personal leave time (with system-set 
limits).

■ Provides a Web service interface for other internal systems to query any 
given employee’s vacation request summary.

■ Interfaces with the HR department legacy systems to retrieve required 
employee information and changes.

The Use Case Model:

<img width="603" alt="Top Level Use Case Model" src="https://github.com/user-attachments/assets/befcef6a-3e47-4b6c-8870-5689037856f5" />

The main use cases are as follows:
 
■ Manage Time: Describes how employees request and view vacation time 
requests.

■ Approve Request: Describes how a manager responds to a subordi
nate’s request for vacation time. 

■ Award Time: Describes how a manager can award a subordinate extra 
leave time (comp time).

■ Edit Employee Record: Describes how an HR clerk edits an employee’s 
information in the system. This includes setting all the leave time allow
ances and the maximum time that can be awarded by the manager.

■ Manage Locations: Describes how an HR clerk manages location 
records and their rules.

■ Manage Leave Categories: Describes how an HR clerk manages 
leave categories and their rules.

■ Override Leave Records: Describes how an HR clerk may override 
any rejection of leave time requests made by the rules in the system.

■ Back Up System Logs: Describes how the system administrator backs 
up the system’s logs.

The system contains the following actors:

■ Employee: The main user of this system. An employee uses this system to 
manage his or her vacation time. 

■ Manager: An employee who has all the abilities and goals of a regular 
employee, but with the added responsibility of approving vacation requests 
for immediate subordinates. A manager may award subordinates comp 
time, subject to certain limits set in the system.

■ Clerk: A member of the HR department who has sufficient rights to view 
employees’ personal data and is responsible for ensuring that employees’ 
information in all HR systems is up to date and correct. An HR clerk can 
add or remove nearly any record in the system. In the real world, HR clerks 
may or may not be employees; however, if they are employees, they use two 
separate login IDs to manage these two different roles.

■ System Admin: A role responsible for the smooth running of the sys
tem’s technical resources (e.g., Web server, database) and for collecting and 
archiving all log files.


