# Container

The container is the host application in this Webpack Module Federation demo. It loads and mounts the `ProductIndex` module from [products](../products) and the `CartShow` module from [cart](../cart).

## Run locally

Start the [products](../products/README.md) remote on port `8081` and the [cart](../cart/README.md) remote on port `8082`. Then, from this directory, install dependencies and start the host:

```bash
npm install
npm start
```

Open [http://localhost:8080](http://localhost:8080). The host expects the remotes at `http://localhost:8081/remoteEntry.js` and `http://localhost:8082/remoteEntry.js`.

For complete setup instructions and the project overview, see the [root README](../README.md).

## Learning scope

This app demonstrates composing independently served frontend modules in a host. The remote modules display locally generated demo data; the project does not include a backend or checkout flow.
