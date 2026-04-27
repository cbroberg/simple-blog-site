# Hello, World!

*Updated: 2026-03-28*
*Language: da*

# Hello, World!

Welcome to this blog, powered by **@webhouse/cms** — an AI-native CMS engine.

## Features

- Schema-driven content modeling
- Static site generation
- REST API for content management
- AI-friendly manifest endpoint

## Getting Started

Define your collections in `cms.config.ts`, add content, and run `cms build`.

```typescript
import { defineConfig, defineCollection } from '@webhouse/cms';

export default defineConfig({
  collections: [
    defineCollection({
      name: 'posts',
      fields: [
        { name: 'title', type: 'text', required: true },
        { name: 'content', type: 'richtext' },
      ],
    }),
  ],
});
```

Happy building!