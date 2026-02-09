<p align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="logo/suga-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="logo/suga-light.svg">
      <img width="120" alt="Shows a black logo in light color mode and a white one in dark color mode." src="docs/logo/suga-light.svg">
    </picture>
</p>

<h1 align="center">Suga Documentation</h1>

<p align="center">
  Documentation for <a href="https://suga.app">Suga</a> — infrastructure deployment with version control, audit trails, and instant rollbacks.
</p>

<p align="center">
  <a href="https://docs.suga.app">View Docs</a> · <a href="https://dashboard.suga.app">Dashboard</a> · <a href="https://suga.app/chat">Discord</a>
</p>

---

## Docs Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

Run the local dev server:

```bash
mintlify dev
```

Preview at `http://localhost:3000`.

## Publishing

Changes pushed to the default branch are automatically deployed via the Mintlify GitHub app.
