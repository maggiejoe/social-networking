# Challenge #18 - Social Networking


## Description
This challenge was to test my abilities with using a noSQL database such as MongoDB. I was given no starter code and created all of the schemas and routes to simulate a social networking program where friends and thoughts can be added, changed and deleted to a person's user profile. This was not a front end application and can be tested through Insomnia.

## Walkthrough Video
[Check out walkthrough video #1 here!](https://drive.google.com/file/d/1Fyb7PgvGOXvNmD3dANBOoLnaRzIwDk1F/view)

[Check out walkthrough video #2 here!](https://drive.google.com/file/d/1nR7SCm2xglKpAa80KrHlP60cmP8BXR9g/view)

## Deployment Link
[Check out my GitHub!](https://github.com/maggiejoe/social-networking.git)


# Challenge #18 Criteria


## User Story
`AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data`

## Acceptance Criteria
`GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list`

## Walkthrough Video
* The walkthrough video must show all of the technical acceptance criteria being met
* The walkthrough video must demonstrate how to start the application’s server
* The walkthrough video must demonstrate GET routes for all users and all thoughts being tested in Insomnia
* The walkthrough video must demonstrate GET routes for a single user and a single thought being tested in Insomnia
* The walkthrough video must demonstrate POST, PUT, and DELETE routes for users and thoughts being tested in Insomnia
* Walkthrough video must demonstrate POST and DELETE routes for a user’s friend list being tested in Insomnia
* Walkthrough video must demonstrate POST and DELETE routes for reactions to thoughts being tested in Insomnia.

## Technical Acceptance Criteria
* Satisfies all of the preceding acceptance criteria plus the following:
    * Uses the Mongoose package (Links to an external site.) to connect to a MongoDB database
    * Includes User and Thought models outlined in the Challenge instructions.
    * Includes schema settings for User and Thought models as outlined in the Challenge instructions
    * Includes Reactions as the reaction field's subdocument schema in the Thought model
    * Uses functionality to format queried timestamps properly

## Repository Quality
* Repository has a unique name
* Repository follows best practices for file structure and naming conventions
* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc
* Repository contains multiple descriptive commit messages
* Repository contains a high-quality README with description and a link to a walkthrough video