# Elm basics workshop

This repo contains Elm code for a simple ToDo app, created for an Elm workshop!
To start the workshop, checkout to the `ws-start` tag, and then create a new
branch:

```bash
git checkout ws-start

git checkout -b <name for your branch>
```

Install required dependencies:

```bash
yarn install
```

Use **Elm** `reactor` to start the app:

```bash
yarn elm reactor --port=<port number>
```

By default `elm reactor` uses port `8000`, so you can ignore the port flag if 
this port is available on your machine.


## What to do?

The workshop consists of 6 exercises:

1. Add missing function signatures
2. Define model and types required for the todo app
3. Add an html input element, which should be used to set new `todo` item text
4. Implement item `add` functionality, and render a list of todo items
5. Implement item `remove` functionality
6. **Bonus exercise**: add some styling


Each exercise step is tagged, you can use git to checkout to any one of them,
and review the code if necessary. To view the tags:

```bash
git tag -l
```

Tho, try to solve the exercise step before you decide it's time to take a peek
at a solution.
