# CSE 134B – HW4: Astro Blog & Multi-Page Website

https://kate-astro.netlify.app/

## 🚀 Project Structure

Here is the structure of the project as it exists now:

```text
src/
├── assets/
│ └── (images or future assets)
│
├── components/
│ ├── Footer.astro
│ ├── Header.astro
│ ├── Menu.astro
│ ├── Navigation.astro
│ ├── Social.astro
│ └── Welcome.astro
│
├── layouts/
│ ├── BaseLayout.astro
│ ├── Layout.astro
│ └── MarkdownPostLayout.astro
│
├── pages/
│ ├── about.astro
│ ├── blog.astro
│ ├── index.astro
│ └── posts/
│ ├── post-1.md
│ ├── post-2.md
│ └── post-3.md
│
├── scripts/
│ └── menu.js
│
└── styles/
└── global.css
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

