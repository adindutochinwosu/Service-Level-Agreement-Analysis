## Service-Level-Agreement-Analysis
This project involves analysing Helpdesk Tickets based on different Service Level Agreements (SLAs)

For this project, I utilized Microsoft Excel to analyse and identify SLAs that have either been fulfilled or breached. 
This project analyses Helpdesk Tickets based on different priority levels (SLAs). This was achieved by answering the following business questions that would aid in making informed business decisions.

### BUSINESS QUESTIONS
Question 1: Based on the cleansed file, can you please identify the following using the basic Excel formulas (such as IF, COUNTIFS):
- Total Tickets per Team
- Total Tickets per Priority
- Total Tickets per Type
- Total Open Tickets
- Total Resolved Tickets
- Total Closed Tickets
- Total Open/Answered Tickets
- Total Tickets from “Email”
- Total Tickets from “Web”
- Total Tickets from “Phone”

Please create a separate worksheet called “Summary” within the same Excel file to display the following output. 

Question 2: I need you to compute the SLA of each ticket based on the following criterion:
- In the tickets list sheet containing the cleansed data of tickets, add a new column “SLA Due Date”.
- Compute SLA for tickets with “Incident/ Problem” types only. For tickets which have “Request” types, print “No SLA for Request” in the cell.
- Follow the SLA below
  - Emergency - 4 hours
  - High Priority - 3 business days
  - Normal - 5 business days
  - Low - 10 business days
- Please compute the due date for each ticket excluding weekends. 
- Add another column called “Breached SLA?”.
  - Print “Yes” if SLA Due date is greater than the Last Updated Date. Else, print “No”.
- Add a new worksheet called “Ticket Viewer”.
  - Formulate a way wherein a user can enter any ticket number, and the following will be populated:
    - Subject
    - From
    - Date Created
    - Priority
    - Type
    - Status
    - SLA Due date
    - Breached SLA?
