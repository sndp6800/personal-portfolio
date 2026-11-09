# Personal Portfolio

A React portfolio website for presenting projects, skills and contact information. Built with React 18, React Bootstrap and Create React App tooling.

## Run and verify

```sh
npm ci
npm start
```

Open http://localhost:3000. Available scripts:

| Command | Purpose |
| --- | --- |
| `npm start` | Local development server |
| `npm test` | Existing React test runner |
| `npm run build` | Generate static files in `build/` |

## Source map

The main sections are in `src/components/`: `Banner`, `NavBar`, `Skills`, `Projects`, `ProjectCard`, `Contact` and `Footer`. Shared styles are in `src/App.css` and `src/index.css`; public assets and page metadata are in `public/`.

Update project descriptions and links alongside their source repositories. A visible contact form does not establish that email delivery is configured; verify its destination before launch.

## Status

This repository retains its original Create React App setup. Dependencies and browser behavior need review before a new deployment. The documentation cleanup inspected the package scripts and component structure; it did not rerun the full install, build or browser suite.
