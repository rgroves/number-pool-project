# Learning Log

- I know I want to Node + Express to implement the backend services.
- My first bit of research will be to look into what is needed to implement log in/membership functionality.
  - For MVP minimum functionality is to just allow someone to sign in with email and password.

# User Authentication

- To start as simply as possible here's what I basically need for authentication:

  1. A database to store email and password
     1a. Ensure passwords are stored in a secure industry-standard way (using bcrypt is what I'm familiar with from my past, is that still "the way" need to look this up)
  2. Need a backend service route that will create a new user if the email does not already exist in the database

- Given the first requirement above I'm going to setup a MongoDB instance to create a store for user/password.
