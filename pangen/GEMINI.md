# Project Overview

This project is a single-page web application with two main features: generating and validating Primary Account Numbers (PANs). It's an experimental and fun project built with plain HTML, CSS, and JavaScript. The application has a retro, synthwave-themed, terminal-like aesthetic, which is an intentional design choice, achieved with CSS and Google Fonts.

The user interface is split into two sections:
1.  **PAN Generator:** Allows the user to specify a Bank Identification Number (BIN) and a PAN length to generate a list of valid PANs.
2.  **PAN Validator:** Allows the user to input a complete PAN to check if its check digit is valid according to the Luhn algorithm.

## Building and Running

This is a simple HTML file. No build process is required. To run the application, open the `index.html` file in a web browser.

## Development Conventions

All the code (HTML, CSS, and JavaScript) is contained within the `index.html` file. There are no external libraries, except for Google Fonts. The JavaScript code is embedded in a `<script>` tag at the end of the `<body>`. Key functions include `generate()` for creating PANs and `checkPan()` for validating them.