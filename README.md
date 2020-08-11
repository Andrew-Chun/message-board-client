[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Hype-Board Client

Hype-Board is a custom-built message board application built using a React frontend framework.

Users on this platform can create an account to make posts and comments hosted publicly on the forum.

![alt text](https://i.imgur.com/9wh9jJD.png)

## Links
-   Deployed Client: https://andrew-chun.github.io/hype-board-client/

-   Hype-Board API Repo: https://github.com/Andrew-Chun/hype-board-api
-   Deployed Hype-Board API: https://hype-board.herokuapp.com/

## List of Technologies Used
-   HTML
-   CSS
-   JavaScript
-   React
-   Axios
-   Boostrap

## User Stories
-   As a user, I would like to sign in with email and password.
-   As a user, I would like to change password and sign out.
-   As a user, I would like to create, view, update, and delete my posts to the message board.
-   As a user, I want to be able to make comments on other user’s posts
-   As a user, I would like to see all my posts on the message board.
-   As a user, I would like to view all other users' posts on the message board.
-   As a user, I would like to comment on other users' posts on the message board.
-   As a user, I would like to edit/delete my comment on other users' posts on the message board.

## Wireframes
[Hype-Board Landing Page](https://i.imgur.com/flcSDv2.png)

[Hype-Board Main Page](https://i.imgur.com/A2w4YeE.png)

## Problem-Solving Strategy/Process
The main goal was to achieve MVP for this project, which was to have authenticated users be able to CRUD posts. Once meeting the requirements for MVP, I decided to take on the additional challenge of adding comments to specific posts to enable more functionality for the user. Then, I added a feature for users to view all other users on the platform and view the specific posts for the selected user. The most challenging part of this project was making API requests to a Django backend server from a React frontend framework. Routing and passing props between components became quite a challenege when dealing with numerous authenticated routes, but I attempted to keep the code as modular and dry as possible.


## Future Iterations
-Allowing users to comment on comments

-Adding categories or topics and add posts to specific category or topic

-Allow users to tag posts
