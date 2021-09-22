# DAT250 Assignment 4

## Ex 1

In the first part I cloned the counter project and started App.java, I then used postman to send a GET request to localhost:8080/counter, this returned a Json representation of a counter object. Afterwards I sent a PUT request to update the values of the counter.

## Ex 2

In the second experiment I started a new project from scratch but took a lot of inspiration from the counter example. The assignment did not mention anything about using a database so I assumed that I was supposed to do the same as in the counter example with only local storing of the Todo objects. In the spark documentation I found out about 
*path groups* that made it more easy to create all the CRUD functions under one path. 
The methods I made were two get methods, one for all todo objects and one for a specific todo object, a post method, a put method and a delete which deleted a specific todo object.

Return from postman when using get

![todoWebApi](https://user-images.githubusercontent.com/42749439/134335976-0b1c3bc5-4264-4693-8233-daf36f3f1d76.png)

## Ex 3

I checked out Swagger and tried to specify the TodoApi there, it seamed like a very practical tool for colaberating and planning APIs however I could not find any option to export
it with Spark/Java framework. 

## Ex 4

For the response to return XML it's possible to use the *after* method to specify the response.type to be "text/xml", I did not figure out a good way for the api to consume 
xml, one way that might be possible is to use the before method and convert the request.body to json but I did not try it out (I'm guessing there is a better way of doing it)










