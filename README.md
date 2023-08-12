# Cash poor kitties
by Jessica Cameron
She Codes crowdfunding project - DRF Backend.
## Link to Deployed DRF Project
https://divine-thunder-6842.fly.dev/projects/
## About
The purpose of this website is to provide a platform for owners or charities to crowdsource for cats needs. Users can create a Project and/or submit a pledge to fund cat funding requests, whether that's basic food and care, or toys and grooming.
## Features
The features of the MVP for this project include:
* [X] Ability for a user to create a project
* [X] Ability for a user to make a pledge
* [X] Ability for a user to log in and out
* [X] Ability to create a new user
### Stretch Goals
The following features are stretch goals following MVP
* [] Ability for a Supporter to edit an existing pledge
* [] Ability for a User to edit or delete an existing Project
## API Specification
| HTTP Method | Url | Purpose | Request Body | Successful Response Code | Authentication <br /> Authorization
| --- | ------- | ------ | ---- | -----| ----|
| GET | projects/ | Return all projects | N/A | 200 | N/A |
| POST | projects/ | Create a new project | project object | 201 | User must be logged in. 
| GET | pledges/ | Post a new pledge | pledge detail | N/A
| POST | users/ | New User | user detail | token
| GET | projects/1/ | N/A | N/A

## Database Schema
![](./crowdfunding/images/database.schema.jpg)
## Wireframes
{{ Insert your wireframes }}
![image info goes here](./crowdfunding/images/wireframe.jpg)
## Colour Scheme
![Not selected yet]
## Fonts
![Not selected yet]
## Submission Documentation
{{ Fill this section out for submission }}
Deployed Project: [Deployed website](https://divine-thunder-6842.fly.dev/projects/)
### How To Run
Open visual studio, directory:
Runserver from folder that contains manage.py with the following bash command
```
python manage.py runserver
```

### Updated Database Schema
{{ Updated schema }}
![image info goes here](./docs/image.png)
### Updated Wireframes
{{  Updated wireframes }}
![image info goes here](./docs/image.png)
### How To Register a New User
{{ Step by step instructions for how to register a new user and create a new project (i.e. endpoints and body data). }}
### Screenshots
* [] A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
![image info goes here](./docs/image.png)
* [] A screenshot of Insomnia, demonstrating a successful POST method for any endpoint.
![image info goes here](./docs/image.png)
* [] A screenshot of Insomnia, demonstrating a token being returned.
![image info goes here](./docs/image.png)