# RFP - Connect Company

## Statement of Purpose :

To achieve our goals and priorities, it is very important to schedule and manage our available time carefully. Our flexible Scheduling platform allows the user to:

1.Schedule different types of events, appointments, etc in an easy way.

2.Admin and Client users will be able to create, edit, delete and view different events.

3.Admin will be able to view and also manage the user activity.

4.Can set the remainders to their scheduled appointments.
## Vision
We would like to create a WA that can be used on browsers like chrome, safari…., etc. The application would encourage users to interact with the companies directly and can get updates on the events happening in the specific company.

The user should have a valid username and password to enter into the system and also get notifications about the updates on subscribed channels. How the application will works

1.Each organization will be registered in the portal and they can post events happening in their company like an interview, Tech talks, or any updates on the company.

2.Users can open and subscribe to the company events or companies listed in the portal.

3.User can submit their request to join in the upcoming events.

4.They can get updates and emails on the subscribed events.

After subscribing to the event,

The user should be able to see a list of events happening and subscribed by him to return to the starting location (show on a map?) The website is cooperative, not complex to find the company and subscribe to the events happening.

## Functional Requirements

Create a web app (or native application) with authentication and authorization. The following roles are suggested:

1.Admin User

2.Committee User

3.End-User / Client

### Organization Admin User Can do :
1.	Create a profile to  the organization  
	1.	Adds the committee members and other Admins
	2.	Provide the Organization details like name, type of organization, etc.
2.	As an Admin User, One  Can manage the Events in a particular organization
	1.	Create or schedule different events in different locations and times and provides to access organization members to add to it.
	2.	can reschedule any event at any time
3.	As an Admin User Can add event users to different events.
	1.	By providing the user details like Name, email address  Admin will add the user into Organization and event.
	2.	Can also delete event User at any time 
4.	Can also delete different events of the organization at any time.
5.	As an Admin User can track the different user activities.
	1.	Can Access all the User's details and Activities performed by an individual.
6.	As an Admin User can manage any events
	1.	Admin users can not only manage their own created events but can manage an event in the organization
7.	Admin users can generate the report of all the events in the organization after completion of the event.

### Committee User:
1.	As a Committee User can manage Events in a particular organization
	1.	Create or Schedule different events in different locations and times and provides to access organization members to add to it.
	2.	can reschedule any event at any time

2.	As a Committee User Can add event users to different events.
	1.	By providing the user details like Name, email address  Admin will add the user into Organization and event.
	2.	Can also delete event User at any time 
3.	Can also delete different events of the organization at any time.
4.	As a Committee User can track the different user activities of his own created events.
	1.	Can Access all the User's details and Activities performed by the individual.
5.	As a Committee User can manage his events
	1.	Committee users can only manage their own created events 
	2.	Can manage user activates of his events 
6.	Committee User can generate the report of his own created event in the organization after completion of the event.

### End-User/Client:
1.	As an End User, he/she can need to create his/her profile
	1.	He will provide his/her details to create the account.
	2.	He/she can also provide what is/her interests what need he/she what to  do with the account 
For example, one wants to communicate  with a business organization
	           
1.	Aa an End User, he/she can choose the organization
	1.	As End-user, one can view the different  organizations
	2.	If one like the particular organization he can add to that organization 
	3.	He can manage the different organizations that are he/she can be in multiple organizations at a time,
2.	As an End User,  one and manage the events
	1.	As an End User, One can add into manage multiple events (At different times)
	2.	As an End User, one can exits from any event before a specific time.


Expected entites may include:

* User
	*	email
	*	password
	*	username
	*	date created
	*	date last accessed

* Organization_details
	*	Org_Id
	*	Org_name
	*	Org_description
	*	createdAt
	*	updatedAt

* User_organization
	*	Id
	*	Org_id
	*	userID

* Event
	*	eventId
	*	eventname
	*	eventdescrption
	*	timeofevent
	*	eventtype
	*	event_location
	*	org_id

    
