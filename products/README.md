# Products

This is the products remote in a small Webpack Module Federation learning demo. It exposes `./ProductIndex` for the [container](../container) host and renders five randomly generated product names using Faker.

## Run locally

Install dependencies and start the development server:

```bash
npm install
npm start
```

The remote is served at [http://localhost:8081](http://localhost:8081), with its federation entry at `http://localhost:8081/remoteEntry.js`. To see it loaded by the host, also start the container and open [http://localhost:8080](http://localhost:8080).

## Learning notes

This is a minimal demo for learning how to expose a frontend module through Webpack Module Federation. Product names are generated locally; there is no backend, real catalog, or ecommerce functionality.
