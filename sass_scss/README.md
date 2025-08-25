# Sass/Scss Project

## Description

This project contains a series of Sass/Scss exercises that cover fundamental concepts including debugging, variables, nesting, mixins, inheritance, imports, and loops. Each exercise focuses on specific Sass features and techniques.

## Requirements

### General
- **Allowed editors**: `vi`, `vim`, `emacs`
- **Environment**: Ubuntu 20.04 LTS using Sass 1.82.0 (or higher)
- All files must end with a new line
- All Scss files must have a comment at the beginning
- All files must start with a comment describing the task
- A `README.md` file at the root of the project folder is mandatory
- File length will be tested using `wc`

### Scss File Format
All Scss files must start with a comment block:

```scss
/* My style */
body {
    .container {
        color: #3D3D3D;
    }
}
```

## Installation

Install Sass/Scss on Ubuntu 20.04 LTS:

```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo npm install -g npm@10
sudo npm install -g sass@^1.82.0
sass --version
```

Expected output:
```
1.82.0 compiled with dart2js 3.5.4
```

## Tasks Overview

### 0. Always debugging!
Write a Sass file that prints "Hello world" in the debug output.

### 1. Color variable
Assign text color #3D3D3D to HTML tags body and p using a Sass variable.

### 2. Colors
Use 2 Sass variables to assign text color #3D3D3D to body and p tags, and background color #6D6D6D to body and h2 tags.

### 3. Nested tag
Use nested declarations to set no margin/padding for body tags and 10px margin for p tags inside body.

### 4. Nested class
Use nested declarations to set text color #3D3D3D for body elements and #FF0000 for .red class elements inside body.

### 5. Nested child
Use nested declarations with direct child selector for .red class elements that are first children of body.

### 6. Nested hover
Use nested declarations to set button text color to #FF0000 and #00FF00 on hover.

### 7. Nested and nested again
Use multiple levels of nesting for font sizes: body (14px), body h1 (16px), body h1.smaller (12px).

### 8. Margin mixin
Create a mixin for left and right margins: 10px for body tags, 15px for div tags.

### 9. Extended
Use @extend to share font-size 12px from .info class to .success (green) and .warning (red) classes.

### 10. Import colors
Use @import to import color variables and apply them to .red, .green, and .blue classes.

### 11. For each
Use @each statement to create photo classes based on a list of names with background images.

### 12. Loop Headers
Use @for statement to create h1-h5 tags with font sizes from 1px to 5px respectively.

## Usage

Compile any Scss file:
```bash
sass filename.scss
```

View debug output:
```bash
sass filename.scss | head -n 0
```

View compiled CSS (skip debug lines):
```bash
sass filename.scss | tail -n +2
```

## Repository

- **GitHub repository**: holbertonschool-web_front_end
- **Directory**: sass_scss


## Author

- Stan QUEUNIEZ