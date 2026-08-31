---
title: Search
description: Full-text search with tag filtering and keyboard navigation.
tags:
  - plugin/component
image: https://images.unsplash.com/photo-1516382799247-87df95d790b7
repository: "[quartz-community/search](https://github.com/quartz-community/search)"
enabled: true
required: false
---

Full-text search functionality.

> [!note]
> For information on how to add, remove or configure plugins, see the [[configuration#Plugins|Configuration]] page.

See [[full-text search]] for detailed usage information.

## Configuration

This plugin accepts the following configuration options:

- `enabled`: Whether to enable full-text search. Defaults to `true`.

### Default options

```yaml title="quartz.config.yaml"
- source: github:quartz-community/search
  enabled: true
```

## API

- Category: Component
- Function name: `ExternalPlugin.Search()`.
- Source: [`quartz-community/search`](https://github.com/quartz-community/search)
- Install: `npx quartz plugin add github:quartz-community/search`
