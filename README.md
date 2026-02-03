# Conference Attendance Optimizer

**Conference Attendance Optimizer** is a tool that helps conference organizers optimize the attendance of events by employees based on the goals of the company. In some cases, we want employees to attend events to learn new skills and knowledge, while in other cases we want employees to attend events to network with other professionals in an industry. 

The choices are based on conversations through a chat interface. The chat interface will allow the user to specify the criteria for choosing events. **Conference Attendance Optimizer** will then construct a context that contains: 1) Conferences that are available to be attended by employees filtered by the criteria specified by the user (cost, topics, industries, etc.)2) Employees available to attende events (calendar availability, budget available to the employee, expertise of the employee, etc.) 3) previous or current event schedule for the employee 4) Any further criteria specified by the user. **Conference Attendance Optimizer** will then use this context to generate an optimized list of events that are recommended for employees to attend that will maximize the goals of the company and the employees.

## Information Required

### Conferences And Events
A list of conferences and events will need to be searched by an agent or service. This list will need to be updated periodically to ensure that the conferences are up to date. The list will need to include the following information for each conference: name, date, location, cost, topics, industries, sessions (and topics for each session), and any other relevant information.

### Employees
A source of information for employees will need to be created and maintained. This information will be used to determine which employees will benefit the most from attending a conference or would be the best to represesent the company at an event and maximize the goals of the company. The employee information will need to include name, employee specialities, industries the employee is engage in, skills the employee has, employee location, weighting of preference for sending and employee as a representative of the company, and budget available to the employee to attend conferences (available budget = budget - cost of events attended or scheduled to attend).

### Company
Company information will need to be created and maintained. This information will include data on the goals of the company, budget allocated to conferences, current industry focus of the company, aspirational industry focus of the company, and any other relevant information.

### Availability
Integration to company calendars will need to be created and maintained. There will also need to be a method to manually block dates for employees to ensure that they are not scheduled to attend events that during times when they will not be available to attend. For example, if an employee is taking PTO, their contract is ending (i.e. we don't want that time to be considered given that they may not be employeed by us any longer), or we have other reasons for blacking out attendance during a time period.

### Travel and Accomdations
We will also include the cost of travel, food, and accomodations. So, we will need the ability to estimate this across multiple airlines, hotels, and other travel options. We will also need to be able to estimate the cost of travel for employees who are not in the same location as the conference.

### Scheduling and Booking
The platform will need the ability to request the employee attend a conference or event and give them the relevant information about the conference or event. If they accept, the platform will need to provide the employee with the necessary information to book our optimized travel options (if needed), book our suggesteed accommodations (if needed), and book the conference or event. The user will need to be able to accept or reject the booking. If they accept, the platform will need to update the employee's calendar and budget. If they reject, the platform will need to remove the event from the employee's schedule and ensure their budget is updated.

## Interfaces
### Chat Interface
A chat interface will be created to allow platform users to interact with the system and specify the any additonal goals (outside of the established company goals) and any other critieria to be used in the context of the optimation process.

### Web Interface
A web interface will need to be present to allow the users to accept or reject attendance at a conference or event, view the schedule of events for an employee, view the budget of an employee, view the availability of an employee, view the travel and accommodations options for an employee, and view the travel and accommodations options for a conference or event.

### Mobile Interface
A Mobile Application should be created to allow employees to accept or reject attendance at a conference or event, view the schedule of events for an employee, view the budget of an employee, view the availability of an employee, view the travel and accommodations options for an employee, and view the travel and accommodations options for a conference or event.

# TL;DR
Our **Conference Attendance Optimizer** is a tool that helps companies optimize the presence of their employees at conferences and events. We want to make sure our employees are appropriately skilled and knowledgeable about the industry and the topics that are being discussed at the conference or event. We also want to make sure our employees are appropriately connected to other professionals in the industry and are able to network with them and learn from them. Companies also need to be able to ensure that business and networking opportunities are maximized for their employees and to grow their business through these opportunities.

# AI
AI should read the `AGENT.md` file to continue it's understanding of this project. The `AGENT.md` file will provide the AI with the context and instructions it needs to continue working on this project.