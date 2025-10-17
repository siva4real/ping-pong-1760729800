# Ping Pong Game with Image Metadata

## Summary
This web application demonstrates a simple ping pong game implemented using HTML5 Canvas. Additionally, it can display an image and its metadata when an image URL is passed as a query parameter. The application is built using pure HTML, CSS, and JavaScript, making it lightweight and easy to deploy.

## Setup
To run this application locally or on a server:
1. Ensure you have a modern web browser installed (Chrome, Firefox, Edge, etc.).
2. Clone the repository or download the `index.html` file.
3. Open the `index.html` file in your web browser.

## Usage
- To play the ping pong game, use the "Up" and "Down" arrow keys to move the paddle.
- To display an image and its metadata, append `?url=<image-url>` to the URL in the address bar. For example: `index.html?url=https://example.com/image.jpg`
- The image metadata (size and type) will be displayed 10 seconds after the image loads.

## Code Explanation
- The HTML structure includes a canvas for the game and a section for displaying the image and its metadata.
- The CSS provides a minimalistic style, focusing on a clean and modern UI.
- The JavaScript code handles the game logic (ball movement, collision detection, paddle control) and fetches the image from the URL parameter, displaying its metadata after 10 seconds.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software. See the LICENSE file for details.