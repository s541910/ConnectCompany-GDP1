# RFP - Connect Company

## Statement of Purpose :

- Connect Company is used to connect job aspirants to the company . Up to now, there are not many platforms where a user can connect to companies. Hence, we developed this application to bridge the gap. This application is used to schedule and manage the time available between the user and the company and It helps in scheduling an appointment for the events flexibly and it helps to create, edit, delete and view different types of events, In this application, the admin has access to view and manage the entire activity of users, even user and client has an access to set remainders for their scheduled appointments. Thus remainder option for their scheduled appointments would help in communication between user and client.

## Overview

- This application is all about connecting the user to companies. So far there are only a few platforms where a user can connect to companies. So we have developed our idea based on this concept. This Connect company is used to connect the job aspirant to the company events. So in this platform where user login into the connect company website and he/she can view the events organized by the companies.
There are multiple side advantages through this connect company firstly The companies can minimize advertisement for hiring the people and from the user point of view instead of he/she searching for the job openings on the mega-platforms simply he/she can look in to connect company for the events.

## Benefits
-	This application is a user-friendly application 
-	By utilizing this application the companies can reduce their money spending on advertising.
-	The user will be up to date with the company events.  
-	This Website acts as a bridge between user and company.
-	There is clear transparency between users and companies

## Epics / User Stories / Tasks:
### Backend
-	Create login Api
-	Create database schema with realtionships
-	Create login and register API.
-	Create Add API to add company person by admin to the system
-	Create Add event API for company person to add/create event/Job
-	Create Subscribe API to subscribe in events or job
-	Create ApplyEvent API to apply for event/job
-	Create ListEvents to view all the events/jobs applied

### Fronend:
-	Create Login page 
-	Create Register page
-	Create 3 different dashboards for 3 different users
-	Create Application submission view to submit event or job by a company
-	Create a Different pages which show all the companies and events in each company.

## Acceptance criteria checklist:
- The user interface should be visually appealing as well as functional.
- Ensuring that the user can continuously receive notifications after subscribing to an event.
- Confirmation of tasks that could not be completed was required.
- The interface is simple to use.
- Displaying error page if service is not responding

## Contract scope / budget / schedule (2 semesters):

-  We students from Northwest Missouri State University as a team doing this project under the guidance of Dr. Badami Charles for two semesters using various technologies. 
# Budget
| S. No. | Name                                                            | Role              | Hourly Pay                | Hours/ Week | Estimated Cost/ Week |
|------|--------------------------------------------------------------------|--------------------|------------------------| ------------- | ---------- |
| 1    | [Ramu Vallapurapu](https://github.com/vallapurapuramu)           |  Developer  | $45 |   9 - 12 |  $405 - $540 |
| 2    | [Venkatesh Vemula](https://github.com/jarugulavenkat7)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
| 3    | [Akhil kasuvojula](https://github.com/saikiranreddygangidi)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
| 4    | [Tejaswi Avula](https://github.com/vivekd31)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
| 5    | [Anusha Kanagala](https://github.com/swetha34)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
|    |               |   |  | Material Resources  | $1000 |
|    |               |   |  | Total  | $3025 - $3700 |



### Project: Connect Company
### Overall Status: On Track
### Major Milestones:
| Stage | Date |
|------|--------------------------------------------------------------------|
|Milestone 1 | 30 October 2021 |
|Milestone 2 | 30 November 2021 |
|Milestone 3 | 30 January 2022 |
|Milestone 4 | 30 February 2022 |
|Milestone 5 | 30 March 2022 |
|Completion | 30 April 2022 |
## ProjectTeam:
|Project Lead | Ramu Vallapurapu |
|------|--------------------------------------------------------------------|
|Team Members | Venkatesh Vemula |
| | Akhil Kasuvojula|
| | Tejaswi Avula |
| | Anusha Kanagala |
## Schedule:

-	**Sprint-1**: In the initial sprint we have built the plan and we have sorted the technologies we are dealing with and we gathered the requirements.
-	**Sprint-2** : In the Second Sprint we have built the UI Page using Vue js and build backend using adonis js .Then we have connected the backend with the frontend using 	 rest API we majorly using Axios for connection.
-	**Sprint-3**: In the Third Sprint we have built the database in MYSQL and deployed the application in Heroku and using a remote free SQL database.


## Schedule:

-	**Sprint-1**: In the initial sprint we have built the plan and we have sorted the technologies we are dealing with and we gathered the requirements.
-	**Sprint-2** : In the Second Sprint we have built the UI Page using Vue js and build backend using adonis js .Then we have connected the backend with the frontend using 	 rest API we majorly using Axios for connection.
-	**Sprint3**: In the Third Sprint we have built the database in MYSQL and deployed the application in Heroku and using a remote free SQL database.


 End of semester GDP-1

 GDP-2 

- **Sprint-4**: Create Database models and schema

- **Spring-5**: Designing the different routes between webpages in frontend .Developing the relations between different tables ( like one-to-one ,many-to -many)

- **Sprint-6** Design web APIs

- **Sprint-7** Create APIs to fetch data from DB

- **Sprint-8**: Design all the frontend UI pages based on feature required

- **Sprint-9**: Integration with both frontend  and backend.

- **Sprint-10**: Testing and fixing issues. Deployment of the application.


## User interface sketches

![](GDP%20Images/ConnectComapny-01.jpeg)
![](GDP%20Images/ConnectComapny02.jpeg)


## Technology stack descriptions:

### Backend framework 
- The backend Framework we are using is adonisJs which is writtern in JavaSprint
- It is a fully optimized frame work which advanced methods and feature for relation struture data operation.

### Backend free app host 
- The Backend app host for our project would be *HEROKU*
### Data host 
- The data host we are planning to use is freesqldatabase which provides as three free database
### Front-end plan 
- For the frontend  we planning to use vue js framework which is an component based framework
### Front-end responsive design 
- The Front-end responsive design would be *Bootstrap*


## E-R diagram displayed:
![](GDP%20Images/LatestErd.png)

## Consistent set of sample data in Excel, use one sheet for each entity
![](GDP%20Images/book1.png)
![](GDP%20Images/book2.png)
![](GDP%20Images/book3.png)
![](GDP%20Images/book4.png)
![](GDP%20Images/book5.png)


## Risks and assumptions:

- Admin should be able to view, add, edit and delete the organizations and events.

- Admin should be able to view any event or organization and filter searches based on
location and type of event.

- The admin would also have the ability to view user registered events.

- Admin should be able to delete the organizations and events.

- User should be notified about the registered event prior to the event date and time.

- The Organization should be able to view the dashboard with details about the total users registered for the particular event
