

## Problem-1
### Compiled with problems
- Coming soon component was not exported by default it could not find this component and was giving the error.
- I exported it by default and the error was solved.

## Problem-2
### Order descending problem
- first I open the browser console and after clicking on subscribe console was showing error. and i see that there is a problem with hitToast.js I was and find out.
- variant was taken as the first props in the hitToast but the message was received first so this error was given.
- This problem  could have solved in another way, but I gave the message as a first props and it is solved. Now the browser is showing error toast. 

## Problem-3
### Api Problem

- After clicking the subscribe button, when the API is hit, if gives the error.
- There is a problem with the API. So the data is not being posted to the database.
- If change the API will save the data to the database.