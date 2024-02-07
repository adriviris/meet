The goal of this project is to develop a serverless, progressive web application (PWA) using React and employing a test-driven development (TDD) approach. The application is designed to retrieve upcoming events by utilizing the Google Calendar API.

1. Filter Events by City.

As a user,
I should be able to filter events by city
So that I can see a list of events taking place in that city.

2. Show/Hide Event Details.

Given the user is on the event page
When they choose to view/hide event details
Then the event details should be displayed or hidden

3. Specify Number of Events.

Given the user is on the event configuration page
When they specify the number of events to display
Then the system should show the specified number of events

4. Use the App When Offline.

Given the user has the app installed
And there is no internet connection
When the user tries to use the app
Then the app should provide offline functionality

5. Add an App Shortcut to the Home Screen.

Given the user has the app installed
When they choose to add a shortcut to the home screen
Then a shortcut to the app should appear on the home screen

6. Display Charts Visualizing Event Details.

Given the user is on the event details page
When they choose to view charts
Then the system should display visualizations for event details

For this app, serverless functions will be used to handle various functionalities such as user authentication, event notifications, and event recommendations.

When a user logs in or searches for events, serverless functions can authenticate them, query databases for relevant events, and send notifications based on user preferences—all without managing underlying infrastructure. This approach ensures scalability to handle varying user loads, cost-effectiveness by only paying for executed functions, and simplified development, allowing the team to focus on delivering a seamless event discovery experience for users.
