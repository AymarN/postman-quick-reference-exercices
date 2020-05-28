Use the Github API documentation (https://developer.github.com/v3/) for doing the assignment.

## Step 1

Add a new request to the collection that creates a new Github repository with the following properties:

- name: Test repository (random string)

- description: This is a test repository created by Postman


Add one test that checks the status code (expected 201).

Note: by visiting your profile, you can notice that the repository is now visible.

Hint: in order to create the repository, you need to send JSON in your request body.


## Step 2

Add a new request to the collection that retrieves (with GET) the newly created Github repository.

Add one test that checks the status code (expected 200).

This is an additional test step that ensures that the repository was indeed created.


## Step 3

Add a new request to the collection that creates a few issue inside the repository with the following content:

- title: Found a bug

- body: This issue has been automatically created by Postman.

Add one test that checks the status code (expected 201).


## Step 4

Add a new request to the collection that retrieves (with GET) the newly created Github repository issue.

Add one test that checks the status code (expected 200).

Add one test that checks the issue title (expected "Found a bug").

This is an additional test step that ensures that the issues was created.


## Step 5

Time to clean-up, otherwise your account will be filled with repositories which you don't need.

Make sure you delete the repository that you have created.

Add one test that checks the status code (expected 204).


## Step 6

Try again to fetch (with GET) the repository that you have just deleted (similar to Step 2).

Add one test that checks the status code (expected 404 Not found).

Clear any variables that you have used in this collection.
Questions for this assignment

How does your collection look like?

Important! Make sure you don't include any usernames / tokens / passwords.

How was this assignment?


## Assignment: Read the SMS code and replace it in the workflow
# Assignment

Before continuing with the next step, try doing the following on your own.

Study the Twilio API documentation / API explorer and figure a way to read the SMS code that was send by Github, but this time from Postman.

To generate a set of API keys you can go here: https://www.twilio.com/console/project/api-keys

Try to integrate the Twilio API request in the existing Github workflow.

Please try to do this on your own.

The answer is in the following lecture. 
