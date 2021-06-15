# A Studious Palm Tree

To get started:

1. Clone the repo
2. use `yarn` to install dependencies
3. Run with 
```
node node_modules/\@jacobmischka/ical-merger/dist/server.js
```

Enjoy the service!

### A sample call

```
GET /combine.ics?url=https://www.officeholidays.com/ics-local-name/france&url=https://www.officeholidays.com/ics-local-name/germany/bavaria
```

This should respond with an ICS file.

### Using `curl`
Using curl (e.g., within a repl.it repl) this could be tested as follows:

```
curl -o merge.ics "http://localhost:3000/combine.ics?url=https://www.officeholidays.com/ics-local-name/france&url=https://www.officeholidays.com/ics-local-name/germany/bavaria"
```
