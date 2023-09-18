# MovieReviewer

A Movie Reviewer that runs in a browser. My code is from this [tutorial](https://www.youtube.com/watch?v=5PdEmeopJVQ).

## How to run

Follow these steps to run a Movie Reviewer in your browser using a private database.

### Setup a MongoDB database

Setup the database and import the data inside `./movieist/_data` as explained in the [tutorial](https://www.youtube.com/watch?v=5PdEmeopJVQ&t=373s).

### Setup MongoDB environment variables in the backend server

Settings should be added in the following file: `./movieist/src/main/resources/.env`. Follow the example in `./movieist/src/main/resources/.env.example`.

### Start backend server

Run using IntelliJ IDEA GUI.

### Install node dependencies

Run the following command inside `./movie-gold-v1`:
```bash
node install
```

### Change axios config and start ngrok tunnel (if used in config)

The `baseURL` must be changed, and ngrok can be removed if desired.

### Start react application

Run the following command inside `./movie-gold-v1`:
```bash
npm start
```