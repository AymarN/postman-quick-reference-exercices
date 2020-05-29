# Assignment 3 : Make the requests more dynamic by taking advantages of variables
## Questions for this assignment

1. Notice: This step requires some JavaScript know-how to complete. If you have trouble getting this to work,<br/>
do not get frustrated :) Please do check the section call "JavaScript fundamentals" inside this course first.

When creating a new board, instead of My Board, try generating a unique board name by incrementing a number <br/> 
(using a pre-request script).

For example the first board you create will be:

My Board 1

The second board:

My Board 2

The third board:

My Board 3

and so on. 

Hint #1: Use an environment variable to save the last used number.

Hint #2: Take into account that when retrieving a value for a variable that has not been defined, you will get the value null.

2. Use environment variables for any dynamic parts in your requests (boardId, listId) and use them in requests and tests.<br/>
Replace all usages of global variables in your requests.

How do does your request and tests look like now?

3. Inspect your environment variables after you reached the last request. Clear any variables that you do not need as soon as you do not use them anymore.

What were the lines of code needed to clear the variables?

4. How was this assignment?

# Assignment 5 : Clearing unsed trello Boards
## WARNING: Doing assignment will delete all the boards associated to your account. Make sure you do not have any boards that you still need. 

Notice: This step requires some JavaScript know-how to complete. If you have trouble getting this to work, do not get frustrated<br/>
Please do check the section call "JavaScript fundamentals" inside this course first.

The goal is to delete all the boards that show up in your Trello profile that you no longer need and to use what <br/> 
you have learned inthe current section.

![DELETE BOARDS](https://i.udemycdn.com/redactor/raw/2018-03-21_19-46-48-a829f4b6231a1be69f662efba6deb7e5.png) <br/>

Questions for this assignment

1. [OPTIONAL] Have a look at the Trello documentation. Can you find a request that gets you all the boards associated <br/>
with your account? 

2. Hopefully you have found, very well hidden, the request that could give us all the boards:<br/>
https://developers.trello.com/v1.0/reference#membersidboards

Try to get this request running. Add this request right at the end of the Trello collection.

Important note: The parameter id is your username. If unsure, just check your Trello profile <br/>
(click on the imageon the right corner when logged in).

If you are getting the error "Model not found", it means that your username is not correct.

3. Try getting the first boardId from the list and print it to the Postman console.

4. Using workflows, try reusing the DELETE request you already have, without changing the order of the requests in your <br/>
collection or duplicating any requests.

5. If there are no boards left to be deleted, make sure you stop the workflow execution. 

6. Run the collection by using the collection runner. After the run is completed, there should no boards left in your account.

7. How was this assignment?

