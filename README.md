Task
Create a React application that provides the features described in this document.
The basic requests of the task must be fulfilled. Further creative approaches are of course always desired and a great bonus.
Good luck and have fun!

Setting up the project
You can use create-react-app in order to kickstart your assignment.
If you prefer, you can setup webpack yourself as well, or use Parcel.

Git
Just fork the repository and add your solutions to your fork, so that we can have a look at your work. Thank you very much!

Description
You are developing a new dashboard. Your task is to create a new dashboard with which the user can manage his account.
Of course, it is not supposed to be complete. We would like to limit ourselves to just one excerpt.
In this scenario, the form used to modify the user profile information has to be created.
The form contains two tabs, as specified below and shown in the mockup.
The user wants to be able to switch between the two tabs and to enter the following information:
In the first tab (basic data):

Change e-mail address
Change Password
The password must have certain properties:

"Password" and "Password repeat" fields need to be identical (including an indicator for this equality)
The password field should accept Uppercase letters, lowercase letters, numbers and special characters
A multi-color password strength indicator should be implemented


Button to update the user data

In the second tab (Address):

Change first name
Change Last Name
Change address (street, house number, postal code)
Change country (Germany, Austria, Switzerland are available)
Button to update the user data

The form also needs a button to submit the information through a fake AJAX call.
It is important that the user receives feedback if his input is incorrect, correct, his data has not been saved and his data has been successfully saved.
The layout also contains a header and a sidebar, which are not functioning in this test.

Layout
Please do not use Bootsrap or similar frameworks for CSS, just create new CSS from scratch.
Please note that this dashboard should be responsive, and be usable on mobile and tablets as well.
When styling, you can decide for yourself what this dashboard should look like.
However, bonus points are awarded if the styles resemble those of energieloft.de and could fit as seamlessly as possible within that website.
A basic layout mockup can be found in the file: mockup.jpg.

Code structure
The application should at the very least use the following:

React.js framework
A CSS pre-compiler (SASS, LESS, SCSS) or other CSS approaches (CSS modules, Styled components)

You can use external modules like Redux, informed, and whatever you think is necessary.
In React, the application is to be assembled into suitable, reusable React components.
Possible components would be:

Header
Footer
User
UserInputTabs
Aside

It is however up to you to provide the structure you think works best in a production-level app.
Bonus points would be awarded for setting up and using linters.

Deadline
You have a week to work on this project, just note down in the end how many hours it took to complete (roughly), as this can be an interesting matter of discussion.
Thank you, and have fun!
