# Simple Astro Blog Project

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

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   ├── images/
│   └── favicon.svg
│   └── heartbeat.png
├── src/
│   ├── components/
│   │   └── Card.astro
│   │   └── H1.astro
│   │   └── Header.astro
│   │   └── Main.astro
│   │   └── Post.astro
│   │   └── PostList.astro
│   ├── content/
│   │   ├── posts/
│   │   └── config.ts
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│   │   ├── blog/
│   │   │   └── [slug].astro
│   │   └── about.astro
│   │   └── blog.astro
│   │   └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
