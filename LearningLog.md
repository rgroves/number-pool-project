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

- First roadblock from mongodb.com: "WINDOWS SUBSYSTEM FOR LINUX (WSL) - UNSUPPORTED — MongoDB does not support the Windows Subsystem for Linux (WSL)." ☹ Guess I'll go with using MongoDB Atlas... or I could just install the Windows version. 🤔 Atlas seems like the path of least resistance, unless I already have MongoDB installed from previous playing around (which is a possibility).

  - Not installed. MongoDB Atlas it is!

# MongoDB Atlas Setup

- Turns out I had a MongoDB Atlas account from when I went through part of freeCodeCamp's APIs and Microservices Certification curriculum. Time to refamiliarize myself with that.
- Needed to create a new project wiht an M0 (free tier) cluster.
- Needed to create a new user, from sidebar: Security -> Database Access then Database Users -> Add new Database User
- To get my connection info, from sidebar: Data Storage -> Clusters then Connect:
  - Add current ip to white list
  - Get connection info for cli and app (saved this for later; can alwas get back to this via Data Storage -> Clusters in sidebar of Atlas admin panel for the project)
- Setup mongo shell:
  - Downloaded mongo shell for Windows.
  - Unzipped archive and add mongo shell's <unzipped directory>/bin to your \$PATH variable
  - Tested connection - successful!
