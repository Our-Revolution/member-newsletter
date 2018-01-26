# member-newsletter
Our Revolution's Monthly Member Newsletters

This repository consists of all Our Revolution Member Newsletters in both `.html`and `.mjml` format. MJML is a responsive email framework that makes coding HTML emails easy.

## Prerequisites
1. [Node.js & npm](https://nodejs.org/en/)
2. [MJML](https://mjml.io/)

## Installation
1. Clone this repisotory
2. Install MJML using npm
```
npm init -y && npm install mjml
```
3. Add MJML to your path
```
export PATH='$PATH:./node_modules/.bin'
```

## Building Newsletters
1. Copy the `base.mjml` template for a new newsletter.
2. Make content changes as needed to your new MJML file.
3. (Optional) To have MJML watch and automatically compile to HTML, run:
```
mjml -w <filename>.mjml
```
