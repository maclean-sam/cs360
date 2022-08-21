## Sam Maclean
## CS-360
## SNHU
## Mobile Architecture & Programming

##### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The requirements and goals for the app I created were a functioning screen for the user to log in, a way to input data into a database, a way to access that data, and a way to send the user SMS notifications if they choose to participate. The project I chose to work on was a weight tracking app that allows the user to input their weight into the database every day with the ability to view the weight log as a grid. The app required CRUD (create, read, update, and delete) functionality which was accomplished for maximum user efficiency. The app was created as a way for people to track their weight losing or gaining progress while having the option to visualize the results. 

##### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
To support the user needs, I added a screen for logging in which had a simple interface where the user enters their username and password. Simplicity was a priority during the development of the app so the user can figure out how to navigate throughout the interface efficiently. There is also an option to register which requires an email address, username, and password. Inside of the app, there is a screen for enabling SMS notifications which the user can choose whether they would like to participate. The home screen is where the user can log a weight and that weight gets added to the database which can be viewed with the "View Progress" button. I planned out all of the functionality that was necessary for the app to provide everything the user needs to be successful in their journey to better health.

##### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I approached coding of the app by planning out all of the funcionality that was needed for the different design elements. For example, every button had to take the user to a new place so I made sure they all had OnClick() events which allows the button to take the user to a new screen in the case of this app. I also created a database in SQLite and managed that database to create CRUD functionality which is required for basic data management. These strategies will be used in future program designs that require basic functionality and a simple to use interface.

##### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
I thoroughly tested my code by checking every button to make sure they function as intended and ensuring every screen is successfully opened when needed. Testing the app revealed things that were not working as intended which gave me the oppurtunity to debug the app using Logcat and figure out where the errors are present. Thoroughly testing the code ensures the app works correctly for the user and does not introduce errors or other problems. 

##### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
I ran into an issue where the app was not reading the database full of weights correctly which was fixed by carefully debugging using Logcat to identify where the program was running into issues. Logcat tells me the exact line numbers in each class that have a problem and I realized that all of the errors that stemmed from this problem all came back to one class that other classes were utilizing.  


##### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I demonstrated my skills by setting up the database that holds both the date and weight information that the user has input into the log at the home page. The database provides full basic functionality and is a centerpiece of the app so basic functionality is important for the user to have the best experience possible when tracking their weight progress.
