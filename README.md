# AI Flywheel Content Schemas

Shared JSON schemas for AI Flywheel content packages.

These schemas define the contract between AI content agents and publishing engines such as `json-to-typst-ebook`. They are designed for AI-generated ebooks, workbooks, slide decks, and visual content.

## Schemas

- `schemas/ebook-layout.v1.schema.json`: ebook and workbook content packages
- `schemas/slides-layout.v1.schema.json`: slide deck and poster-style visual content packages

## Examples

- `examples/ebook-minimal.json`
- `examples/slides-layout-as-code.json`
- `examples/poster-minimal.json`

## Install

Use directly from GitHub:

```sh
npm install github:mongmx/ai-flywheel-content-schemas
```

## Package Exports

```js
import ebookSchema from '@mongmx/ai-flywheel-content-schemas/ebook-layout.v1' assert { type: 'json' };
import slidesSchema from '@mongmx/ai-flywheel-content-schemas/slides-layout.v1' assert { type: 'json' };
```

For file-based validators, resolve these paths from the installed package:

```text
node_modules/@mongmx/ai-flywheel-content-schemas/schemas/ebook-layout.v1.schema.json
node_modules/@mongmx/ai-flywheel-content-schemas/schemas/slides-layout.v1.schema.json
```
