# Products

Products is a Webpack Module Federation remote in this e-commerce demo. It exposes `./ProductIndex` for the [container](../container/README.md) host. The module renders five product names generated locally with Faker.

## Run locally

From this directory, install dependencies and start the development server:

```bash
npm install
npm start
```

The remote runs at [http://localhost:8081](http://localhost:8081), and its federation entry is `http://localhost:8081/remoteEntry.js`. You can view the standalone demo there. To see it composed with the cart remote, start all projects as described in the [root README](../README.md) and open [http://localhost:8080](http://localhost:8080).

## Learning scope

This app demonstrates exposing a frontend module through Webpack Module Federation. Product names are generated locally; there is no backend or real product catalog.
