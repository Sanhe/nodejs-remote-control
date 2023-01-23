# NodeJS Websocket Remote Control

Simple NodeJS Websocket Remote Control server with static web client.

## Overview

It is built using Node.js and TypeScript.

## Presets

* Node.js v18.0.0 is installed.

* Make sure print screen functionality works on your OS. It might not work on Ubuntu.

## Getting Started

* Clone the repository to get the latest version of the code.

```bash
git clone git@github.com:Sanhe/nodejs-remote-control.git
```

* Switch to dev branch.

```bash
git checkout dev
```

* Run npm installation.

```bash
npm ci
```

* Copy `.env.example` to `.env` and update the websocker server and client ports if needed.


## Run the application

See package.json for all available commands.


* App served @ `http://localhost:8181` without nodemon

---

**All commands**

Command | Description
--- | ---
`npm run start:dev` | App served @ `http://localhost:8181` with nodemon
`npm run start` | App served @ `http://localhost:8181` without nodemon

**Note**: replace `npm` with `yarn` in `package.json` if you use yarn.
