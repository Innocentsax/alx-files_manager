# Overview:
* This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

* The objective is to build a simple platform to upload and view files:

- User authentication via a token
- List all files
- Upload a new file
- Change permission of a file
- View a file
- Generate thumbnails for images


## Core technologies

|                                                                                                         |                                                                                      |                                                                                              |
| ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| ![Redis](https://upload.wikimedia.org/wikipedia/en/thumb/6/6b/Redis_Logo.svg/1000px-Redis_Logo.svg.png) | ![MongoDB](https://webassets.mongodb.com/_com_assets/cms/mongodb_logo1-76twgcu2dm.png) | ![NodeJS](https://d2eip9sf3oo6c2.cloudfront.net/tags/images/000/000/256/full/nodejslogo.png) |

## Testing and Jobs

A queueing job mechanism for creating thumbnails of photos uploaded to the application is included in the project. When a new user is created, it also leverages this feature to generate a welcome message. Bull is used in all of this. 
![Bull & NodeJS](https://raw.githubusercontent.com/OptimalBits/bull/master/support/logo%402x.png)

Mocha is used in combination with Chai for testing the app.

![Mocha & Chai](https://miro.medium.com/max/499/0*WpXBkrfgR2g9dw2T.png)


# Resources
## Read or watch:

- Node JS getting started
- Process API doc
- Express getting started
- Mocha documentation
- Nodemon documentation
- MongoDB
- Bull
- Image thumbnail
- Mime-Types
- Redis
# Learning Objectives
* At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- how to create an API with Express
- how to authenticate a user
- how to store data in MongoDB
- how to store temporary data in Redis
- how to setup and use a background worker
# Requirements
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the js extension
- Your code will be verified against lint using ESLint
