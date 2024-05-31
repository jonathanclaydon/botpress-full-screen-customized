# Botpress Full-Screen Webchat Customization

This repository demonstrates how to take the Botpress full-screen webchat implementation to the next level by customizing the provided code. The repository contains four files:

- `default.html` - The standard code provided by Botpress for the traditional side bot.
- `fullscreen-original.html` - The code provided by Botpress for the full-screen bot, as described on their [embedding webchat options page](https://botpress.com/docs/developers/webchat/embedding-webchat-options/full-screen-bot/).
- `fullscreen-updated.html` - A customized version of `fullscreen-original.html` demonstrating how to modify the full-screen bot implementation.
- `example.css` - The CSS used to style the bot in `fullscreen-updated.html`.

## Files Overview

### `default.html`
This file contains the standard Botpress code for embedding a traditional side bot on a webpage. It serves as a reference for the default implementation.

### `fullscreen-original.html`
This file contains the original Botpress code for embedding a full-screen bot, as provided in the Botpress documentation. It is the starting point for customization.

### `fullscreen-updated.html`
This file demonstrates the customized implementation of the full-screen bot. The modifications in this file are aimed at enhancing the bot's appearance and functionality. Key changes include:
- Custom styling
- Adjustments to the bot's layout
- Improved user interface elements

**Note:** The `botId` used in this file (`"botId": "dec7ae95-d874-4f04-ac5c-03d5b5a425bf"`) is a placeholder and will not work. You need to replace it with your own `botId`, which can be found in the Botpress Webchat "configurable" section of your specific bot.

### `example.css`
This CSS file contains the styles used in `fullscreen-updated.html`. It includes custom styles to enhance the look and feel of the full-screen bot, making it more visually appealing and user-friendly.

## Usage

To use these files, follow these steps:

1. **Standard Side Bot:**
   - Open `default.html` in your browser to see the traditional side bot implementation provided by Botpress.

2. **Original Full-Screen Bot:**
   - Open `fullscreen-original.html` in your browser to see the original full-screen bot as described in the Botpress documentation.

3. **Customized Full-Screen Bot:**
   - Open `fullscreen-updated.html` in your browser to see the customized full-screen bot.
   - Ensure `example.css` is in the same directory as `fullscreen-updated.html` to apply the custom styles.
   - Replace the placeholder `botId` in `fullscreen-updated.html` with your own `botId`.

## Customization Guide

The process of customizing the full-screen bot was not intuitive and required several adjustments to the original code. Here are some key points to consider when customizing your Botpress webchat:

1. **Modify the HTML Structure:**
   - Adjust the HTML elements to fit your desired layout and functionality.

2. **Update CSS Styles:**
   - Use `example.css` as a reference for custom styles. You can modify the CSS to match your branding and design preferences.

3. **Test and Iterate:**
   - Test the changes in various browsers and devices to ensure a consistent user experience.
   - Iterate on the design and functionality based on user feedback.

## YouTube Video

For a detailed walkthrough of this project, watch the accompanying YouTube video: [Insert YouTube Video Link Here]

## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is available for use under the terms of the Unlicense. This means anyone can use, modify, and distribute the code as they see fit, without any restrictions. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Botpress](https://botpress.com) for providing the webchat framework and documentation.

## About SageRock

This project is brought to you by [SageRock](https://sagerock.com), a company dedicated to **Humanizing Technology for Mission-Driven Organizations Since 1999**. We specialize in creating technology solutions that empower organizations to achieve their goals and make a positive impact.

---

By customizing the full-screen bot, we aim to create a more engaging and user-friendly chat experience. We hope this repository helps you in your Botpress webchat customization journey!
