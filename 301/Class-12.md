# Status Codes Based On REST Methods
## In your own words, describe what each group of status code represents:
* 100’s = These are informational status codes; these status codes tell the user that the header of the  request is delivered and the server will try to response to the client


* 200’s = These are the success codes. these status codes tell the client that its request is accepted.


* 300’s = These are redirection codes. these status code tell the user that the resource is not available at that URL .


* 400’s =  These are the client error codes. these status codes refer to an error in request from client.



* 500’s = These are the server error codes. these status codes refers to a problem within the server  maybe it is unreachable . 


## What is a status code 202? 
this status code is returned  when (CUD)(Creat,Update,Delete) operations happen in  asynchronous mode and tell the client that the request is accepted but it need time to accomplish it.
## What is a status code 308?
it happens with READ and tell the client that the current URI is not available and he should use the returned one.
## What code would you use if an update didn’t return data to a client?
204 No Content
## What code would you use if a resource used to exist but no longer does?
I think 307 Temporary Redirect or 308 Permanent Redirect.
## What is the ‘Forbidden’ status code?
403 Forbidden: The client has authorized , but still has no permissions to access the resource.


# Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes
## Why do we need to pull our MongoDB database string out of our server and put it into our .env?
because the MongoDB database string refers to localhost and  when we dyploys the sever we need to change this string in the dyployed website to live MongoDB database string.
## What is middleware?
The middleware is a code that runs when the sever gets a request but before the request gets passed to server routes.
## What does app.use(express.json()) do?
tell the server to accept json as body 
## What does the /:id mean in a route?
It means there is a parameter `id` after the slash and we can access it by `req.params.id`
## What is the difference beween PUT and PATCH?
The `PATCH` updates only what the user passes in the route and the `PUT` update all the information the user passes. Although the user requests some update the `PUT` updates what the user wants as well as the other information by updating them to what they were before.
## How do you make a defalut value in a schema?
Just by writing `default` keyword inside schema key object and giving it a value.
## What does a 500 error status code mean?
It means that the error is from the server side not from the client.
## What is the difference between a status 200 and a status 201?
`201` is more specific of what happened and `200` is general status which means success

## Things I want to know more about

I want to learn more a bout the middleware used in the attached video.


## References 

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
[Build A REST API With Node.js, Express, & MongoDB - Quick ](https://www.youtube.com/watch?v=fgTGADljAeg)