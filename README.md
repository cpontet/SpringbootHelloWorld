# Hello World with Spring Boot REST API

Based on [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service)

Run the app.

Now that the service is up, visit http://localhost:8080/greeting, where you should see:

```json
{"id":1,"content":"Hello, World!"}
```


Provide a name query string parameter by visiting http://localhost:8080/greeting?name=User. Notice how the value of the content attribute changes from Hello, World! to Hello, User!, as the following listing shows:

```json
{"id":2,"content":"Hello, User!"}
```
