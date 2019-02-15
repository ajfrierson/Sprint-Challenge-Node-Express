Mention two parts of Express that you learned about this week. We learned about Middleware (which is basically all of express) and we learned about Routers which help to break up complex endpoints.

Describe Middleware? Middleware is an array of functions that are executed in the order they appear in the server code. What's most important about them is that they have access to the request and response objects and the next() function in a server. As such they manipulate these objects and control the execution flow and paths of server code.

Describe a Resource? A resource is a piece of data accessed by a unique locator.

What can the API return to help clients know if a request was successful? A status code, specifically of '200'

How can we partition our application into sub-applications? Using express Router and passing around endpoints as modules.

