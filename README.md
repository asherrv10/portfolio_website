# Portfolio Website

A **modern, responsive portfolio website** for showcasing web development projects and skills. Built using SCSS and vanilla JavaScript, the site features multiple pages (Home, About, Work, Contact) with a dark-themed UI and dynamic layouts.

## Features

- **Responsive design** using SCSS media queries
- **Multi-page site:** Home, About, Work (Projects), and Contact
- **Custom SCSS styling:** Modular and easily customizable
- **Grid and Flexbox layouts**
- **SCSS-powered animations and transitions**
- **Easy setup and modification**

## Getting Started

### Prerequisites

- Node.js and npm

### Installation

```bash
git clone https://github.com/asherrv10/portfolio_website.git
cd portfolio_website
npm install
npm run sass
```
Then open `dist/index.html` in your browser.

## Project Structure

```
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
```

## Customization

- Edit theme colors and layout in `scss/_config.scss`
- Add your projects in `work.html` and update images accordingly

## Deployment

You can deploy this website on **GitHub Pages**, **Vercel**, or **Netlify**.

### Deploying to GitHub Pages

1. Commit and push all changes to your `main` branch.
2. In your repository settings, go to the **Pages** section.
3. Set the deploy branch to `main` and folder to `/dist` (or root if moving build to root).
4. Save—your site will be available at `https://.github.io/portfolio_website/`

### Deploying to Vercel or Netlify

- Import your GitHub repo to Vercel/Netlify.
- Set build output directory to `dist`.
- Follow their deployment instructions.

## Contributing

Contributions are **welcome**!  
If you have ideas for improvement or want to fix issues:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`
3. Make your changes and commit: `git commit -m 'Add some feature'`
4. Push to your branch: `git push origin feature/YourFeature`
5. Open a Pull Request describing your changes.

Please follow the code style and add clear, descriptive commit messages.

## Author

**Asher Roni Verghese**  
Student, Web Developer & Programmer

## Acknowledgements

- This project was built by following  [@bradtraversy 's YouTube tutorial](https://www.youtube.com/@TraversyMedia). All credit for the original design and structure goes to him. I built this project alongside the tutorial for learning purposes.

***
