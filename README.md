# My Blog

Hugo static site.

## Requirements

- Hugo Extended `0.161.1`
- The active Hugo binary must include `extended` in `hugo version` because the site compiles Sass.

The expected Hugo version is recorded in `.hugo-version`.

## Local Development

```bash
hugo version
npm run dev
```

Equivalent direct command:

```bash
hugo server
```

## Production Build

```bash
npm run build
```

Equivalent direct command:

```bash
hugo --gc --minify
```

Generated Hugo output is intentionally ignored:

- `public/`
- `resources/_gen/`
- `.hugo_build.lock`
