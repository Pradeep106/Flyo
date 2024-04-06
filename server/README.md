# Welcom to Flights Service

## Project SEtup

- Clone the project on your local

- Execute `npm install`on the same path as of your root directory of the downloaded project
- Create a `.env` file in the root directory and add the following environment variables -`PORT=300`
- Inside the `src/config` folder create a new file `config.json` and then add the following piece of json

```
{
  "development": {
    "username": <YOUR_DB_LOGIN_NAME>,
    "password": <YOUR_DB_PASSWORD>,
    "database": "Flyo_Search_Dev",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
}

```
