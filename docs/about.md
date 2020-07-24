# About

This API is written for our [online bookstore](https://mycool-bookstore.io).

The API is based on [Flask](https://flask.palletsprojects.com/en/1.1.x/ "Flask website").

With this API you can list, update, add and delete books.

This API is licensed under the MIT license.

For any help or support please contact `support@mycool-bookstore.io`

## Validation

To check our endpoints, we can use Postman.
Postman is an application for testing APIs that works by sending requests to the web server and getting the responses back.

We can test our endpoints via Python as well, but it’s nice to have a sleek user interface to make requests with without the hassle of writing a bunch of code just to test them out.

Once we have Postman installed, let’s start testing our endpoints. In this article, we’ll only test our GET and POST requests.

First let’s run our app.py file. To check if everything is working, we’ll try a GET request.

From the dropdown menu, we select GET and send a request to http://localhost:4996/booksApi.