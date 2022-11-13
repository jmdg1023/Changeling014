# Changeling014

`Changeling - A word of play for 'Challenging'`

`014 - Natural number following 013 (The previous challenge in this course)`

## Links to Repo and deployment📌

🔸 GitHub Repository [link](https://github.com/jmdg1023/Changeling014)
🔸 Deployment [link]()

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## User Story 👨

```http
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

```

## What this project does 💡💡💡

```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```

## Installation

```
npm install mysql2
npm install sequelize
npm install dotenv
npm install bcrypt
npm install connect-session-sequelize
npm install express
npm install express-handlebars
npm install express-session
```

## Usage

To start the process, go to the deployed site [here](https://warm-beyond-65052.herokuapp.com/)

Then create an account or view the first few blogs and comments.

## Screenshot

![Screenshot](./assets/Screenshot-test.jpg)
![Screenshot](./assets/post.jpg)

## Learning Resources

🔸[Dotenv](https://www.npmjs.com/package/dotenv)

🔸[Sequalize](https://www.npmjs.com/package/sequelize)

🔸[Inquirer](https://www.npmjs.com/package/inquirer)

🔸[SQL2](https://www.npmjs.com/package/mysql2)

🔸[Heroku](https://dashboard.heroku.com/)

🔸[jawsDB](https://elements.heroku.com/addons/jawsdb)

🔸[Express](https://www.npmjs.com/package/express)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/mecuboi/my-profile-website/blob/main/LICENSE)
