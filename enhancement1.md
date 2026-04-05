# Software Design and Engineering Enhancement

## Artifact
**Event Tracker Mobile Application**  
Originally developed in Android Studio using Java during CS 360 Mobile Architecture and Programming.

## Overview
This enhancement focuses on improving the software design of the Event Tracker application by introducing a layered architecture. The goal of the enhancement was to improve maintainability, readability, and separation of responsibilities without changing the core functionality of the application.

## What Was Improved
- Added a service layer to handle business logic.
- Added a repository layer to manage database access.
- Updated Activities so they no longer interact directly with SQLite.
- Improved responsibility boundaries between the UI and database logic.

## Narrative
​​The artifact I selected for this enhancement is​ my Event Tracker mobile ​application, which I originally developed in​ Android Studio using Java during the ​CS 360 Mobile Architecture and Programming course​. The application allows users to ​create accounts, log in, add events​, view them in a list, and delete events. It also includes functionality for managing SMS notification permissions. I chose this artifact because it represents a complete, working application that demonstrates both front-end and back-end functionality, including user interaction, data storage, and basic security considerations. 

​​I included this artifact in my ePortfolio because it​ showcases my ability to design and build a functional mobile application while working with multiple components such as Activities, SQLite databases, and user input validation. ​One of the main reasons I​ selected this project ​is because it​ allowed me to demonstrate growth through enhancement. In its original form, the application directly connected the user interface to the database, which worked but was not ideal for long-term scalability. Through this enhancement, I improved the design by introducing a layered architecture that separates responsibilities across different parts of the system. I created service and repository classes so that Activities no longer communicate directly with the database. This change improved ​the organization of the code​ and made the application easier to maintain and expand, while still preserving all original functionality. 

​​This enhancement allowed me to meet the course outcomes I planned in​ ​Module One​, especially ​those related to​ software design and engineering practices. I demonstrated my ability to improve ​an existing system​ by applying better ​architectural​ design, specifically by implementing separation of concerns and modular design. I also ​strengthened my ability​ ​to evaluate an existing​ solution and ​identify​ areas for improvement. At this point, I do not need to make ​major updates to my outcome-coverage​ plan, as this enhancement clearly supports my goal of demonstrating software engineering skills. 

Throughout ​the process of enhancing this artifact, I learned​ the importance of structuring code in a way that supports long-term growth rather than just immediate functionality. One of the biggest takeaways for me was understanding how separating logic into different layers can make a system easier to work with and less prone to errors. A challenge I faced during this process was making sure that the application continued to function correctly after refactoring the code. Since I was changing how different parts of the system communicate, I had to be careful not to break existing features. By testing each change step by step, I was able to successfully refactor the application without introducing issues. Overall, this experience helped me better understand how real-world applications are structured and gave me more confidence in improving existing code rather than just creating new programs from scratch. 

## Artifact Files
- [Enhanced Artifact](
