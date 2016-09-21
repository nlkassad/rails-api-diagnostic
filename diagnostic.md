# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
// the purpose of the backend is to have a usable interface for interacting
with data that provides permanence
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
// The Model fetches and places data
```

Which layer in the MVC pattern communicates with the model?

```bash
// the controller communicates with the model and provides instructions from
other elements.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// we don\'t use views because our intent is for this istance to handle
data and we\'re handling views in out apps
```

What does C.R.U.D stand for?

```bash
// Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
// We find them in the model
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
// GET, POST, PATCH, DELETE, INSERT, SELECT
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
•Request is sent to server
•Server sends request to controller
•Controller looks at request and sends it to model that handles GET item
requests
•Model checks request and sends response to controller
•Controller takes response and send it to the Server
•Serve presents response as a string to controller
•User is happy

```

What is the command to generate a new rails-api app?

```bash
rails new my_api --api
```

What is the command to start an instance of a rails server?

```bash
// your response here
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
bundle exec rails serve
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bundle exec rails-api g scaffold pet name:string age:integer
```
