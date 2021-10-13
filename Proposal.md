# RFP - Connect Company

## Statement of Purpose :

- Connect Company is used to connect job aspirants to the company . Up to now, there are not many platforms where a user can connect to companies. Hence, we developed this application to bridge the gap. This application is used to schedule and manage the time available between the user and the company and It helps in scheduling an appointment for the events flexibly and it helps to create, edit, delete and view different types of events, In this application, the admin has access to view and manage the entire activity of users, even user and client has an access to set remainders for their scheduled appointments. Thus remainder option for their scheduled appointments would help in communication between user and client.

## Overview

- This application is all about connecting the user to companies. So far there are only a few platforms where a user can connect to companies. So we have developed our idea based on this concept. This Connect company is used to connect the job aspirant to the company events. So in this platform where user login into the connect company website and he/she can view the events organized by the companies.
There are multiple side advantages through this connect company firstly The companies can minimize advertisement for hiring the people and from the user point of view instead of he/she searching for the job openings on the mega-platforms simply he/she can look in to connect company for the events.

The user should have a valid username and password to enter into the system and also get notifications about the updates on subscribed channels.
How the application will works
- Each organization will be registered in the portal and they can post events happening in their company like an interview, Tech talks, or any updates on the company.
-	Users can open and subscribe to the company events or companies listed in the portal.
-	User can submit their request to join in the upcoming events.
-	They can get updates and emails on the subscribed events.

After subscribing to the event,
-	The user should be able to see a list of events happening and subscribed by him to return to the starting location (show on a map?)
The website is cooperative, not complex to find the company and subscribe to the events happening.

## Benefits
-	User's can easily connect with the company and get their dream job.
-	This website helps user to know more about the companies that are existing in the market.
-	Details and events of all the companies are available in single website so there is no need to browse individual websites.
-	By utilizing this application the companies can reduce their money spending on advertising.
-	The user will be up to date with the company events.  
-	This Website acts as a bridge between user and company.
-	There is clear transparency between users and companies.

## Epics / User Stories / Tasks:
### Backend
**USER**
- As a **USER** I want to be able to login into the application,So that I can view main dashboard of the application .
- As a **USER** I want to be able to register into the application,So that I can login into the system.
- As a **USER** I want to be able to subcribe the events in the companies,So that I can view my events whenever required.
- As a **USER** I want to be able to apply for a job,So that I can able to communicate to the company directly.
- As a **USER** I want to be able to view previous applications or events,So that I can get to know the progress of my performance.
- As a **USER** I want to be able to logout,So It can assure that my profile is seccured.

**ADMIN**
- As a **ADMIN** I want to be able to login into the system,So that I can have access on user applications.
- As a **ADMIN** I want to be able to view all the applications or job events,So that I can be able to notify to the user's.
- As a **ADMIN** I want to be able to view all the register,So that I can view the profile of the user.
- As a **ADMIN** I want to be able to remove companies form the system,So that I can edit the available company list.
- As a **ADMIN** I want to be able to update details about the company in the system,So that I can provide a detailed information about the companies.

**COMMITTEE MEMBER**
- As a **COMMITTEE MEMBER** I want to be able to login into the system,So that I can access the applications.
- As a **COMMITTEE MEMBER** I want to be able to add an event or job,So that I can update the events/job.
- As a **COMMITTEE MEMBER** I want to be able to view events or jobs which he/she posted,So that I can access al the events/job applications.
- As a **COMMITTEE MEMBER** I want to be able to see application request/user request,So that I can view all the appliations.



### Frontend:
- User/admin/committeemember can view	Create Login page 
-	User/admin/committeemember can create Register page
-	User/admin/committeemember can create 3 different dashboards for 3 different users
- User/admin/committeemember can	create Application submission view to submit event or job by a company
-	User/admin/committeemember can create a Different pages which show all the companies and events in each company.

## Acceptance criteria checklist:
- The user interface should be visually appealing as well as functional.
- Ensuring that the user can continuously receive notifications after subscribing to an event.
- Confirmation of tasks that could not be completed was required.
- The interface is simple to use.
- Displaying error page if service is not responding.

## Functional Requirements:
- Create a web application with authentication and authorization. The following roles are suggested:

- Admin User 
- Committee User 
- End-User / Client

### Organization Admin User Can do :

- Admin user can create a profile  for an organization
- Can have an access on adding the committee members and other Admin
- Provide the Organization details like name, type of organization, etc.
-  As an Admin User, Can manage the Events in a particular organization.
- Organization member have an access of creating and scheduling an events at different locations and at diffrent time.
- can have an access of rescheduling any event at any time.
- As an Admin User Can add event organizer to different events.
- Admin will add the user into Organization and event when user provides the details like Name ,Email address.
- Can also delete events and event User at any time.
- Admin User can have access to track the different user activities.
- Can Access all the User's details and Activities performed by an individual.
- As an Admin User can manage and create own events but only manage in the organization.
-  Generating the report of all the events in the organization after completion of the event is done by admin user.

### Committee User:
- Committee User can manage the Events in a particular organization.

- Organization member have an access of creating and scheduling an events at different locations and at diffrent time
- can have an access of rescheduling any event at any time.
- As a Committee User Can add event organizer to different events.

-  committe user will add the user into Organization and event when user provides the details like Name ,Email address.
- Can also delete events and event User at any time.

- Committee User can track the different user activities of his own created events 

- Comittee user can have access of all the User's details and Activities performed by the individual.
- Committee User can only manage his own created events
- As a committee user can manage user activates of his events
- After completion of the event Committee User can generate the report of his own created event in the organization .

### End-User/Client:
- As an End User need to create his/her own profile.

- He will provide his/her details to create an account.
- He/she can also provide what the client interested in and  what to do with the account For example, one wants to communicate with a business organization.
- As an End User, he/she can choose the organization.

- As a End-user, one can view the different organizations.
- If one like the particular organization he can add to that organization.
- can have a access to add in any organization in which ever they are intrested. 
- He can manage the different organizations that they  can be in multiple organizations at a time.
-  End User can manage the events and can can have a access to add into multiple events at defferent times.
- End user can have access to exit at any time.

## Performance requirements :  
- when the multiple conflicts or the confusing scope assessments occur by the organizations then we as the team have a clear scope about the project, to underpin those performance requirement.
- The database will be checked for each time when the user logins by using his database (username, password).
- The connection among the data in the table and database should be efficient to access the data and display it.
- When ever the users, customers and organizations fails to communicate with the development team. The development team will clarify the goals limitations and essential factors to overcome the issues with them.
- The performance requirements will occur at any time, the software development team will receive , prioritize and assimilate those requirements without any distruption.

## Other requirements :
- There should be separate accounts for admin and members such that no member can access the database and only admin has the rights to update the database.
- User should be able to receive notifications whenever they have registered for an event
- This application needs to handle different users at a time who are registering for the same event

## User interface sketches

![](GDP%20Images/ConnectCompany02.jpeg)



![](GDP%20Images/ConnectComapny-01.jpeg)

![](GDP%20Images/sc-1.PNG)

![](GDP%20Images/sc-2.PNG)

## E-R diagram displayed:
![](GDP%20Images/LatestErd.png)

## Consistent set of sample data in Excel, use one sheet for each entity
![](GDP%20Images/book1.png)
![](GDP%20Images/book2.png)
![](GDP%20Images/book3.png)
![](GDP%20Images/book4.png)
![](GDP%20Images/book5.png)

## Technology stack descriptions:

### Backend framework 
- The backend Framework we are using is Java with Spring Boot
- It is a fully optimized frame work which advanced methods and feature for relation struture data operation.

### Backend free app host 
- The Backend app host for our project would be *HEROKU*
### Data host 
- The data host we are planning to use is freesqldatabase which provides as three free database
### Front-end plan 
- For the frontend  we planning to use React Js framework which is an component based framework
### Front-end responsive design 
- The Front-end responsive design would be *Bootstrap*

## Risks and assumptions:

- Admin should be able to view, add, edit and delete the organizations and events.

- Admin should be able to view any event or organization and filter searches based on
location and type of event.

- The admin would also have the ability to view user registered events.

- Admin should be able to delete the organizations and events.

- User should be notified about the registered event prior to the event date and time.

- The Organization should be able to view the dashboard with details about the total users registered for the particular event.

# Deliverable artifacts
| S. No. | Deliverable Name                                                           | Description              | Owner | Status |
|------|--------------------------------------------------------------------|--------------------| ------------- | ---------- |
| 1    | Prepare Project Plan           |  Identify the milestones, Tasks  | Ramu |  Completed |
| 2    | Design Wireframes                   |  Design the layout of the website | Anusha | In Progress |
| 3    | Back-end and Frontend SetUp                  |  Set the code base and Repo | Akhil | Completed |
| 4    | Login Module UI                  |  Creating Login Page using React | Teja | Completed |
| 5    | Register Module UI                   |  Creating Register Page  | Venkatesh | Completed |
| 6    | Add "+" Functionality for Admin | Creating an UI functionality for Admin to add companies into system | Ramu | Not yet Started |
| 7    | API to post comapny data to system | Creating an API to add data to databse | Akhil | Not yet Started|
| 8    | Committed member can add events | Creating a form where a committe member can add events to the system| Teja | Not yet Started|
|9     | API to add events| Creating an API to add events to the system | Anusha | Not yet started|

 ## Scope
   |Module Name | Roles | Description |
   |------|--------------------------------------------------------------------|-----------|
   |Login Module | Admin/User/CommitteMember | Any user with valid Credentails should be able to login and invalid user details should provide error |
   | Register Module| Admin/User/CommitteMember | Any user wants to register should be able to submit their details and if there is no format for username and password system should throw error|
   | New Events Module | Committe member  |Committed member should be able to create new events and  Events once created can be able to edit and can delete |
   | User Dashboard | User | User can able to view all the events happening and able to register without any issues|
   | New Committe Member | Admin | Admin can able to add new committe member to the system and he/she should recieve email as notification|
   | Subscribe Module | User | User can able to subscribe to the events happening and able to get updates on time|

# Major Milestones:
| Stage | Date | Status |
|------|--------------------------------------------------------------------|-----------|
|Milestone 1 | 30 October 2021 | Complete static pages |
|Milestone 2 | 30 November 2021 | Complete Backend API's |
|Milestone 3 | 30 January 2022 | Integrating Backend with Database |
|Milestone 4 | 30 February 2022 | Integrating Backed & Frontend |
|Milestone 5 | 30 March 2022 | Testing |
|Completion | 30 April 2022 | Final product delivery |

## Schedule and Iteration Plan:
### Project: Connect Company
### Overall Status: On Track
## ProjectTeam:
|Project Lead | Ramu Vallapurapu |
|------|--------------------------------------------------------------------|
| Team Member | Venkatesh Vemula |
| Team Member | Akhil Kasuvojula|
| Team Member | Tejaswi Avula |
| Team Member | Anusha Kanagala |


-	**Sprint-1**: (Start Date: 11th October 2021 - 25th October 2021)
  -	In the initial sprint we have built the plan and we have sorted the technologies we are dealing with and we gathered the requirements.
-	**Sprint-2** : (Start Date: 25th October 2021 - 8th November 2021)
  -	In the Second Sprint we have built the UI Page using React js and build backend using Java with spring Boot .Then we have connected the backend with the frontend using 	 rest API we majorly using Axios for connection.
-	**Sprint-3**: (Start Date: 8th November 2021 - 22nd November 2021)
  - In the Third Sprint we have built the database in MYSQL and deployed the application in Heroku and using a remote free SQL database.

 End of semester GDP-1

 GDP-2 

- **Sprint-4**: (Start Date: 12th January 2022 - 26th January 2022)
  - Create Database models and schema

- **Spring-5**: (Start Date: 26th January 2022 - 9th february 2022)
  - Designing the different routes between webpages in frontend .Developing the relations between different tables ( like one-to-one ,many-to -many)

- **Sprint-6**: (Start Date: 9th February 2022 - 23rd February 2022)
  - Design web APIs

- **Sprint-7**: (Start Date: 23rd February 2022 - 9th March 2022)
  - Create APIs to fetch data from DB

- **Sprint-8**: (Start Date: 9th March 2022 - 23rd March 2022)
  - Design all the frontend UI pages based on feature required

- **Sprint-9**: (Start Date: 23rd march 2022 - 6th April 2022)
  - Integration with both frontend  and backend.

- **Sprint-10**: (Start Date: 6th April 2022 - 20th April 2022)
  - Testing and fixing issues. Deployment of the application.

## budget (2 semesters):

-  We students from Northwest Missouri State University as a team doing this project under the guidance of Dr. Badami Charles for two semesters using various technologies. 
# Budget
| S. No. | Name                                                            | Role               | Hours/ Week | Estimated Cost/ Week |
|------|--------------------------------------------------------------------|--------------------| ------------- | ---------- |
| 1    | [Ramu Vallapurapu](https://github.com/vallapurapuramu)           |  Developer  | 9 - 12 |  $405 - $540 |
| 2    | [Venkatesh Vemula](https://github.com/Vemula23)                   |  Developer | 9 - 12 | $405 - $540 |
| 3    | [Akhil kasuvojula](https://github.com/akhilkasuvojula)                   |  Developer | 9 - 12 | $405 - $540 |
| 4    | [Tejaswi Avula](https://github.com/tejaavula)                   |  Developer | 9 - 12 | $405 - $540 |
| 5    | [Anusha Kanagala](https://github.com/Anushakanagala)                   |  Developer | 9 - 12 | $405 - $540 |
|    |               |   |  | Material Resources  | $1000 |
|    |               |   |  | Total  | $3025 - $3700 |



# Test plan with requirements
   ## Test Deliverables
   - Test Plan
   - Test Cases
   - Bug Reports
   - Test Strategy
   - Customer Sign Off
   ## Testing Tools
   - Quality Testing
   - Manual Testing
  
   
   
   
