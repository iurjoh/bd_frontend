# bd_frontend

[Português (Brasil)](README.pt-BR.md) | **English**

A React front-end study project, by name the front-end of the Baby Daily app.

**Source:** public repository. Documentation reviewed on 2026-10-01.

## Status

Study project from the Code Institute Full Stack course period (last commits in 2023). The previous README was the unchanged Code Institute Codeanywhere template text; it was replaced by this document on 2026-10-01. The project is not currently deployed at a known public URL.

## Purpose

The repository name and package name (`bd_frontend`) identify it as the front-end of [Baby Daily](https://github.com/iurjoh/Baby-Daily), a private platform for parents to share baby milestones with a trusted circle. Note that the Baby Daily repository also carries its own `frontend/` directory; whether this repo is an earlier standalone copy or the source that was later merged was not confirmed during this review and is not asserted as fact. The code is built on the course's "Moments" walkthrough stack (Create React App, React Bootstrap, Axios, JWT auth); the matching backend is a Django REST Framework API.

## Tech stack

From `package.json`:

- React 18 with `react-scripts` (Create React App) and React Router
- React Bootstrap and Bootstrap
- Axios for API calls, `jwt-decode` for token handling
- `react-infinite-scroll-component`
- Testing Library (jest-dom, react, user-event)

## Run locally

```bash
npm install
npm start
```

Opens on `http://localhost:3000`. A running backend API is needed for real data. Other scripts: `npm test`, `npm run build`. A `heroku-prebuild` script remains from the original Heroku deployment setup; no current deployment is verified.

## Development record

The exact feature set and original planning notes were not reconstructed during this documentation update, and no process history is invented here. The full product documentation lives in the [Baby Daily](https://github.com/iurjoh/Baby-Daily) repository. Git history is the source for implementation details.

## Testing

Testing Library dependencies are present, but the test suite was not run in this update. Before any reuse, run `npm install` and `npm test` and check the app against a live backend.

## Credits and license status

Bootstrapped with Create React App and based on the Code Institute "Moments" walkthrough template. No `LICENSE` file was found at the repository root during this review; third-party template code retains its original terms, and this update does not apply a new license to them.
