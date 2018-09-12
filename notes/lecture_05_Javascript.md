# CS50 Web: Lecture 5 Javascript  

## Outline
* Client vs. Server
* Javascript 
* Ajax 
* Web Sockets

### Client vs. Server 
* flask/python on server while HTML/CSS/JS are mostly local on client computers. 
* advantages of running code on the client side: 
	* take off the load from the server 
	* it's faster 

### Javascript - ES6 
* `<script> </script>` 
* `alert()`
![](./img/JS_function.png) 
* Events
![](./img/JS_events.png) 
* `document.querySelector(`h1`).innerHTML = 'Good!'`: extract HTML element (only find the first HTML tag) and modify it. 
![](./img/JS_query.png) 
* `let counter = 0;`: var definition 
* `counter % 10 === 0`: checking equality. 
* formatted string 
![](./img/JS_formatted_str.png) 
* refactor JS out of HTML (when DOM is fully loaded): 
![](./img/JS_event_listener.png) 
* defining variables 
	* const: constants
	* let: scoping is the innermost curly braces 
	* var: exists in the innermost function 
![](./img/JS_var.png) 
* for HTML tags, we can add attribute like `data-<placeholder>` to specify user-defined additional info. 
![](./img/JS_dataset.png) 
* Arrow Functions: defining functions more easily 
![](./img/JS_arrow_func.png) 
![](./img/JS_arrow_func2.png) 
![](./img/JS_arrow_func3.png) 
* this is referred to object before the function(). 
![](./img/JS_this.png) 
* storing information - local storage:
* `localStorage` is a variable in JS which can be used to store data even after closing the page. Most of the browsers support this variable. Namespace collisions will not occur for different domains.

### Ajax 
* It stands for asynchronous JS and XML. 
* A technology we can use in order to get more information from a server even without needing to reload an entire new page. 

### Web Sockets - Socket.IO
* real-time communications 
* broadcasting and receiving information 
* `@socketio.on("str")`: decorator for listening to submit events from client to server. 
* `emit("", {}, broadcast=True)`: broadcasting from server to all clients 
* 
