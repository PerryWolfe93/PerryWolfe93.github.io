#### Databases Enhancement

For this enhancement, my goal was to add role-based authentication to the application.  I began by researching how to connect to a database using an API.  This led me to the Retrofit library built for Android studio and PHP (Hypertext Pre-Protocol).  I used the Retrofit library to convert Java objects into JSON format which could be passed to a server.  I am using AWS EC2 in conjunction with AWS RDS to host my web server and database.  Once the JSON code is passed to the server, PHP converts it to code that can be used by the MySQL database.  I then added a server role for application users to log in as.

From this enhancement, I have learned how internet connections are established using different protocols along with the host URL.  I have also learned to use the Retrofit library as well as PHP to convert objects between Java and JSON objects.  Finally, I actually learned how dependencies work.  The most difficult part of this enhancement was setting up the remote database and establishing a connection correctly.  Once I learned to do this, the rest only required that I learn to use Retrofit and PHP.  

[Back to Home Page](/)
