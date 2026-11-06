# Brunch — Indian Restaurant Website

A static, single-page restaurant website concept for an Indian cuisine restaurant. The page brings together restaurant storytelling, featured dishes, a menu-style presentation, editorial content, and a reservation form interface.

> **Project type:** Front-end website template  
> **Status:** Static front-end implementation

## Preview

**Live Demo:** [https://a-kandeel.github.io/brunch-restaurant-landing-page/]

- **Repository:** https://github.com/A-Kandeel/Brunch-Website

## Features

- Restaurant landing section with introductory call to action.
- About section highlighting the restaurant concept.
- Featured dishes and menu-style food listings with prices.
- Restaurant story and editorial/gallery-style content.
- Reservation form UI with date, time, party size, and customer contact fields.
- Contact and footer navigation.
- Locally stored image assets, icons, and stylesheets.
- Google Fonts integration using Cookie and Raleway.

## Built With

- HTML5
- CSS3
- Font Awesome
- Google Fonts

The project uses custom stylesheets and local CSS utility/framework files. It does not require a JavaScript build tool or package manager.

## Project Structure

```text
Brunch-Website/
├── index.html
├── css/
│   ├── Brunch.css
│   ├── Brunch-Framework.css
│   ├── MyFramework.css
│   ├── normalize.css
│   └── all.min.css
├── Imgs/
└── webfonts/
```

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/A-Kandeel/Brunch-Website.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

You can also use a local development server, such as the Live Server extension in Visual Studio Code, to serve the page locally.

## Implementation Notes

- This repository contains a static front-end website; no server-side application or database is included.
- The reservation form is currently a visual front-end form. The HTML does not define a submission endpoint, so reservations are **not** sent to a booking system.
- Some page copy is placeholder text and should be replaced with real restaurant information before production use.
- Google Fonts are loaded from Google Fonts, so those typefaces require an internet connection.

## Possible Next Improvements

- Connect the reservation form to a booking service or backend.
- Add client-side form validation and clear submission feedback.
- Replace placeholder copy and sample menu data with final restaurant content.

## License

No license file is currently included in this repository. All rights remain with the project owner unless a license is added.
