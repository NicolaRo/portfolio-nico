# NicolaRo.github.io

This is my personal website showcasing my profile as a Full-Stack Developer.

## Description

This website serves as a portfolio to display my skills, experiences, and projects. It includes:

- An introduction about myself.
- A link to my CV.
- A contact form for visitors to reach out.
- Links to my social media profiles.

## Technologies Used

- HTML
- CSS
- JavaScript
- SCSS
- Swiper.js (for the slider in some projects)
- EmailJS (for handling the contact form)

## File Structure

The project structure is organized as follows:

- `index.html`: Main landing page.
- `CV.html`: My curriculum vitae.
- `Contact-Me.html`: Contact form.
- `Depyl_Project.html`: Project showcase.
- `Green-Earth_Project.html`: Project showcase.
- `css/`: Contains compiled CSS files.
  - `style.css`: Main stylesheet.
- `img/`: Contains images used throughout the site.
  - `contact-form-logo.png`
  - `Depyl_Logo.png`
  - `Dev-logo.png`
  - `...`
- `js/`: Contains JavaScript files.
  - `slider.js`: Slider functionality.
- `scss/`: Contains SCSS source files.
  - `_variables.scss`: SCSS variables.
  - `style.scss`: Main SCSS file.
  - `pages/`: SCSS files for specific pages.
    - `CV-Style.scss`
    - `Contact-Me-Style.scss`
    - `Index-Style.scss`
    - `Green-Earth_project.scss`
    - `Depyl-Project.scss`

## Setup

To run this project locally:

1.  Clone the repository:

    ```bash
    git clone https://github.com/NicolaRo/NicolaRo.github.io.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd NicolaRo.github.io
    ```

3.  Open `index.html` in your browser.

## SCSS Compilation

The project uses SCSS for styling. To compile SCSS files to CSS, you can use the following command:

```bash
sass --watch scss/style.scss:css/style.css
```
