# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The purpose of a backend is to process server requests made by the client.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The model
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md

```

What does C.R.U.D stand for?

```md
CREATE, READ, UPDATE, DELETE.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
MODEL
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
INDEX, CREATE, SHOW, DESTROY, UPDATE
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md

```

What is the command to generate a new rails-api app?

```bash
bin/rails generate
```

What is the command to start an instance of a rails server?

```bash
CREATE
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
rake db:migrate

rake db:seed

rake db:drop

rake db:create
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold name: string age: integer
```
