# LetsGO
Android app
This application has basic UI written in XML in the Android Studio.
It has lines of code that connect it to the Parse cloud storage and also uses Parse Push notification services.
The basic functions of this application is to collect user details as they create user accounts in a 'User class' in the cloud.
It allows the user to go further, only on signing in, using the same username and password they just used for creating the account.
Next step, is to update a status that includes the User's travel details, which is stored in another class in the cloud.
Presently it has limited set of starting points and destinations to choose from a drop down. However this can be enhanced in the next versions, by either an integration with the Google Map APIs or more regional choices.
Based on the destinations and the travel dates, the app will cross-check its database in the Parse cloud and generate a push notification for every member that has a common entry in these fields, hence forming a group of people travelling to the same place on the same day.
The list of users is displayed only after asking the user the permission to share his/her details with their new found co-passengers.
There is also a security feature that allows the user to choose the type of co-passengers he/she wishes to travel with. 
This application was designed to help android users find co-travellers for their weekly trips home, especially for College students as freshers, who can use this app to make new friends as well.
