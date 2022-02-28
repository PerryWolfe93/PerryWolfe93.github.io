#### Data Structures And Algorithms Enhancement

This enhancement was designed to allow data to sync between local and remote databases in my fitness application.  I started building this application in Android Studio for a previous course, Mobile Architecture and Programming.  I chose this enhancement because it requires retrieving, sorting, and storing data which are all problems that are solved using either data structures or algorithms.

In working with data structures and algorithms, I have found that my code can get overly complicated very quickly.  Luckily, for this enhancement the data is already stored in databases.  Each of these databases has its own retrieval method within Android Studio.  A simple SQL query can retrieve the necessary data, though the syntax is extremely important and will cause problems if incorrect.
The enhancement will first require the user to click a button followed by another button to ensure that they want their data to be synchronized.  Next, the data is retrieved and compared before determining if it needs to be stored in the other database.  For this step, I have found it easiest to use pseudocode to better understand what I am doing.  

The database structure used in each of the databases was very important in allowing that only a simple algorithm be necessary.  Both the local and remote databases have user IDs as well as entry IDs stored for every data entry, though the entry IDs will definitely not match up.  To complete the task, only user data is retrieved that belongs to the specified user.  The data is then sorted by entry ID. One database will then have its date compared to the other database's date. If the date does not exist in the comparator’s data pool, entries will be copied until a matching date is found. Otherwise, it will check the next date and repeat the process until both databases have all relevant dates filled. This is the algorithm planned for this enhancement. 

One issue with this method will arise if the user saves data both locally and remotely and stores different data on each without syncing.  In this scenario, one of the databases will have to take precedence over the other resulting in some data loss.

Although I did not finish this enhancement, I do not think it will be difficult to implement once all of the bugs are worked out of my project.  Until the application can function using both local and remote users, this enhancement cannot be completed.

[Back to Home Page](/)
