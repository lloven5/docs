# Snakemake Wrappers Documentation

This directory contains the documentation for the Snakemake Wrappers project, built with [Mintlify](https://mintlify.com).

## Overview

The Snakemake Wrappers repository provides reusable wrappers for popular bioinformatics tools that can be used in Snakemake workflows. This documentation helps users understand how to use existing wrappers and create new ones.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally:

```bash
npm i -g mint
```

Run the following command at the root of the `docs` directory:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Documentation Structure

- **index.mdx** - Main landing page
- **quickstart.mdx** - Quick start guide for using wrappers
- **usage.mdx** - Comprehensive guide on using wrappers
- **wrappers.mdx** - Overview of available wrappers
- **creating-wrappers.mdx** - Guide to creating new wrappers
- **contributing.mdx** - Contributing guidelines
- **development.mdx** - Development setup guide

## Publishing Changes

Changes to the documentation are automatically deployed when pushed to the repository. If using Mintlify's hosting, install the GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to enable automatic deployments.

## Need Help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`

### Resources

- [Snakemake Documentation](https://snakemake.readthedocs.io)
- [Mintlify Documentation](https://mintlify.com/docs)
- [GitHub Repository](https://github.com/snakemake/snakemake-wrappers)
