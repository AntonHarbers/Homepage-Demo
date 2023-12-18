# The Odin Project - Homepage

A Portfolio page created using HTML, CSS and Javascript for the Odin Project.

[Live Link](https://antonharbers.github.io/Odin-Portfolio/)

![Screenshot of Webpage](/src/Images/repoImage.png)

## Folder Structure

```
    /.git               ->  This git repository
    /node_modules       ->  Node Dependencies
    /src
        /Images             ->  Contains all images used (Favicon, repo image, app images, logo etc.)
        /styles             ->  Contains all the stylesheets.
        script.js           ->  Prevent Default Submit behaviour script
    .eslintrc.js        ->  Eslint Config File
    .gitignore          ->  Gitignore for this repo
    index.html          ->  Entry Point and contains all HTML
    package-lock.json   ->  Package-lock for Node
    package.json        ->  Package.json for Node
    README.md           ->  This readme File
```

## Key Concepts

### Linting

ESLint is a static code analysis tool for identifying problematic patterns in JavaScript code. It helps maintain code quality and consistency, especially in projects with multiple contributors.

Code Example:

JS:

```
    // ESLint configuration example
    module.exports = {
        "env": {
            "browser": true,
            "es2021": true,
            "node": true
        },
        "extends": "eslint:recommended",
        "parserOptions": {
            "ecmaVersion": 12,
            "sourceType": "module"
        },
        "rules": {
            "indent": ["error", 2],
            "linebreak-style": ["error", "unix"],
            "quotes": ["error", "double"],
            "semi": ["error", "always"]
        }
    };
```

This is a basic ESLint configuration file. It defines the environment, extends the recommended ESLint rules, sets ECMAScript version, and includes custom rules for indentation, linebreaks, quotes, and semicolons.

### NPM

NPM (Node Package Manager) is the default package manager for JavaScript's runtime environment Node.js. It's used to manage project dependencies and run scripts.

Code Example:

JSON:

```
// Example of a package.json file
    {
    "name": "your-project-name",
    "version": "1.0.0",
    "description": "Your project description",
    "main": "index.js",
    "scripts": {
        "start": "node app.js",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "author": "Your Name",
    "license": "ISC",
    "dependencies": {
        "express": "^4.17.1"
    }
    }
```

This package.json file is a standard for any Node.js project. It includes metadata like name, version, description, main entry point, scripts (like start and test), author, license, and project dependencies (like Express).

### Devicon Icons

Devicon is an icon library featuring programming languages, design and development tools. It's a great visual aid for tech stacks in your portfolio or documentation.

Code Example:

HTML:

```
    <!-- Example of using Devicon icons in HTML -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/devicon/devicon.min.css">
    <i class="devicon-javascript-plain"></i>
    <i class="devicon-react-original"></i>
```

This HTML snippet demonstrates how to include the Devicon library via CDN and use specific icons (JavaScript and React in this case) in your webpage.

### Responsive Styling

Responsive layout in CSS ensures that your webpage looks good on all devices. It uses media queries and flexible grid layouts to adapt the design to various screen sizes.

Code Example:

CSS:

```
    /* Example of a basic responsive layout */
    .container {
        display: flex;
        flex-wrap: wrap;
    }

    @media screen and (max-width: 600px) {
        .container {
            flex-direction: column;
        }
    }
```

The .container class uses a flex display to align items. The media query adjusts the layout for screens smaller than 600px by changing the flex direction to column, making it responsive.

## Final Notes

Jumping into this portfolio project was a cool ride into the world of web development. Getting my hands dirty with ESLint was eye-opening – it’s like having a neat-freak for your code, keeping everything tidy. NPM was the trusty sidekick, handling all those packages and scripts like a boss.

Adding flair with Devicon icons was a slick touch, giving the tech side of things a visual punch. The real game-changer, though? Mastering Responsive Layout with CSS. It’s all about making your site look good on any device – essential stuff in our screen-filled world.

All in all, this project was a solid mix of learning and fun. It’s not just about coding; it’s about creating something that clicks.
