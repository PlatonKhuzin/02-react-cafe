# 02-react-cafe

React + TypeScript application for collecting café feedback. Built with Vite.

## Local development

```sh
npm ci
npm run dev
```

## Checks

```sh
npm run build
npm run format:check
```

## Deploy on Vercel

Import the GitHub repository into Vercel. Use the Vite preset, build command `npm run build`, output directory `dist`, and repository root as Root Directory. No environment variables are needed. Submit the stable production domain from Domains, together with the GitHub repository URL.

## Behavior

Votes are kept in App state. Totals and rounded positive percentage are computed from votes. Statistics and Reset appear after the first vote. Reset restores the initial screen. Reloading resets votes.

Component styles: https://github.com/goitacademy/react-cafe-styles
