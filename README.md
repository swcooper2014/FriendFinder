# FriendFinder

Friend Finder implements friend matching based on the user's responses to a ten question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined.

The application is implemented using a Node.js and Express server on the back end and the Materialize CSS framework on the front end.

Demo
(Heroku Link Here)

Installation
To install the application follow the instructions below:

    git clone https://github.com/swcooper2014/FriendFinder.git

    cd FriendFinder

    npm install

    node server.js

The application will now be running locally on PORT, in this case that is port 8080. You can then access it locally from your browser at the URL localhost:PORT, in this case localhost:8080.

Tehcnologies Used:

    HTML

    CSS

    Materialize CSS

    Node.js

    Express NPM Package (https://www.npmjs.com/package/express)

    PAth NPM Package (https://www.npmjs.com/package/path)

    Body-Parser NPM Package (https://www.npmjs.com/package/body-parser)
