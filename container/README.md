# Container

This is the host application in a small Webpack Module Federation learning demo. It loads the `ProductIndex` module exposed by the [products](../products) remote.

## Run locally

Install dependencies and start each project in a separate terminal:

```bash
cd products
npm install
npm start
```

```bash
cd container
npm install
npm start
```

Open [http://localhost:8080](http://localhost:8080) after both development servers are running. The container expects the products remote at `http://localhost:8081/remoteEntry.js`.

## Learning notes

This is a minimal demo for learning how a host can load a separately served frontend module. It is not a production-ready ecommerce application: it has no backend, checkout, or real product data.
