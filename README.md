# Typing Text Effect using Typed.js

This project demonstrates a dynamic typing text effect using the [Typed.js](https://github.com/mattboldt/typed.js) library. It's a simple and customizable way to create animated typing effects for your website.

[Demo](https://teneplays.github.io/Typing-Text-Effect-using-Typed.js)

## How I Made This

### 1. Setup

I started by setting up a basic HTML structure for the project, where I wanted to display a dynamic text that changes over time. The idea was to animate words like "Game Developer," "Web Developer," and "Content Creator."

### 2. Adding Typed.js

I integrated the [Typed.js CDN](https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js) directly into the HTML. This library handles the typing animation effect by automatically cycling through predefined strings, typing them out, backspacing, and then typing the next string.

### 3. JavaScript Configuration

Next, I wrote a simple JavaScript snippet to configure Typed.js. The key parameters I customized include:

- **strings**: I defined an array of roles (`["Game Developer", "Web Developer", "Content Creator"]`) that I wanted to display in rotation.
- **typeSpeed** and **backSpeed**: These control how fast the text is typed and erased. I set both speeds to `150` milliseconds for a balanced typing and deleting effect.
- **loop**: I set this to `true` so that the text continuously loops without stopping.

This made it easy to add multiple roles that get displayed dynamically in sequence.

### 4. Styling

To ensure the effect looks good on the page, I added basic CSS for centering the text and applying a simple design. This enhanced the visual appeal and kept the focus on the typing effect.

## Key Features

- **Dynamic Typing**: The project animates typing text effects for multiple strings.
- **Customizable Speeds**: You can easily adjust the typing and backspacing speeds.
- **Looping**: The text loops indefinitely, making it suitable for a personal website or portfolio.

## Setup and Usage

1. **Include the Typed.js CDN**: Add the Typed.js library to your HTML via a CDN.
2. **Configure the Effect**: Customize the strings and speeds in your JavaScript file.
3. **Style the Text**: Use CSS to match the design to your website.

## Conclusion

This project is a simple demonstration of how Typed.js can create a professional-looking typing effect with minimal setup. It’s a great tool for adding interactive and eye-catching text animations to any website.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


*Stay connected! Follow me on [Socials](https://linktr.ee/tenegames).*
