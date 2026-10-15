# Personal Portfolio

A responsive personal portfolio website for **Mian Muhammad Fahad**. The page introduces his background, education, current skills, and selected projects, with a contact section for visitors.

## Features

- Single-page layout with navigation links to each section.
- Introduction and profile photo.
- About section with career goals.
- Skills list covering HTML, CSS, JavaScript, and Git/GitHub.
- Project summaries for the NHA Website, Dentist Website, and AI Quiz Builder.
- Education table for the BS Computer Science degree and NHA internship.
- Contact form layout and a footer email link.
- Responsive styling for desktop, tablet, and mobile screens.
- Google Fonts typography with a local sans-serif fallback.

## Built With

- HTML5
- CSS3
- Google Fonts (Inter)

This is a static website. It does not require a package manager, build step, JavaScript framework, or database.

## Project Structure

```text
personal-potfolio-/
├── index.html
├── style.css
├── README.md
└── images/
    └── profile.jpeg
```

## Run Locally

1. Clone or download this repository.
2. From the project directory, start a local web server:

   ```bash
   python3 -m http.server 8000
   ```

3. Open [http://localhost:8000](http://localhost:8000) in a browser.

You can also open `index.html` directly, though using a local server is more reliable for loading assets.

## Customize

- Update the text, section content, navigation, and contact details in `index.html`.
- Replace the profile image in `images/` and update the image `src` in `index.html` to match its path.
- Change colors, spacing, typography, and responsive breakpoints in `style.css`. The main theme colors are defined near the top of the file as CSS custom properties.
- Update the footer copyright year when needed.

## Contact Form Note

The contact form currently points to `submit.php`, but no PHP handler or server-side processing is included in this repository. The form will not send or store submissions until a backend endpoint is added and configured. The footer email link is a separate way to contact the portfolio owner.