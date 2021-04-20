# Challange

## Instructions

Hard Requirements:
- This is a Go challenge and we expect it to be written in Go.
- This should be runable on a Unix system.

In particular we are looking for working, readable and simple code. We consider a simpler solution a more elegant solution.

To write the test we recommend that you clone this project and upload the code to public code provider of your choice, **please do not fork the repo**.

We are building a GUID web app where we can store GUID's, we expect the server to expose the following independent operations. We expect the server to handle and serve responses over HTTP.

- Create a new GUID
- Remove a GUID
- Replace a GUID
- Get a GUID

We require an authentication endpoint to return at token used to authorize any call to the rest of the API endpoints. Credentials may be hardcoded.
Any specific GUID may only be changed 3 times, after the limit is reached an appropriate error should be returned.
Storage should be in memory but be easily swapped out for a presistent store.


**Bonus Points For:**

- Restful
- Unit/Functional tests
- Dealing with money as integers
- Runnable as Docker image
- Clear commit messages
- Thread-safe


