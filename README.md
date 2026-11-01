# E-commerce Microfrontend Demo

A learning project that combines three independently served frontend apps with Webpack Module Federation:

- [Container](./container/README.md) is the host, served on port `8080`.
- [Products](./products/README.md) exposes the `ProductIndex` remote, served on port `8081`.
- [Cart](./cart/README.md) exposes the `CartShow` remote, served on port `8082`.

The host loads both remotes and displays a generated list of product names and a generated cart item count.

## Run the complete app

Install dependencies and start each app in its own terminal, from the repository root:

```bash
cd products
npm install
npm start
```

```bash
cd cart
npm install
npm start
```

```bash
cd container
npm install
npm start
```

Once all three development servers are running, open [http://localhost:8080](http://localhost:8080).

## Learning scope

This project demonstrates a host loading separately served frontend modules. Product names and the cart count are generated locally with Faker; there is no backend, persistent cart, checkout, or real product catalog.
