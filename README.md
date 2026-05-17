# scholia-ai

AI-generated structured notes based on my interests.

Built with [mdBook](https://rust-lang.github.io/mdBook/) and
[`mdbook-katex`](https://github.com/lzanini/mdbook-katex) for KaTeX math.

## Local development

Install the toolchain (one time):

```bash
cargo install mdbook mdbook-katex
# or grab the prebuilt binaries from the GitHub releases of each project.
```

Serve locally with live reload:

```bash
mdbook serve --open
```

Build the static site into `./book/`:

```bash
mdbook build
```

## Adding a note

1. Create a Markdown file under `src/`, e.g. `src/notes/my-topic.md`.
2. Link it from `src/SUMMARY.md`:

   ```markdown
   - [My Topic](./notes/my-topic.md)
   ```

3. Use `$...$` for inline math and `$$...$$` for display math.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the
book and publishes `./book/` to GitHub Pages. Enable Pages once in the repo
settings: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
