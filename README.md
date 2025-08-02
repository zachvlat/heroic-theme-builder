# Heroic Theme Builder

A simple web app to create custom themes with color accents for the Heroic Games Launcher.  
Build your own color scheme and font selection, then preview the theme live and copy the generated CSS to use in your launcher or other projects.

---

## Features

- Interactive live preview of your theme with a navbar, buttons, and text
- Customize key colors: accent, background, surface, text, and danger
- Choose from multiple Google Fonts
- Define a custom CSS theme class name
- Responsive 2-column layout for controls and preview
- Copy generated CSS with one click

---

## Usage

1. Open `index.html` in any modern web browser.
2. Adjust the color pickers to select your preferred colors.
3. Choose your favorite font from the dropdown.
4. Enter a custom theme class name.
5. See the preview update live.
6. Copy the generated CSS from the textarea and use it in your Heroic Games Launcher theme or your own project.

---

## Fonts

This app supports:

- [Fira Sans](https://fonts.google.com/specimen/Fira+Sans)
- Roboto
- Inter
- Ubuntu
- Poppins
- Lato
- Montserrat
- Open Sans
- Raleway
- Source Sans Pro
- Merriweather
  
---

## How it works

The app dynamically updates CSS variables based on user input, applies those variables in a preview container, and generates a CSS theme snippet ready to be copy-pasted.

Google Fonts are loaded dynamically except for Adwaita, which is assumed to be installed on the local system.

---

## Contributing

Feel free to fork the repo, improve the UI, add more features or fonts, and send a pull request!

---

## License

This project is licensed under the GNU General Public License v3.0 (GPLv3). See the [LICENSE](LICENSE) file for details.

---

## Screenshot

![Heroic Theme Builder Screenshot](https://i.imgur.com/wA55tak.png)

---

## Acknowledgements

Inspired by the Heroic Games Launcher styling and Material Design principles.
