# hello-world-test01
## Summary
This is a simple static web application that displays a greeting message. The application includes a button that, when clicked, changes the greeting text from "Hello World" to "Goodbye World".

## Setup
To set up this project, follow these steps:
* Clone the repository using `git clone https://github.com/your-username/hello-world-test01.git`
* Open the `index.html` file in a web browser to view the application

## Usage
To use this application, simply click on the button with the id "btn" to change the greeting text.

## Code Explanation
The code for this project consists of a single HTML file (`index.html`) that includes a button element with an onclick event handler. The event handler is defined in a JavaScript function that updates the text of the greeting element.
```html
<button id="btn" onclick="changeGreeting()">Click me</button>
```
```javascript
function changeGreeting() {
  document.getElementById("greeting").innerHTML = "Goodbye World";
}
```
The greeting text is initially set to "Hello World" in the HTML file.
```html
<p id="greeting">Hello World</p>
```

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.