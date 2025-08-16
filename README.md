Portfolio Website
A modern, responsive portfolio website for showcasing web development projects and skills. Built using SCSS and vanilla JavaScript, the site features multiple pages (Home, About, Work, Contact) with a dark-themed UI and dynamic layouts.

Features
Responsive design using SCSS media queries.

Multi-page site: Home, About, Work (Projects), and Contact.

Custom SCSS styling: Modular, dark-themed, and easily customizable.

Grid and Flexbox layouts.

SCSS-powered animations and transitions.

Easy setup and modification for your own needs.

Getting Started
Prerequisites
Node.js and npm

Installation
bash
git clone https://github.com/asherrv10/portfolio_website.git
cd portfolio_website
npm install
npm run sass
Then open dist/index.html in your browser.

Project Structure
text
portfolio_website/
├── dist/
│   ├── css/
│   ├── img/
│   ├── js/
│   ├── index.html
│   ├── about.html
│   ├── work.html
│   └── contact.html
├── scss/
│   ├── _config.scss
│   ├── _menu.scss
│   ├── _mobile.scss
│   └── main.scss
├── package.json
└── .gitignore
Customization
Edit theme colors and layout in scss/_config.scss.

Add your projects in work.html and update images accordingly.

Author
Asher Roni Verghese
Student, Web Developer & Programmer

Acknowledgements
This project was built by following @bradtraversy's YouTube tutorial. All credit for the original design and structure goes to him. I built this project alongside the tutorial for learning purposes.
