# Social-Network-API

# User Story
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

# Acceptance Criteria
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

# Technology
* JavaScript
* Node.js
* Express.js
* Mongoose
* MongoDB
* Insomnia
* Moment

# Installation:
This repo is not to be deployed, if you wanted to, you could by doing the following:

1. Download the repo files from the link below
2. You must have mongoDB installed
3. Run the following at the command line:

- npm init -y
- npm install express
- npm install mongoose
- npm install moment

# Mock-Up:
The following animation shows GET routes to return all users and all thoughts being tested in Insomnia:

![18-nosql-homework-demo-01](https://user-images.githubusercontent.com/86209350/176320349-06972180-0395-486e-be8b-a2d1b295b703.gif)

The following animation shows GET routes to return a single user and a single thought being tested in Insomnia:

![18-nosql-homework-demo-02](https://user-images.githubusercontent.com/86209350/176320431-76522bd5-d049-4afa-a72e-6c0764fe3b98.gif)

The following animation shows the POST, PUT, and DELETE routes for users being tested in Insomnia:

![18-nosql-homework-demo-03](https://user-images.githubusercontent.com/86209350/176320470-eafafd72-8de8-4dc3-bb4c-191178fdae4e.gif)




