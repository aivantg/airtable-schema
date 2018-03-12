# airtable-schema

Download Airtable schema to JSON file.

## Clone or download the repository.

`git clone https://github.com/cape-io/airtable-schema.git && cd airtable-schema`

## Edit run.js

Make sure you have password enabled on your Airtable account.

Change the values of `email`, `password`, `baseId`. The `baseId` can be gotten from the URL https://airtable.com/`{baseId}`/api/docs.

## npm start

Running `npm start` will open an electron app browser window that will fill in your username and password. Once the api page loads it will download a json file with the schema information to the downloads directory.
