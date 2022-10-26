# Fetch 
#The fetch() method in JavaScript is used to request data from a server. The request can be of any type of API that return the data in JSON or XML. The fetch() method requires one parameter, the URL to request, and returns a promise.
![1]()
#Parameters: This method requires one parameter and accepts two parameters:

#### 1 URL: It is the URL to which the request is to be made. Options: It is an array of properties. It is an optional parameter.
#### 2 Return Value: It returns a promise whether it is resolved or not. The return data can be of the format JSON or XML. It can be an array of objects or simply a single object.

##### Making Post Request using Fetch: Post requests can be made using fetch by giving options as given below:

### What is Axios?
#Axios is a promise-based HTTP Client for node.js and the browser. It is isomorphic (= it can run in the browser and nodejs with the same codebase). On the server-side it uses the native node.js http module, while on the client (browser) it uses XMLHttpRequests.