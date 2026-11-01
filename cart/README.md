# Cart

Cart is a Webpack Module Federation remote in this e-commerce demo. It exposes `./CartShow` for the [container](../container/README.md) host and displays a randomly generated cart item count using Faker.

## Run locally

From this directory, install dependencies and start the development server:

```bash
npm install
npm start
```

The remote runs at [http://localhost:8082](http://localhost:8082), and its federation entry is `http://localhost:8082/remoteEntry.js`. You can view the standalone demo there. To see it composed with the products remote, start all projects as described in the [root README](../README.md) and open [http://localhost:8080](http://localhost:8080).

## Learning scope

This app demonstrates exposing a frontend module through Webpack Module Federation. The cart count is generated locally and is not persistent; there is no backend, checkout, or order processing.
