# Movie finder data.

## General Info
* I used the Express framework to build a server that can talk to another server and cache the results.
* The web server will respond to GET requests for http://localhost:3000/ and return the data from the API.
*  When making a second request to the same endpoint the server should not return data from the API, but instead from some object or array.

## Setup
Fork/clone the repo onto your local system then run the following commands:
```
npm install
```
```
npm start
```
Then try one of the following in your browser:
* http://localhost:3000/?t=baby%20driver
* http://localhost:3000/?i=tt3896198

## To run the test, use a separate terminal:
```
npm test
```
