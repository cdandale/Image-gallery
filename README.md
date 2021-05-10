
# Getting started #

Clone or download the files

Create new firebase project at https://firebase.google.com/

Once you create a project with firebase, you will have to update the environment variables
in a new .env file. Make sure you create this file at root folder level and not inside src
or public folder.

You will have to add all the variables from src/firebase/config.ts file into the .env file properly 

Once that setup is done, you can run 'npm-i' to install the dependencies and 'npm-start' to execute the project

# About the website #
Currently what the application does is:
- signup for an account
- sign in
- upload multiple images
- delete the images.
I have used Firestore database to store two tables: Users and Images.

# Additional features for application #
- I will be implementing unit tests using Jest.Currently the application is not fully tested.
- Add tags
- Search by User/ tag
- Functionality to Download images
- Functionality to like the images
