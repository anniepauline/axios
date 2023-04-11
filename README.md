# axios
Used JSON placeholder,[fake REST API](https://jsonplaceholder.typicode.com/) for our data


>Axios is an HTTP client library based on promises, which helps to make request to your own backend or a 3rd party API to fetch data, which is almost similar to the `FETCH API` that's built into the browser. It makes sending asynchronous HTTP requests to REST endpoints easier and helps you perform CRUD operations.
Axios is more simpler and can be used with node.js and perform complex tasks.

The `GET` request :
>Send a request to the API and recieves a response with a status of 200 along with headers, data and config. The data limit is set to 5 objects.

The `POST` request:
>Generates a response of the data sent that is send to the server in the form of Objects.


The `PUT` request:
>Replaces the entire resource while updating data, the ID is included in the URL, with the method being PUT.

The `PATCH` request:
>Updates data incrementally and not the entire resource.


The `DELETE` request:
>Takes in the ID and deletes the given record and it returns an empty object.

The `SIMS`(Simultaneous requests):
>Can perform multiple requests using axios.all() which takes in an array of requests, and when all the promises are fulfiled, we then get our response and handle it.


AN `INTERCEPTORS`:
>Every time a request is made, an interceptor, captures the info about the request and is displayed on the console.


`CUSTOM HEADERS`:
>Mainly used in authentication with JSON web tokens, while making a request to login, validating the login and when we get back a token we have to send that token in the header to access protected routes, stored in the config of the headers section.

`TRANSFORM RESPONSES`:
>Used to transform requests and responses.

`ERRORS`:
>Used to handle error.We can perform some kind of functionality based on the errors


`CANCEL TOKENS`:
>We can cancel any requests on the fly, by using axios.CancelToken.source()


