# Web API IV Challenge

In this challenge, you will **deploy** an API of your choosing to `heroku`.

## Instructions

You are allowed, and **encouraged**, to collaborate with other peers. Please follow the twenty-minute rule, before seeking support from your PM and Instructor.

## Minimum Viable Product

Pick any API, could be one of your past projects, and deploy it to `heroku`. Once deployed, send the URL to the TL for your group.

## Stretch Goal

- add support for environment variables using `.env` files. You can use the [dotenv](https://www.npmjs.com/package/dotenv) npm module.


### BASE URL: https://lw-lotr-user-list.herokuapp.com/ 

| request | endpoint             | description                                     |
|---------|----------------------|-------------------------------------------------|
|   GET   | /api/users/          | returns all users                               |
|   GET   | /api/users/:id       | returns specific user                           |
|   GET   | /api/users/:id/posts | returns specific user's posts                   |
|   POST  | /api/users/          | creates a new user, needs "name" key/val pair   |
|   POST  | /api/users/:id/posts | creates a new post, needs "text" key/val pair   |
|   PUT   | /api/users/:id       | edtits existing user, needs "name" key/val pair |
|  DELETE | /api/users/:id       | deletes existing user                           |

