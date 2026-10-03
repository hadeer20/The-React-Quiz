# The React Quiz

A React quiz application built while learning and practicing modern React concepts.

## Features

* Fetches quiz questions from a REST API
* Multiple-choice questions
* Tracks the selected answer
* Calculates the score based on correct answers
* Different points for different questions
* Progress tracking
* Countdown timer
* Automatically finishes the quiz when the time runs out
* Next question navigation
* Final score screen
* High score tracking
* Restart quiz functionality
* Uses `useReducer` to manage application state
* Uses `useEffect` for fetching data
* Responsive user interface

## Technologies

* React
* JavaScript
* CSS
* REST API
* `useReducer`
* `useEffect`

## Getting Started

Clone the repository and install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The app will run at:

```text
http://localhost:3000
```

## API

During development, the quiz questions are provided by a local JSON Server running on:

```text
http://localhost:9000/questions
```

Make sure the JSON Server is running before starting the application.

## Project Purpose

This project was built as part of my React learning journey to practice:

* `useReducer`
* State management
* `useEffect`
* Fetching API data
* Component composition
* Props and event handling
* Conditional rendering
* Timers and state updates
* Derived state
