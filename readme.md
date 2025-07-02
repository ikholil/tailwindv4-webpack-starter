# HTML Tailwind Webpack Starter

This is a starter template for building modern websites using HTML, Tailwind CSS v4, and Webpack. It includes a development server with hot reloading and a build process for production.

## Features

*   **HTML5:** Ready-to-use HTML5 boilerplate.
*   **Tailwind CSS v4:** The latest version of the utility-first CSS framework.
*   **Webpack:** Module bundler for JavaScript, CSS, and other assets.
*   **SCSS:** SCSS support for advanced styling.
*   **SwiperJS:** A modern touch slider which is lightweight and easy to use.
*   **UI Range Slider:** A simple and customizable range slider.
*   **Live Reloading:** The development server automatically reloads when you make changes.
*   **File Watching:** The `watch-new-files.js` script automatically restarts the development server when you add or remove files.
*   **Partials:** Support for HTML partials to keep your code organized.

## Getting Started

### Prerequisites

*   Node.js and npm (or yarn) installed on your machine.

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/your-username/tailwindv4-webpack-starter.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd tailwindv4-webpack-starter
    ```

3.  Install the dependencies:

    ```bash
    npm install
    ```

### Development

To start the development server with hot reloading, run the following command:

```bash
npm run dev
```

This will start a development server at `http://localhost:5000`. The server will automatically reload when you make changes to the files in the `src` directory.

### Building for Production

To build the project for production, run the following command:

```bash
npm run build
```

This will create a `dist` directory with the optimized and minified files.

## Project Structure

```
.
├───.gitignore
├───package-lock.json
├───package.json
├───postcss.config.mjs
├───readme.md
├───watch-new-files.js
├───webpack.config.js
├───.git/...
├───dist/...
├───node_modules/...
└───src/
    ├───404.html
    ├───index.html
    ├───index.js
    ├───input.css
    ├───assets/
    │   └───images/
    │       ├───404.png
    │       ├───hero.png
    │       ├───home1-banner.webp
    │       └───logo.png
    └───partials/
        ├───footer.html
        ├───header.html
        └───loader.html
```

*   **`src`:** This directory contains the source code for your website.
    *   **`assets`:** This directory contains the assets for your website, such as images, fonts, and icons.
    *   **`partials`:** This directory contains the HTML partials for your website, such as the header, footer, and loader.
    *   **`index.html`:** The main HTML file for your website.
    *   **`index.js`:** The main JavaScript file for your website.
    *   **`input.css`:** The main CSS file for your website.
*   **`dist`:** This directory contains the built files for your website.
*   **`node_modules`:** This directory contains the dependencies for your project.
*   **`.gitignore`:** This file contains the files and directories that should be ignored by Git.
*   **`package.json`:** This file contains the metadata for your project, such as the name, version, and dependencies.
*   **`postcss.config.mjs`:** This file contains the configuration for PostCSS.
*   **`readme.md`:** This file contains the documentation for your project.
*   **`watch-new-files.js`:** This file contains the script that watches for new files and restarts the development server.
*   **`webpack.config.js`:** This file contains the configuration for Webpack.

## Customization

### Tailwind CSS

You can customize the Tailwind CSS configuration in the `tailwind.config.js` file.

### Webpack

You can customize the Webpack configuration in the `webpack.config.js` file.

### Partials

You can add new partials to the `src/partials` directory. To include a partial in an HTML file, use the following syntax:

```html
<include-partial-name />
```

For example, to include the `header.html` partial, you would use the following code:

```html
<include-header />
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.