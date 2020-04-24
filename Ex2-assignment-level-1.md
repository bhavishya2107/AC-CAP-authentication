## BLOCK-readText

#### Timeline for the entire topic - 3 hours.

In this topic, you have to build a small web API from scratch for the following user stories.

*Note - This is not fullstack application, you only have to build the API using Node.js, Express.js and MongoDB. Please follow standard web practices.*

```
1. There are two kinds of users in our system 
  - students
  - mentors
2. A student should be able to signup using following information.
  - Name, Email Id, Password, Batch Number.
3. A student should be able to login using his/her email id and password.
4. Atleast 3 mentors should be automatically seeded into the database and so they don't have to signup. Mentor data should be seeded with the following information.
  - Name, Email Id, Password.
5. A mentor should be able to login using email and password.
6. The identification route for both the types of users has to be the same.
7. A mentor should be able to add a task in a resource called `Todo` with following info.
  - Name of todo, Whether its completed or not.
8. A mentor should be able to see all the tasks.
9. A student should be able to see all the tasks but should not be able to add a new task.
```

## BLOCK-writeTextAnswer

Here write the psuedo code you would follow to build the above API.

1. Create models for student,mentor and todo <br/>
2. Install all the neccessary packages <br/>
3. Seed mentors data into db <br/>
4. GET request to see all the task <br/>
5. POST request to login,signup mentors and students <br/>
6. POST route for creating a todo 
7. Create a middleware which checks whether the todo is being created by the mentor or not <br/>
8. Show a error response if a student is trying to access the route for creating todo.
