# Netflix Clone

> A full-stack streaming-catalog interface with authenticated user access, movie and TV content routes, search history, watch pages, and TMDB service integration.

## Overview

This repository contains the source and supporting files for **Netflix Clone**. The documentation below was prepared from the current repository structure and implementation files so that setup expectations, project boundaries, and implemented capabilities are explicit.

## Technology

| Area | Implementation |
| --- | --- |
| Frontend | React and Vite client in frontend/ |
| Backend | Express 5 API in backend/ |
| Data | MongoDB with Mongoose |
| External content | TMDB service integration |
| Authentication | Token generation and protected routes |

## Key capabilities

| Area | Current implementation |
| --- | --- |
| Content discovery | Provides movie, TV, trending-content, search, and search-history experiences. |
| Viewing flow | Includes an authenticated watch page and loading skeleton. |
| Account access | Implements login, signup, tokens, and protected backend routes. |

## Getting started

Use the following workflow to work with the project locally.

```bash
git clone https://github.com/aihamjassar/netflix-clone.git
cd netflix-clone
npm install
npm install --prefix frontend
# Configure MongoDB, authentication, and TMDB environment values
npm run dev
# In another terminal: npm run dev --prefix frontend
```

## Project structure

| Path | Purpose |
| --- | --- |
| backend/controllers/ | Auth, movie, TV, and search logic |
| backend/services/tmdb.service.js | TMDB integration |
| backend/routes/ | Auth, movie, TV, and search API routes |
| frontend/src/pages/ | Home, search, history, watch, login, and signup views |
| frontend/src/store/ | Authenticated-user and content state |

## Configuration notes

Use a valid TMDB API configuration in a secured environment file and comply with TMDB’s applicable terms. This project is an educational clone and is not affiliated with Netflix.

## License

A license file is included in this repository. Review it before reusing, distributing, or modifying the project.

## Maintainer

Maintained by [Aiham Jassar](https://github.com/aihamjassar). Contributions, issue reports, and improvement suggestions are welcome through the repository.
