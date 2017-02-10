# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The purpose of a backend is to allow multiple users access to an API to connect them to a single application.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The model
```

Which layer in the MVC pattern communicates with the model?

```md
The controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Because the HTML and CSS we create will do everything the views are intended to do.
```

What does C.R.U.D stand for?

```md
Create Read Update Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
In the controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
index
new
create
show
update
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1. The GET request is recieved and goes through the router and then the controller chooses the best route.
2. The proper route is sent out with the given paramters assigned to it.
3.The model performs the request
4. The model gives a response back
5. The controller gives back the response returned from the model
6. The server renders the data as an HTTP response in the browser
```

What is the command to generate a new rails-api app?

```bash
rails-api new my_api
new is the command
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
dr:drop
db:create
db:migrate
db:seed
db:examples
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails generate scaffold pet name:string age:integer
//reminder: scaffold is a quick way to generate major parts of an
application
```
