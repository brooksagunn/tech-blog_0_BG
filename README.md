# tech-blog_BG

### [My GitHub!](https://github.com/worldunfurled)

## Table of Contents:

* [Description](#description)
* [Installing](#installing)
* [Usage](#usage)
* [Testing](#testing)

## Description

A CMS-style blog site that allows publication of tech-related opinions.

![cms_homepage](https://user-images.githubusercontent.com/80599137/131240782-4e70dc20-fbc7-4732-aa13-462deaa3b551.png)
![cms_login](https://user-images.githubusercontent.com/80599137/131240786-87ebaf86-d07f-4b38-998c-5231bd06349c.png)
![cms_create](https://user-images.githubusercontent.com/80599137/131240787-7b60d2ca-838a-44b2-94aa-300cd71b3c6b.png)

## Installing

The npm packages used for this are as follows:

* *express*: for the server
* *express-Handlebars*: for the views
* *express-session*: for session storage
* *connect-session-sequelize*: for authentication
* *mySQL2*: for database management
* *sequelize*: for modeling and associations
* *dotenv*: to protect environment variables
* *bcrypt*: for password encryption

Use `npm i` to install all of them at once if you have cloned the repo, or use the Heroku link for the ready-to-use live version.

## Usage

The homepage you are led to will be quite empty by design if no users have made posts. Later, this will be filled with all comments from all users. To access other pages, you will be prompted to log in or sign-up. After doing so, you can go to your dashboard and request to create a new post. Specify the title and content and submit! You can then view the post on the homepage and in your dashboard. From the dashboard view, the post can be edited or deleted entirely. Finally, users can make comments on the post and (hopefully) comment you on your good work!  

## Testing

Workbench was used for DB testing. Insomnia helped a bit with the routing.

## E-signature

Brooks Gunn :)
