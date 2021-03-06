# TinyApp Project

TinyApp is a full stack web application built with Node and Express that allows users to shorten long URLs.

## Final Product

![Screenshot of Login](https://github.com/MaxHuw/tiny-app/blob/test/stretch/docs/login.png)

![Screenshot of users current TinyURLs](https://github.com/MaxHuw/tiny-app/blob/test/stretch/docs/ulrsList.png)

![Screenshot of individual TinyURL's information](https://github.com/MaxHuw/tiny-app/blob/master/docs/editURL.png)


## Dependencies

    "bcrypt": "2.0.0",
    "body-parser": "^1.18.3",
    "cookie-session": "^2.0.0-beta.3",
    "ejs": ">=2.5.5",
    "express": "^4.16.4",
    "method-override": "^3.0.0",
    "valid-url": "^1.0.9"

## Getting Started

* Install all dependencies (using 'npm install' command).
* Run the development web server using the 'node express-server.js' command.

## Notes

* Left the email & password fields as 'text' in the forms, because it makes testing (loggin in and out again with same / different user) faster.