This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## About The App

This app will use [Spotify API](https://developer.spotify.com/documentation/) to build a website that allows users to search the Spotify library, create a custom playlist, then save it to your own Spotify account.

## Installation
To run the app successfully, you’ll need to

### `npm install`

add your own [Spotify API Client ID](https://developer.spotify.com/documentation/) to <strong>src/util/Spotify.js</strong>.

Start the Create React App server, run:

### `npm start`

## How To Deploy The App (Optional)
you will use [surge](https://surge.sh/) to deploy your project.

You will start by installing surge globally.

In your console, run:

### `npm install --global surge`

Before you deploy, you need to think of a domain name with the following format:

### `SOME_NAME.surge.sh`

<strong>SOME_NAME</strong> can be replaced with anything you like.

Next, you need to replace or add this URI to two locations in your project.
1) In *Spotify.js, set 'redirectUri' to your new domain
2) In your [Spotify application](https://developer.spotify.com/dashboard/), add your new domain as a redirect URI

Back in the command line, from the Jammming project’s root directory, run:

### `npm run build`

'cd' into the 'build' directory and run the command

### `$ surge`

Follow the steps on the screen. Change the domain value to your new URI.

## Trying The App

If you want to try the app, the link provided below is to lookup how the app will look like. The app will fully functional to add a new playlist to my spotify account, so please don't try to abuse my spotify playlist. Thank you

[nyomanadi-spotify.surge.sh/](nyomanadi-spotify.surge.sh/)