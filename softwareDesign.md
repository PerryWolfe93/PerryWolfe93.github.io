#### Software Design Enhancement

My goal with this project enhancement was to incorporate functionality for the user to be able to track journal entries.  I began by creating the interfaces for the user to interact with.  The first of these, the journal entry activity, is necessary for the user to make new journal entries as well as access previous entries.  The second activity is used to view past journal entries.  I then developed the database methods for storing and accessing the data.  Finally, I added the backend code that is needed for the user's inputs to operate as intended. 

The completion of this task required that I learn to use a new widget, improve my understanding of Java interfaces and inner classes to incorporate a recycler view widget, and set up a remote database.  Of these, setting up the remote database proved to be extremely challenging for me.  I first had to learn to use an Android library, Retrofit, to convert Java objects into a JSON format.  The JSON object then needed PHP code on the server side to convert the JSON object to code that could be understood by MySQL.  I used Amazon's ec2 and rds systems to host both my remote server and MySQL database.  This was especially challenging for me because I previously had very little understanding of web APIs.

[Back to Home Page](/)
