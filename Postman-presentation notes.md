# Talk preparation:

1) Decide my "call to action"
* make an outline
* Include a summary slide of main points (take-aways)
2) Create a story
3) Test the talk for effectiveness
* have the audience do stuff
4) Create the slides, make intro slide last.
* add my contact information to every slide
* create a link to Resources like the talk. Github is my preferred location.
5) Practice the talk multiple times until I know how long it takes.

Bonus: Don’t Overthink

# Call to action

Getting started with Postman

* What is HTTP status Code
* What is API
* How does Postman help?
* How to Make a Get request.



## What is HTTP status Code

Resource for front end questions
https://developer.mozilla.org/en-US/

Http Status codes
https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

* HTTP status codes are returned by the server to tell the browser how the "HTTP Request" was handled.
* Front end is happy with success (200). Any other response can be problematic.
* Postman is an API testing platform. Postman shows the http status codes for a request and much more.

## What is API

List of Public APIs
https://github.com/public-apis/public-apis

* Application Programming Interface (API) allows two programs to communicate with each other.
* HTTP is a collection of rules for transmission of data on the world wide web.
* APIs primarly use 4 Request Methods.
  * GET retrieves data from an API.
  * POST sends new data to an API.
  * PUT update existing data.
  * DELETE removes existing data.
* APIs are URLs (https://postman-echo.com/get)
  1) URL connects to External system
  2) External system reads parameters send with URL
  3) External system resolves request
  4) External system returns a response with HTTP status code

## How does Postman help?

Postman Documentation & Tutorials
https://learning.postman.com/docs/getting-started/introduction/

Navigating Postman
https://learning.postman.com/docs/getting-started/navigating-postman/

* Postman simplifies APIs so developers can test APIs without writing any code.
* Since we use Postman instead of doing the coding ourselves we must learn the application interface and other things that are only specific to Postman and not all API designs.

## How to Make a Get request.

Send first request with Postman
https://learning.postman.com/docs/getting-started/sending-the-first-request/

### Workflow to know

1) Click New [button]
2) Select "HTTP Request"
3) Paste in API URL
4) Click Send [button]
5) Read "Body" that comes back with the server response

### Add credentials to API

