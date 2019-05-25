# Create a Simple, Stylish, and Secure Node Express App

In this tutorial series, you'll learn how to create a secure and simple **Node.js** application built with the **Express** web framework. You'll see how **Passport.js with Auth0** is used to manage user authentication and protect routes. On the frontend, you'll use **Pug** templates for rendering views along with **CSS** for maintaining style sheets.

Additionally, you'll learn to streamline your Node.js development workflow by using `nodemon` to restart the server and `browser-sync` to reload the browser whenever relevant source files change.

In this first part, you'll build the foundation for the user interface and API. In the second part, you'll learn how to secure it by adding user authentication.

In this second part, you'll secure the web app by adding user authentication to it using [Passport.js](http://www.passportjs.org/) and [Auth0](https://auth0.com/).

![Styled page created with background image using Pug, Express, and CSS](https://cdn.auth0.com/blog/create-a-simple-yet-secure-node-express-app:styled-page-created-with-background-image-using-pug-express-and-css-3.png)

## Auth0: Never Compromise on Identity

At [Auth0](https://auth0.com/), we make heavy use of full-stack JavaScript to help our customers to [manage user identities including password resets, creating and provisioning, blocking and deleting users](https://auth0.com/user-management). We also created a serverless platform, called [Auth0 Extend](https://auth0.com/extend/), that enables customers to run arbitrary JavaScript functions securely. Therefore, it must come as no surprise that using our identity management platform on JavaScript web apps is a piece of cake.

[Auth0 offers a **free tier**](https://auth0.com/pricing) to get started with modern authentication. Check it out, or <a href="https://auth0.com/signup" data-amp-replace="CLIENT_ID" data-amp-addparams="anonId=CLIENT_ID(cid-scope-cookie-fallback-name)">sign up for a free Auth0 account here</a>!

![Auth0 Login Page](https://cdn2.auth0.com/docs/media/articles/web/hosted-login.png)