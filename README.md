## SERVICE LEVEL AGREEMENT (SLA) ANALYSIS
This project focuses on analyzing Helpdesk Tickets in relation to various Service Level Agreements (SLAs).

To conduct this analysis, I used Microsoft Excel to examine and identify whether SLAs have been met or breached. The project evaluates Helpdesk Tickets based on different priority levels and aims to answer key business questions that support informed decision-making.

## BUSINESS QUESTIONS
#### Question 1: Identify the following using the basic Excel formulas (such as IF, COUNTIFS):
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

Create a separate worksheet called “Summary” within the same Excel file to display the following output. 

#### Question 2: Compute the SLA of each ticket based on the following criterion:
- In the tickets list sheet containing the cleansed data of tickets, add a new column “SLA Due Date”.
- Compute SLA for tickets with “Incident/ Problem” types only. For tickets which have “Request” types, print “No SLA for Request” in the cell.
- Follow the SLA below
  - Emergency - 4 hours
  - High Priority - 3 business days
  - Normal - 5 business days
  - Low - 10 business days
- Compute the due date for each ticket excluding weekends. 
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

#### Question 3: I’d like to have a representation of the data using Pivot in Excel for easier visualization and analysis of data. Based on the cleansed file, can you please identify the following using Pivot table and graphs? 
- Add a new worksheet for Pivot Table and present the following:
  - Total Tickets per Team
  - Total Tickets per Priority
- Add a new worksheet for Pivot Chart and present the following:
  - Total Tickets per Status
- In the sheet with Pivot Chart, add slicers for the following:
  - Priority
  - Source
  - Type
  - Department
  - Breached SLA
### Variables
- Ticket Number
- Date Created
- Subject
- From
- From Email
- Priority
- Department
- Type
- Source
- Current Status
- Last Updated
- Due Date
- Overdue
- Answered
- Agent Assigned
- Team Assigned
- Category
- Issue Origin
- Select Ticket Status Update
- SLA Due Date
- Breached SLA
## TOOLS USED
- Microsoft Excel
- Power Query
## METHODOLOGY
- Data Collection
- Data Preprocessing
- Data Cleaning
- Data Visualization
- Data Reporting
## FINDINGS
Findings categorized by each section:

#### Total Tickets per Team:
- AWS Team: 16 tickets
- BPM - ProcessMaker Support Team: 2 tickets
- Hardware Team: 3 tickets
- Help Desk Team: 35 tickets
- JDE Support Team: 249 tickets
- Network Team: 38 tickets
- Salesforce Team: 8 tickets
- SAP Support Team: 191 tickets
- Workday Team: 8 tickets

#### Total Tickets per Priority:
- Emergency: 53 tickets
- High: 115 tickets
- Normal: 341 tickets
- Low: 41 tickets
#### Total Tickets per Type:
- Incident / problem: 374 tickets
- Not Specified: 2 tickets
- Request: 174 tickets
#### Total Tickets per Source:
- Email: 31 tickets
- Web: 492 tickets
#### Total Tickets per Status:
- Closed: 472 tickets
- Open: 64 tickets
- Resolved: 14 tickets
#### Total Open/Answered Tickets:
- Open/Answered: 31 tickets

### Summary:
#### 1. Team Workload:
- The JDE Support Team has the highest number of tickets (249), followed by the SAP Support Team (191).
- The BPM - ProcessMaker Support Team and the Hardware Team have the fewest tickets, with 2 and 3 tickets respectively.

#### 2. Ticket Priority:
- Most tickets are of Normal priority (341 tickets), followed by High priority (115 tickets).
- The Low priority tickets are the least common (41 tickets).

#### 3. Ticket Type:
- The majority of the tickets are categorized as Incident / problem (374 tickets).
- A significant number of tickets are Requests (174 tickets).
- Only 2 tickets have an unspecified type.

#### 4. Ticket Source:
- The majority of the tickets were reported via Web (492 tickets), while only 31 tickets were reported through Email.

#### 5. Ticket Status:
- The majority of the tickets are Closed (472 tickets).
- There are 64 Open tickets and 14 Resolved tickets.
- 31 tickets are marked as Open/Answered.

### Insights:
 - The JDE Support Team and the SAP Support Team might need more resources or improved processes to handle their high volume of tickets.
 - The high number of Normal priority tickets suggests that while many issues are important, they are not urgent.
 - The predominance of tickets being reported through the web indicates a need to ensure the web reporting system is robust and user-friendly.
 - Since most tickets are closed, the teams are managing to resolve issues effectively, though the 64 open tickets need attention to prevent backlog.

## RECOMMENDATION
 - Drive volume to other sources to improve ticket quality.
 - Hold regular meetings to discuss tickets that are close to breaching.
 - Build or improve a self-service portal with a knowledge base to allow users to resolve their own issues, reducing incoming ticket volume to the service desk.
 - Leverage AI capabilities to speed up ticket processing and resolution.
 - Automate manual tasks wherever possible.
 - Revisit and update your SLAs to prioritize expectation management for your end users.
 - Organize the ticket categorization scheme for proper routing and reporting.
