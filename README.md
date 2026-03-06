# React Flux Isomorphic Photo App

A full-stack isomorphic web application built with React, Fluxible, and Express that displays photos from the 500px API. It demonstrates server-side rendering, Flux architecture, internationalization, and modern JavaScript tooling with Webpack and Babel.

## Overview

This project is a universal JavaScript photo application inspired by the original `isomorphic500` example. It renders React on both the server and the client, uses Fluxible for application architecture and routing, and serves content through an Express server.

The app showcases:

- React-based UI rendering
- Flux architecture with Fluxible
- Express-powered server-side rendering
- Webpack and Babel development/build tooling
- Internationalization with `react-intl`
- Hot reloading during development

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/gpbl/isomorphic500.git
cd isomorphic500
npm install
```

## Running the Development Server

Start the app in development mode:

```bash
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

## Production Build

Build the production bundle:

```bash
npm run build
```

Run the production server locally:

```bash
npm run prod
```

Then open [http://localhost:8080](http://localhost:8080).

## Project Structure

```text
.
├── index.js              # Starts the Express server
├── config/               # Environment-specific configuration
├── src/
│   ├── app.js            # Fluxible application setup
│   ├── client.js         # Client entry point
│   ├── server.js         # Server bootstrap and rendering
│   ├── routes.js         # Application routes
│   ├── actions/          # Fluxible actions
│   ├── components/       # Presentational React components
│   ├── containers/       # Container components
│   ├── intl/             # Localization messages
│   ├── server/           # Server-only helpers and middleware
│   ├── services/         # Fetchr / API services
│   ├── stores/           # Fluxible stores
│   ├── style/            # Sass styles
│   └── utils/            # Shared utilities
├── static/               # Static assets and generated bundles
└── webpack/              # Webpack configuration
```

## Technologies Used

- React
- Fluxible
- Express.js
- Webpack
- Babel
- React Hot Loader
- ESLint
- React Intl
- Sass
- Superagent

## Notes

- Development server: `npm run dev`
- Production build: `npm run build`
- Production server: `npm run prod`