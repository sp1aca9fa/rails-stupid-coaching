# Rails Stupid Coaching

A minimal Ruby on Rails application where users can ask a question and receive a response from a "coach" based on simple logic.

## Features

- Submit a question through a form
- Receive a dynamic answer based on input
- Navigate between pages using standard Rails routing

## Tech Stack

- Ruby on Rails
- ERB (Embedded Ruby)
- Bootstrap (for basic styling)

## How It Works

The app follows the MVC pattern:

- **Route**: Handles `/ask` and `/answer` requests
- **Controller**: Processes user input and generates responses
- **View**: Displays the form, question, and answer

### Coach Logic

- "I am going to work" → "Great!"
- Questions ending with "?" → "Silly question, get dressed and go to work!"
- Anything else → "I don't care, get dressed and go to work!"

## Setup

git clone <your-repo-url>
cd rails-stupid-coaching
bundle install
rails db:create
rails server

Then open:
http://localhost:3000/ask

## Learnings

- Understanding Rails MVC structure
- Handling HTTP requests and params
- Building forms and routing user flows
- Connecting controller logic to views

## Notes

This project was built as part of a bootcamp exercise to practice core Rails fundamentals.
