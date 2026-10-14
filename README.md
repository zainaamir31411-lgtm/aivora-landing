# Aivora Labs

Company site for Aivora Labs, an AI lab. Products sit under the lab, and each one keeps its own theme. [Animaay](https://animaay.com) is one of them.

The only public contact is [info@aivoralabs.si](mailto:info@aivoralabs.si).

```bash
npm install
npm run dev
```

The dev server runs at http://localhost:4321. `npm run build` writes a static site to `dist/`.

Railway builds the `Dockerfile` and serves `dist/` with Caddy on `$PORT`. Point the service at this repo; no start command is required.
