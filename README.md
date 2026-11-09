# ↔️ Palindrome Checker

### Node.js Server-Side JavaScript Project

## About the Project

This is a simple palindrome checker I built to practice using Node.js and working with server-side JavaScript.

A palindrome is a word or sequence that reads the same forward and backward, like "racecar" or "level."

The goal of this assignment was to build an application where someone could enter a word and have the server determine whether it's a palindrome.

## Features

- Enter a word or text into an input field.
- Send the input to a Node.js server.
- Check whether the input is a palindrome.
- Display the result on the page.
- Compare uppercase and lowercase letters without treating them as different.

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Node.js
- Node.js `http` and `fs` modules
- Fetch API

## How It Works

1. The user enters a word and clicks Submit.
2. JavaScript sends the input to the `/api` endpoint using `fetch()`.
3. The Node.js server receives the input through a query parameter.
4. A `for` loop builds a reversed version of the input.
5. The server compares the original and reversed strings in lowercase.
6. The server returns a result, which JavaScript displays on the page.

## Getting Started

1. Clone the repository:

   `git clone https://github.com/KevSal227/node-palindrome-kevin.git`

2. Navigate into the project:

   `cd node-palindrome-kevin`

3. Start the server:

   `node server.js`

4. Open `http://localhost:8000` in your browser.

This project uses Node.js built-in modules and does not require an `npm install` step.

## What I Learned

This assignment helped me understand the difference between client-side and server-side JavaScript.

Some of the concepts I practiced include:

- Creating a server using Node.js.
- Using the `http` module to handle requests.
- Using the `fs` module to serve HTML, CSS, and JavaScript files.
- Working with URL query parameters.
- Using a `for` loop to reverse a string.
- Comparing strings using `.toLowerCase()`.
- Sending data between the browser and server using the Fetch API.

One of the biggest things I learned was how to write the palindrome-checking logic myself instead of relying on a built-in reverse method.

## Current Limitations

- Spaces and punctuation are not removed before comparison.
- The input is not URL-encoded before being sent to the server.
- Error handling and input validation could be improved.
- The API response is JSON text but is served with an HTML content type.

## Future Improvements

I'd like to add better input validation, support for full phrases, and clearer feedback when users enter invalid input.

## Author

**Kevin Salazar**

[GitHub](https://github.com/KevSal227)
