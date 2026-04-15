# Databases Enhancement


## Artifact
Event Tracker Mobile Application  
Originally developed in Android Studio using Java during CS 360 Mobile Architecture and Programming.


## Overview
This enhancement focuses on improving how data is stored and managed within the application by redesigning the database structure. The goal was to improve data organization, support multiple users, and ensure that each user’s data is stored securely and independently.


## What Was Improved
- Redesigned the database schema to include a unique user_id for each user.
- Linked events to specific users using a foreign key relationship.
- Updated SQL queries to retrieve, insert, and delete events based on the logged-in user.
- Improved data privacy by ensuring users only see their own events.
- Added indexing to improve query performance.


## Narrative
 The artifact I selected for this enhancement is my Event Tracker mobile​ ​application, which I originally developed in Android Studio using Java​ ​during the CS 360 Mobile Architecture and Programming course. The​ ​application allows users to create accounts, log in, add events, view​ ​them in a list, and delete events while storing data using an SQLite​ ​database. I chose to continue using this artifact because it provides a​ ​complete and functional system that can be further improved to demonstrate more advanced concepts in​ database design ​and data​ management. ​I included this artifact in my ePortfolio because it​ ​highlights my ability to​ improve how data is stored, accessed, and organized within an application. 
 
 ​In its original form, the application​ stored events without associating them with a specific user, which meant that all users shared the same data. ​In this enhancement, I​ redesigned the database ​by introducing a​ user-based structure using a user_id field and linking events directly to the user who created them. This required updating the database schema and modifying queries so that each user only retrieves their own events. ​These changes improved the overall​ structure of the application and ensured better data organization, integrity, and privacy. This enhancement demonstrates my ability to design relational database solutions and apply database concepts to improve an existing system. 

 Through this enhancement, I met the course outcome related to using computing practices and tools to implement database-driven solutions. ​I was able to demonstrate​ my understanding of relational database design, SQL queries, and how to manage user-specific data within an application. ​This enhancement aligns with my original plan from Module​ ​One, where I identified the need to improve how data is​ structured and accessed. ​At this time, I do not need to make any major updates to my​ ​outcome-coverage plan, as this enhancement​ fully ​supports my goal of​ strengthening my database ​skills. Throughout the process of enhancing​ ​this artifact, I learned the importance of​ structuring data in a way that supports scalability and real-world use cases. ​
 
 One key takeaway was​ ​understanding how​ linking data through a unique identifier, such as a user_id, allows for better organization and separation of user information. A challenge I faced was updating the database structure without breaking the existing functionality of the application. Since multiple parts of the app rely on database operations, I had to carefully update each component and test the system after making changes. Overall, this enhancement helped me gain a better understanding of how relational databases work in real applications and reinforced the importance of maintaining secure and organized data. 


## Artifact Files
- [Download Enhanced Artifact (ZIP)](EventTracker_Enhancement3.zip)
