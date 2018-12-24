# Exercise Tracker Project freecodecamp

### User Stories

1. I can create a user by posting form data username to /api/exercise/new-user and returned will be an object with username and _id.
2. I can get an array of all users by getting api/exercise/users with the same info as when creating a user.
3. I can add an exercise to any user by posting form data userId(_id), description, duration, and optionally date to /api/exercise/add. If no date supplied it will use current date. Returned will the the user object with also with the exercise fields added.
4. I can retrieve a full exercise log of any user by getting /api/exercise/log with a parameter of userId(_id). Return will be the user object with added array log and count (total exercise count).
5. I can retrieve part of the log of any user by also passing along optional parameters of from & to or limit. (Date format yyyy-mm-dd, limit = int)


#### Example output:
* {"username":"Spruha","id":"5c2087bd6e66ad315aac9f85"}
and
* {"username":"Spruha","_id":"5c2087bd6e66ad315aac9f85","description":"Spruha's Exercise Record","duration":"68","date":"Mon Dec 24 2018"}

### How to run the project :

1. Clone the repository :                  
     https://github.com/akshataw/exerciseTracker.git

2. Navigate to the repository:
     cd exerciseTracker

3. Install the dependencies :
     npm install     

4. Run the project :
     node server.js
