```markdown
# Nexter-CSS

## Overview

**Nexter-CSS** is a responsive landing page project developed as part of the "Advanced CSS and Sass" course by Jonas Schmedtmann. The project focuses on mastering the CSS Grid layout method and incorporates modern CSS techniques to create a visually appealing and user-friendly interface.

## Features

- **CSS Grid Layout**: Utilizes CSS Grid for efficient and responsive design.
- **SVG Icons**: Implements scalable vector graphics for crisp and scalable icons.
- **BEM Methodology**: Follows Block Element Modifier conventions for organized and maintainable code.
- **Responsive Design**: Ensures optimal viewing experiences across various devices and screen sizes.

## Technologies Used

- **HTML5**
- **CSS3**
- **Sass (SCSS)**

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/melvinprince/Nexter-CSS.git
   cd Nexter-CSS
   ```

2. **Install Dependencies**:

   Ensure you have [Node.js](https://nodejs.org/) and npm installed. Then, run:

   ```bash
   npm install
   ```

3. **Compile Sass**:

   For development with live reloading, run:

   ```bash
   npm run watch:sass
   ```

   For a production build with optimized CSS, run:

   ```bash
   npm run build:css
   ```

4. **View the Project**:

   Open `index.html` in your browser to see the landing page in action. Using a live server is recommended for the best development experience.

## Project Structure

The project is organized as follows:

- `index.html`: The main HTML file.
- `sass/`: Contains all Sass files, organized using the 7-1 architecture.
- `css/`: Compiled CSS files.
- `img/`: Images and SVG icons used in the project.
- `package.json`: Contains project metadata and npm scripts.

## Scripts

The project utilizes npm scripts for various tasks:

- **Watch Sass**: Compiles Sass files in development mode with live watching.

  ```bash
  npm run watch:sass
  ```

- **Build CSS**: Compiles, prefixes, and compresses CSS for production.

  ```bash
  npm run build:css
  ```

- **Start Development Server**: Runs a live server for development.

  ```bash
  npm start
  ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is part of the "Advanced CSS and Sass" course by Jonas Schmedtmann. Special thanks to Jonas for the comprehensive course and guidance.

## Contact

For any inquiries or support, please contact:

- **GitHub**: [melvinprince](https://github.com/melvinprince)
```
