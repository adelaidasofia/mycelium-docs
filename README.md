# Mycelium docs

Public docs site for Mycelium AI. Built on [Mintlify](https://mintlify.com).

## Local dev

```bash
npm install -g mintlify
cd mycelium-docs
mintlify dev
```

Opens at http://localhost:3000.

## Build

```bash
mintlify build
```

## Deployment

Production deploy is via the Mintlify GitHub action, which publishes to `docs.myceliumai.co` on every push to `main`. Configure the deploy in the Mintlify dashboard once the repo is pushed to GitHub.

## Structure

```
mycelium-docs/
  mint.json                 site config + nav
  getting-started/          install + quickstart
  architecture/             pillars, typed memory, resolver, lineage
  connectors/               substrate skills + webhook receivers + enterprise
  skills/                   shipped skills index
  reliability/              the manifesto, framed for security architects
  security/                 posture summary, links to /trust
  api-reference/            runtime endpoints
  sdk/                      Python / TypeScript / Java / Go
  self-host/                BYOC + airgapped
  vertical-packs/           legal / finance / healthcare / manufacturing / public sector
```

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md). Doc PRs welcome.

## License

MIT. See [LICENSE](./LICENSE).
