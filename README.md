# Dante - Astro & Tailwind CSS Theme by justgoodui.com

Dante is a single-author blog and portfolio theme for Astro.js. Featuring a minimal, slick, responsive and content-focused design. For more Astro.js themes please check [justgoodui.com](https://justgoodui.com/).

![Dante Astro.js Theme](public/dante-preview.jpg)

[![Deploy to Netlify Button](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/JustGoodUI/dante-astro-theme)

If you click this☝️ button, it will create a new repo for you that looks exactly like this one, and sets that repo up immediately for deployment on Netlify.

## Theme Features:

- ✅ Dark and light color mode
- ✅ Hero section with bio
- ✅ Portfolio collection
- ✅ Pagination support
- ✅ Post tags support
- ✅ Subscription form
- ✅ View transitions
- ✅ Tailwind CSS
- ✅ Mobile-first responsive layout
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## Template Integrations

- @astrojs/tailwind - https://docs.astro.build/en/guides/integrations-guide/tailwind/
- @astrojs/sitemap - https://docs.astro.build/en/guides/integrations-guide/sitemap/
- @astrojs/mdx - https://docs.astro.build/en/guides/markdown-content/
- @astrojs/rss - https://docs.astro.build/en/guides/rss/

## Project Structure

Inside of Dante Astro theme, you'll see the following folders and files:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── data/
│   ├── icons/
│   ├── layouts/
│   ├── pages/
│   ├── styles/
│   └── utils/
├── astro.config.mjs
├── package.json
├── README.md
├── tailwind.config.cjs
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro (`.astro`) components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## Astro.js Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Want to learn more about Astro.js?

Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Credits

- Demo content generate with [Chat GPT](https://chat.openai.com/)
- Images for demo content from [Unsplash](https://unsplash.com/)

## Astro Themes by Just Good UI

- [Ovidius](https://github.com/JustGoodUI/ovidius-astro-theme) is a free single author blog theme.

## License

Licensed under the [GPL-3.0](https://github.com/JustGoodUI/dante-astro-theme/blob/main/LICENSE) license.

```
2025_portfolio
├─ .gitignore
├─ .prettierrc
├─ .vscode
│  ├─ extensions.json
│  ├─ launch.json
│  └─ settings.json
├─ LICENSE
├─ README.md
├─ admin
│  ├─ config.yml
│  └─ index.html
├─ astro.config.mjs
├─ package-lock.json
├─ package.json
├─ public
│  ├─ about.jpeg
│  ├─ dante-preview.jpg
│  ├─ favicon.svg
│  ├─ hero.jpeg
│  ├─ post-1.jpg
│  ├─ post-10.jpg
│  ├─ post-11.jpg
│  ├─ post-12.jpg
│  ├─ post-13.jpg
│  ├─ post-14.jpg
│  ├─ post-2.jpg
│  ├─ post-3.jpg
│  ├─ post-4.jpg
│  ├─ post-5.jpg
│  ├─ post-6.jpg
│  ├─ post-7.jpg
│  ├─ post-8.jpg
│  ├─ post-9.jpg
│  ├─ project-1.jpg
│  ├─ project-2.jpg
│  ├─ project-3.jpg
│  ├─ project-4.jpg
│  ├─ project-5.jpg
│  ├─ project-6.jpg
│  └─ project-7.jpg
├─ src
│  ├─ components
│  │  ├─ BaseHead.astro
│  │  ├─ Button.astro
│  │  ├─ Footer.astro
│  │  ├─ FormattedDate.astro
│  │  ├─ Header.astro
│  │  ├─ Hero.astro
│  │  ├─ IconButton.astro
│  │  ├─ Nav.astro
│  │  ├─ NavLink.astro
│  │  ├─ Pagination.astro
│  │  ├─ PostPreview.astro
│  │  ├─ ProjectPreview.astro
│  │  ├─ Subscribe.astro
│  │  └─ ThemeToggle.astro
│  ├─ content
│  │  ├─ blog
│  │  │  ├─ post-1.md
│  │  │  ├─ post-10.md
│  │  │  ├─ post-11.md
│  │  │  ├─ post-12.md
│  │  │  ├─ post-13.md
│  │  │  ├─ post-14.md
│  │  │  ├─ post-2.md
│  │  │  ├─ post-3.md
│  │  │  ├─ post-4.md
│  │  │  ├─ post-5.md
│  │  │  ├─ post-6.md
│  │  │  ├─ post-7.md
│  │  │  ├─ post-8.md
│  │  │  └─ post-9.md
│  │  ├─ pages
│  │  │  ├─ about.md
│  │  │  ├─ contact.md
│  │  │  └─ terms.md
│  │  └─ projects
│  │     ├─ project-1.md
│  │     ├─ project-2.md
│  │     ├─ project-3.md
│  │     ├─ project-4.md
│  │     ├─ project-5.md
│  │     ├─ project-6.md
│  │     └─ project-7.md
│  ├─ content.config.ts
│  ├─ data
│  │  └─ site-config.ts
│  ├─ icons
│  │  ├─ ArrowLeft.astro
│  │  └─ ArrowRight.astro
│  ├─ layouts
│  │  └─ BaseLayout.astro
│  ├─ pages
│  │  ├─ [...id].astro
│  │  ├─ blog
│  │  │  ├─ [...page].astro
│  │  │  └─ [id].astro
│  │  ├─ index.astro
│  │  ├─ projects
│  │  │  ├─ [...page].astro
│  │  │  └─ [id].astro
│  │  ├─ rss.xml.js
│  │  └─ tags
│  │     ├─ [id]
│  │     │  └─ [...page].astro
│  │     └─ index.astro
│  ├─ styles
│  │  └─ global.css
│  └─ utils
│     ├─ common-utils.ts
│     └─ data-utils.ts
├─ tailwind.config.cjs
└─ tsconfig.json

```
