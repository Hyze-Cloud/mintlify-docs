# Hyze Cloud Docs

Documentation for the Hyze Cloud API, built with [Mintlify](https://mintlify.com).

## Local development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the docs from this folder:

```bash
mint dev
```

The preview runs at `http://localhost:3000`.

## Structure

- `docs.json` controls navigation, branding, and global links.
- `index.mdx` is the landing page.
- `quickstart.mdx` is the first-run guide.
- `guides/` contains task-based guides.
- `api-reference/` contains endpoint reference pages.

## Writing style

- Use "workspace", "app", "database", and "API key".
- Keep headings in sentence case.
- Prefer short, direct instructions and working `curl` examples.
- Use Mintlify components like `<Card>`, `<Steps>`, `<Tip>`, and `<Callout>`.

## Publishing

Mintlify deploys from the connected repository after changes are pushed to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
