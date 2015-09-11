
Requirements Definition Document for database project application
=================================================================
1. Introduction
===============
  1.1 Purpose: The purpose of this document is to define the requirements for our ICOM 5016 class project. This document is written for better understanding of the features that our application will have. 
  1.2 Scope
  1.3 Name of the product: Sweather 
  1.4 Team Name: Sweather Team
  1.5 Team members: 
      Alejandro Sánchez (Project Manager)
      Howard Martínez
      José Rodriguez
  1.5 What the product will do: This is a social network that permits users to post weather updates from their current location. The purpose of this app is to let users know and share local weather updates.  
  1.6 What the product won’t do: It won’t be able to tell detail weather updates. This is because we want users to share their weather. 
  1.7 Benefits, goals and objectives: Sometimes weather models are inaccurate or ambiguous. For example, if a user wants to go to the beach and the local news say that in a town far away from my hometown it is raining, the user would decide that it's better to stay home instead of going out, when in reality it's a perfectly sunny day at the beach. With this app we plan to fix this problem by having users become weather reporters. The goal is to have every user report weather conditions in their current locations so that other users can enjoy their day.
  1.9 Technologies used:
      1.9.1 Angular.js: It will be used for creating the front end of the web application.
      1.9.2 Node.js + Express.js: It will be used for the back end of the web application. Node.js + Espress.js will be the link between the database and the front end.
      1.9.3 Ionic Framework: It will be used for adding mobile application elements and features to the web application.
      1.9.4 PostgreSQL: Database for storing all the data of the application.
      1.9.5 Heroku: Server used to deploy the application.
2. General Description
  2.1 Product perspective
    This product is a social network that is categorized as an independent product. With this product users will become weather reporters and describe via status updates what the weather is like in their current location. Users will also become spectators. They will be able to look at friends post about weather. The full set of product specifications is described below. 
  2.3 Product Functions This application will let users do the following:
    2.3.1 Create an account: The user will be able to create an account from the application.
    2.3.2 Delete an account: The user will be able to delete his/her account from the application.
    2.3.3 Edit account details. The user will be able to edit the following details from the application:
      - password
      - first_name
      - second_name
      - first_surname
      - second_surname
      - email
      - gender
      - phone
      - date of birth
      - profile picture
    2.3.4 Reset user password: If the user has forgotten their password they may request a password change from within the app and then receive an email detailing instructions on how to reset the password.
    2.3.5 Post weather status update. The user may post a weather update to friends or groups within the application. These status updates include one or more of the following:  
      - Text
      - Images
      - Videos
      - Links
    2.3.6 Delete weather status update: The user will be able to delete a post they have shared.
    2.3.7 Friend user: The user will be able to add a friend within the application. This means that user will now receive status updates from the user they have just friended.
    2.3.8 Unfriend user: The user will be able to unfriend other users within the application. This implies that the user will stop receiving status updates from the user they have just friended.
    2.3.9 Read other user's status update: The application will have a news feed in which the user may read the weather updates from friends and from business pages. 
    2.3.10 Create groups of users for private sharing among groups: Users may create group that will be used to share specific weather update only with the people that are part of that group.
    2.3.11 Edit group: Users will be able to change the name and category of the group
    2.3.12 Invite to group: Users will be able to add users to their groups 
    2.3.13 Join group: Users will be able to join groups they were invited to.
    2.3.14 Leave group: Users will be able to leave a group they belong to.
    2.3.15 Delete group: The group admin can delete the group.
    2.3.16 Create events: A user may create events, with a time, location, description, name and type.
    2.3.17 Edit event: Users may be able to edit event details such as time, location, description, name and type.
    2.3.18 Share events: The user may share these events with other users. The events may be shared publicly or privately.
    2.3.19 Categorize events: The evens may be categorized into public or events shared among groups
    2.3.20 Join event: A user invited to an event can join an event or decline the event invitation.
    2.3.21 Leave event: A user that accepted the invitation can leave the event if he/her changes its mind.
    2.3.22 Delete event: The user that created the event can delete the event.
    2.3.23 Create a business page: A user may create a business page. This page is independent from the user, i.e., A person that is not a friend of the user may follow the business page to receive updates in their newsfeed. Business pages are public.
    2.3.24 Delete a business page: The user that created the business page may delete it.
    2.3.25: Follow a business page: A user might follow a business page. Post from that business page will then appear on their newsfeed.
    2.3.26: Unfollow a business page: A user might unfollow a business page. Posts from that business page will stop appearing on their newsfeed.
    2.3.27: Search for one or more of the following. The application will have a universal search that will let users search between the following criteria:
      - Friends (ESTA)
      - Groups (ESTA)
      - Events (ESTA)
      - Business Pages (ESTA)
  2.4 Users of the product: The users of this application are people who are smartphone owners. They do not need to be technically savvy as the interface for the application will be easy to use, user friendly and within the guidelines of smartphone applications.
  2.5: General Constraints: Users who are not logged in or part of the social network cannot access or add information from the application.
  2.6: Assumptions and dependencies: Depending on what is accomplished in each sprint, the specifications may change. Implementations may change depending on how well they are working.



