# Hip Hip Array

**Hip Hip Array is a web application designed to help beginner programmers find appropriate array methods. Simply input in the array you've got, along with the output you want, and the tool will generate all the methods to get you there. Available for 3 programming languages - Javascript, Ruby and Python.**

## Contributors

- Layth Al-Qattan - https://github.com/laythq
- Bibi Collins - https://github.com/bibicollins
- Elishka Flint - https://github.com/elishkaflint
- John Forster - https://github.com/JohnForster

## Demo

[to be added]

## Quickstart

### Launching the application

**EITHER** install the code:

1. Clone the directory
```
$ git clone https://github.com/elishkaflint/hip_hip_array.git
$ cd hip_hip_array
$ npm install (requires node to be installed)
```
2. Start the back end server
```
$ npm start (web app will open in the browser at localhost:3000)
```
3. Start the front end server
```
In a new terminal window:
$ cd client
$ npm start (web app will open in the browser at localhost:3000)
```

**OR** view the [app deployed on Heroku](https://hip-hip-array.herokuapp.com/)

### Running the tests

Back end and front end tests:
```
npm test
```
Current test coverage: **80%** [to be updated]

## Team Objectives

We defined our objectives as a group at the start of our project, as follows:

- Our project has a compelling technical aspect
- That said, we do not sacrifice developer processes for technical achievement
- We consolidate gaps in our learning from the course (we highlighted JSON API calls, client-side programming eg. React)
- We prefer a simple and finished output to a complex and messy/unfinished output
- We are all able to explain every aspect of the final product

## Process Highlights

- We took an Agile approach to structuring our work (daily stand ups, 2 day sprints each followed by a team retrospective).
- We took on a new project after 2 days, because we didn't feel comfortable with our initial idea (you can read more about that [here](https://hackmd.io/hdESol_BTpmGwfJR8lY9Gw)).
- We used Trello to organise tickets.
- We used TDD to drive creation of each individual model. We wrote retrospective tests for some of the React elements because it was our first time programming with this library.

## Implemented User Stories
```
As a user
So that I can use the right array method
I want to be able to input a simple initial array and a simple target array and be
given the method which gets me from one to the other
```
```
As a user
So that I can use the tool for more complex methods
I want to be able to use arrays which take arguments
```
```
As a user
So that I can use the tool for more complex methods
I want to be able to input multi-dimensional arrays
```
```
As a user
So that I can learn about lots of different languages
I want to be able to use the tool for Ruby, Javascript and Python
```
```
As a user
So that I can revisit my searches
I want my queries to be logged in a search history
```
```
As a user
So that I can use the tool easily
I want to access the programme via a clean user interface
```
## What we would do next

- Improve the Python model which currently returns only very basic array methods
- Conduct thorough user-testing to find and cover edge cases
- Increase our test coverage by writing additional tests, particularly on the client-side
- Create user accounts so history can be retained between browser sessions
- Extend our product further (additional languages, Atom plug in etc)
