## NodeJS & Cloudinary API

This is an introductory course into cloudinary for NodeJS Developers

*<b>NOTE: </b>* You can download or clone this repo (after which you will run `npm install` or `npm i` to install the neccessary packages for running and testing the project. Then run `npm start` on your terminal to start the server, which can then be accessible on the following URL: `http://localhost:3000`) or if you want to follow the steps in setting up your own: below is a quick guide on how to do so.

## Setup and Installation

- Download and install NodeJS from the following URL [Installation Link](https://nodejs.org/en/download/)
- Verify the installation by typing `node --version` on your terminal
- Also verify your `npm version` by typing `npm --version`

## Setting up a NodeJS Project

- Follow this link for more insights: [setting up a nodejs project](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment)

## Cloudinary Account

- Sign up for a free account at: [create an account on cloudinary](https://cloudinary.com/users/register_free)
- Or login here if you already have an account on cloudinary: [log into your account at cloudinary](https://cloudinary.com/users/login)

## Cloudinary Access

- In nodejs and other technologies, in-order to access and perform manipulations/transformations on your assests on cloudinary; you need to get the following information/secrets from your cloudinary dashboard:

1. Cloud Name
2. API Key
3. API Secret
4. Or API Environment variable - we will emphasize on this later on.

These are used for communicating with cloudinary's API and signing your requests made unto cloudinary.

*<b>NOTE:</b>* Don't expose the above keys/secrets, store them as prescribed here or use any other secure way to store your secrets.

## Securing Cloudinary keys/scerets

- Install dotenv package using the following command `npm i dotenv` or `npm install dotenv`.
- Create a `.env` file within the root of your application.
- Store the following variable inside yout .env file: `CLOUDINARY_URL=<get and paste your cloudinary url here>`. Please remove these `<` and `>` when storing your secret.
- Create a `.gitignore` file in your project and add `.env` into it as done within the .gitignore file in this repository so as to avoid pushing this unto Github for those using it.