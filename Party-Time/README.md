Exercise 3: Party time

Are you excited for the biggest party on the planet? We are and we would like to invite everyone, but there is only a limited number of seats.

Write a function that makes a reservation and log the response to the console. First take a look at the documentation of the API, before you proceed: https://reservation100-sandbox.mxapps.io/rest-doc/api.

Then follow the steps:

    Create a function called makeReservation
    Read the documentation https://reservation100-sandbox.mxapps.io/rest-doc/api#/reservations/post_reservations. Find out:

    Which methods are available (GET or POST)?
    What is the URL?
    What headers are expected?
    What should the request body contain?

    Inside of the makeReservation function, reuse node-fetch method to make an API request
    Include in your request the correct headers and body
    Make use of async/await and try/catch
    Print the response to the console

Hints:

    To set headers use fetch(<URL>, { headers: { 'XXXX': 'YYYY' } }
    The documentation at https://www.npmjs.com/package/node-fetch can be of great help
