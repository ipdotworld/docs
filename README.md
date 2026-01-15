# ip.world docs

This folder contains the `ip.world` documentation site (Mintlify).

## Local development

Install the Mintlify CLI:

```bash
npm i -g mint
```

From this directory (where `docs.json` lives), run:

```bash
mint dev
```

Then open `http://localhost:3000`.

## Notes

- The sidebar/navigation is configured in `docs.json`.
- Pages are written in MDX and referenced by their path (without `.mdx`) in `docs.json`.
