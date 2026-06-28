# CS 360 Project Three README Reflection

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of my app was to create an event tracker that helps users keep track of important events in one place. Users can create an account, log in securely, add new events, edit existing events, delete events they no longer need, and receive SMS notifications for upcoming events. The app was designed for students, workers, parents, or anyone who needs an easy way to organize their schedule and remember important dates.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app includes a login screen, account creation screen, event list screen, add/edit event screen, and SMS permission screen. These screens allow users to easily access their events while keeping their information secure. I tried to make the interface simple by using clear buttons, readable text, and a layout that does not overwhelm the user. I also improved the design throughout development by increasing spacing between the date and time fields, making the event list scrollable, and sorting events by the closest date first. These changes made the app easier to use and helped create a better user experience.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I built the app one feature at a time instead of trying to complete everything at once. I first made sure the login system worked, then created the database, followed by adding event management and SMS notifications. Breaking the project into smaller tasks made it easier to find and fix problems before moving on. I also added comments throughout my code to keep it organized and easier to understand. I can use this same approach on future software projects because it keeps development organized and makes debugging much easier.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the app by running it on the Android emulator after making changes to each feature. I created multiple user accounts, added, edited, and deleted events, tested database storage, and checked the SMS permission process. Testing was important because it helped me find problems like events not displaying in the correct order, layout spacing issues, and the SMS permission screen appearing more often than it should. Finding these issues early allowed me to fix them before completing the project.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the biggest challenges was making all of the different parts of the app work together correctly. The login system, database, event management, RecyclerView, and SMS notifications all depended on each other. I had to redesign parts of my code several times to keep everything connected while still keeping the project organized. I also improved the event sorting so users would always see the closest upcoming events first, making the app more useful.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I believe my strongest work was implementing the SQLite database and connecting it to the event management system. Users can create accounts, save events, update them, delete them, and have their information remain available after closing the app. I also successfully integrated SMS notifications, giving the app functionality beyond basic event storage. Completing these features showed that I understand user interface design, databases, Java programming, and Android app development while creating a complete and functional application.
