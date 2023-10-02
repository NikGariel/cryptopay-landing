# CryptoPay Landing: Landing Contest for Web Developers
by [NikGariel](https://github.com/NikGariel/)

🚀 Welcome to the cryptopay-landing repository! This is the official repository for my entry in the Web Developers Challenge. In this contest, I'll be developing a one-page website layout in accordance with the provided design, using the performance-optimized Astro 3 framework. This repository will house all the project files, including the Astro 3 code, HTML, CSS, and JavaScript, as well as any other related assets.

<a href="https://cryptopay-landing.pages.dev/"><img src="https://raw.githubusercontent.com/NikGariel/cryptopay-landing/main/cloudflarePagesButton.svg" height="32"></a>

> **Are you a representative of CryptoPay?** Then read the [license agreement](https://github.com/NikGariel/cryptopay-landing/blob/main/LICENSE.md).

![just-the-cover](https://raw.githubusercontent.com/NikGariel/cryptopay-landing/main/cover.webp)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── assets/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

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
