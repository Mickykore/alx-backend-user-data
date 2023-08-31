# User Authentication Service

In this project, we will implement an authentication system in Flask. While in real-world scenarios, it's recommended to use established modules or frameworks for authentication, this project aims to guide you through building a basic authentication mechanism for learning purposes.

## Resources

Read or watch the following resources to better understand authentication in Flask:

- [Flask Documentation](https://intranet.alxswe.com/rltoken/lKExyvivrrW4eh0eI8UV6A)
- [Requests Module](https://intranet.alxswe.com/rltoken/py7LuuD1u2MUwcaf8wnDzQ)
- [HTTP Status Codes](https://intranet.alxswe.com/rltoken/py7LuuD1u2MUwcaf8wnDzQ)

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without using external references:

1. Declaring API routes in a Flask app
2. Getting and setting cookies
3. Retrieving request form data
4. Returning various HTTP status codes
5. Interacting with SQLAlchemy for database operations
6. Implementing a basic authentication mechanism
7. Designing a separation of concerns between app, authentication, and database

## Requirements

- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- A `README.md` file at the root of the project folder is mandatory
- Your code should adhere to the `pycodestyle` style (version 2.5)
- Use SQLAlchemy 1.3.x
- All your files must be executable
- The length of your files will be tested using `wc`
- All your modules, classes, and functions should have appropriate documentation
- All your functions should be type annotated
- The Flask app should interact with `Auth` and not with the database directly
- Only public methods of `Auth` and `DB` should be used outside these classes

## Setup

You will need to install the `bcrypt` library:


