# HOT TAKES

This is the front end and back end server for Hot Takes :

The web's best HOT SAUCE reviews

![Logo](https://i.postimg.cc/y6MbCsR9/Hot-TAKES-1.png)

![Logo](https://i.postimg.cc/bwTCnnBH/Hot-Takes-2.png)

## Installation

Clone this repository

You have to initialize the submodules :

```bash
  git submodule init
```

```bash
  git submodule update --remote
```

**Back end Prerequisites:**

You will need to have Node and `npm` installed locally on your machine.

To run this project, you will also need to add the following environment variables to your .env file in your backend folder.

`PORT=3000`

`APP_SECRET="hottakes1234"`

`RANDOM_TOKEN_SECRET="YOURTOKENPASSWORD"`

**Back end Installation:**

From the "backend" folder of the project, run `npm install`.

You can then run the server with `node server` or `nodemon server`.
The server should run on `localhost` with default port `3000`. If the
server runs on another port for any reason, this is printed to the
console when the server starts, e.g. `Listening on port 3001`.

**Front-end Installation:**

Here are the dependancies you need to install:

- NodeJS 12.14 or 14.0.
- Angular CLI 7.0.2.
- node-sass : make sure to use the corresponding version to NodeJS. For Noe 14.0 for instance, you need node-sass in version 4.14+.

Run `npm install`, and run `npm install --save-dev run-script-os`.

On Windows, these installations require to use PowerShell in administrator mode.

**Front-end usage:**

Run `npm start`. This should both run the local server and launch your browser.

If your browser fails to launch, or shows a 404 error, navigate your browser to http://localhost:8080.

The app should reload automatically when you make a change to a file.

Use `Ctrl+C` in the terminal to stop the local server.

## API Reference

![Logo](https://i.postimg.cc/13mtMxvh/HOTAPI1.png)
![Logo](https://i.postimg.cc/s2ZR4wCC/HOTAPI2.png)

## Tech Stack

**Client:** Angular

**Server:** NodeJS, Express, MongoDB
