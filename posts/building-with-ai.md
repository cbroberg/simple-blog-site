# Building Websites with AI

*Updated: 2026-03-28*
*Language: da*

How AI coding agents can use @webhouse/cms to scaffold complete websites.

# Building Websites with AI

AI coding agents like Claude Code can use **@webhouse/cms** to build complete, production-ready websites in minutes.

## The Protocol

1. Install the package: `npm install @webhouse/cms`
2. Read the manifest at `GET /api/manifest`
3. Generate a `cms.config.ts` tailored to the site's purpose
4. Create content via the REST API
5. Run `cms build` to generate the static site

## Why This Works

The CMS is designed to be introspectable. Every collection, field, and block type is described in a machine-readable manifest that AI agents can read and act upon.

This means less time writing boilerplate and more time building unique features.