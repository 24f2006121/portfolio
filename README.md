# Om Kumar’s Portfolio

I’m a student developer who builds desktop apps, reusable web interfaces, and command-line tools. My academic background is in Data Science & Applications at IIT Madras and Computer Applications at C. M. Science College, Darbhanga.

[GitHub](https://github.com/24f2006121) · [LinkedIn](https://www.linkedin.com/in/om-kumar-92a586322/)

## Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| [Tabria React](https://github.com/24f2006121/tabria-react) | Reusable browser-style tab manager with tab search, page history, and the ability to reopen closed tabs. | React, TypeScript, Vite |
| [Zensys](https://github.com/24f2006121/zensys) | Local-first desktop app that ranks notes by importance and stores them on the device. | React, Tauri, Rust |
| [Build Your Own CLI](https://github.com/24f2006121/Build-your-own-cli) | Interactive CLI with an Ask Mode for codebase questions and an Agent Mode that proposes edits for review. | TypeScript, Bun, Commander |

## Run locally

Open [`public/index.html`](public/index.html) directly in a browser. The portfolio uses HTML and CSS and requires no dependency installation or build step.

To preview the site over HTTP, run this command from the repository root with Python 3 installed.

```sh
python -m http.server 8000 --bind 127.0.0.1 --directory public
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser. Press `Ctrl+C` to stop the server.

## Edit the site

- Update the bio, education, project descriptions, and contact links in [`public/index.html`](public/index.html).
- Adjust the responsive layout, colors, and typography in [`public/styles.css`](public/styles.css).
- Find the hero image and favicon in [`public/assets/`](public/assets/).

## Deploy to Vercel

[`vercel.json`](vercel.json) configures Vercel to serve `public/` as a static site. The project requires no build command or environment variables. [Vercel project configuration](https://vercel.com/docs/project-configuration/vercel-json)

### From GitHub

1. Push the site files to GitHub, with `public/` and `vercel.json` at the repository root.
2. Import the repository in Vercel. If prompted, select **Other** as the framework preset and keep the repository root as the **Root Directory**. [Vercel New Project](https://vercel.com/new)
3. Select **Deploy**. Future pushes to the configured production branch trigger new production deployments. [Vercel’s GitHub integration](https://vercel.com/docs/git/vercel-for-github)

### From the command line

With Node.js and npm installed, run these commands from the repository root.

```sh
npx vercel login
npx vercel deploy --prod
```

On the first run, follow the prompts to link the repository to a Vercel project. Once the initial deployment is live, use `npx vercel deploy` to create a preview and `npx vercel deploy --prod` to publish updates. [Vercel CLI documentation](https://vercel.com/docs/cli/deploy)
