# J Furniture

A website for J Furniture, a business that provides specialty furniture services.

Built with [Astro](https://astro.build/) for fast performance and SEO optimization.

## Tech Stack

- [Astro](https://astro.build/) (Static site generator)
- [Tailwind CSS](https://tailwindcss.com/) (Styling)
- Currently deployed with [GitHub Pages](https://pages.github.com/)

## Features

- SEO-friendly one-page design
- Easy anchor link navigation
- Responsive layout with Tailwind CSS
- Sections:
  - Landing
  - Services
  - Gallery
  - About
  - Contact

## Assets & Media

All images, logos, and videos used in this project are provided by J Furniture. They are intellectual property of the business and are protected by copyright law. These assets are **not licensed for reuse, redistribution, republication, or commercial use**.

If you fork or clone this project, please replace them with your own media.

## Astro Starter Kit: Minimal

### Getting Started

```sh
npm create astro@latest -- --template minimal
```

Or follow [this guide](https://docs.astro.build/en/getting-started/) provided by Astro.

### 🚀 Project Structure

Inside of this Astro project, you'll see the following folders and files:

```text
/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── .vscode/
│   └── extensions.json
│   └── launch.json
├── public/
│   └── images/
│   └── videos/
│   └── favicon.svg
│   └── logo.jpg
│   └── square-logo.jpg
├── src/
│   └── components/
│       └── About.astro
│       └── Contact.astro
│       └── Gallery.astro
│       └── Landing.astro
│       └── NavBar.astro
│       └── Services.astro
│   └── pages/
│       └── index.astro
│   └── styles/
│       └── global.css
└── .gitignore
└── astro.config.mjs
└── package-lock.json
└── package.json
└── README.md
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

### 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

### 👀 Want to learn more about Astro?

Feel free to check their [documentation](https://docs.astro.build) or jump into their [Discord server](https://astro.build/chat).
