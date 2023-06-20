# Anonymous Message Board
<img width="1124" alt="Screenshot 2023-06-20 at 7 40 23 AM" src="https://github.com/pejmantheory/FCC-Message-Board/assets/81389644/b0e9f3b8-0399-492b-b427-9b94a3f92dad">
<img width="695" alt="Screenshot 2023-06-20 at 7 42 34 AM" src="https://github.com/pejmantheory/FCC-Message-Board/assets/81389644/81aea687-90ba-4640-b751-4873fdf8fee4">

(http://localhost:3002/)
* Set NODE_ENV to test without quotes when ready to write tests and DB to your databases connection string (in .env)
* Recommended to create controllers/handlers and handle routing in routes/api.js
* You will add any security features to server.js
* Write the following tests in tests/2_functional-tests.js:
* Creating a new thread: POST request to /api/threads/{board}
* Viewing the 10 most recent threads with 3 replies each: GET request to /api/threads/{board}
* Deleting a thread with the incorrect password: DELETE request to /api/threads/{board} with an invalid delete_password
* Deleting a thread with the correct password: DELETE request to /api/threads/{board} with a valid delete_password
* Reporting a thread: PUT request to /api/threads/{board}
* Creating a new reply: POST request to /api/replies/{board}
* Viewing a single thread with all replies: GET request to /api/replies/{board}
* Deleting a reply with the incorrect password: DELETE request to /api/replies/{board} with an invalid delete_password
* Deleting a reply with the correct password: DELETE request to /api/replies/{board} with a valid delete_password
* Reporting a reply: PUT request to /api/replies/{board}
