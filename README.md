# my-node-app

![CI](https://github.com/TEgor1212/my-node-app/actions/workflows/ci.yml/badge.svg)

Node.js app with CI — `npm test` on push and PR.

A Node.js/Express application with a CI pipeline that runs linting and tests across Node.js 18, 20, and 22. A Docker image is built on successful pushes to main.

## Quick Start

```bash
npm ci
npm run lint
npm test
```