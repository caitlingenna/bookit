#### How to run the project

- Fork or clone the repository
- Open the root folder i.e. bookit
- Run `npm install`
- Now Create a web Firebase project by visiting the firebase website.
- Copy the .env.example and remove .example from the file by renaming it.

- insert below lines of code into that file.

```
REACT_APP_API_KEY=""
REACT_APP_AUTH_DOMAIN="",
REACT_APP_DATABASE_URL="",
REACT_APP_PROJECT_ID="",
REACT_APP_STORAGE_BUCKET="",
REACT_APP_MESSAGING_SENDER_ID="",
REACT_APP_APP_ID="",
REACT_APP_MEASUREMENT_ID=""
```

- Run `npm start` in the terminal for running on localhost:3000

Note: If this does not work look try removing the .env variables from the firebaseConfig and store the actual config values which you got from the firebase and then run the `npm start`
