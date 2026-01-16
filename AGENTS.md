# hardssh.github.io

Static SvelteKit site for HardSSH project documentation.

## Build System

- **Package Manager**: pnpm
- **Framework**: SvelteKit 2.x with Svelte 5.x
- **Adapter**: @sveltejs/adapter-static (outputs to `docs/`)
- **Styling**: TailwindCSS 3.x

## Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server |
| `pnpm build` | Build for production |
| `pnpm preview` | Preview production build |
| `pnpm check` | Run svelte-check for type/lint errors |
| `pnpm lint` | Run prettier and eslint |
| `pnpm format` | Format code with prettier |

## Project Structure

```
src/
  routes/           # SvelteKit pages
    +layout.svelte  # Root layout
    +page.svelte    # Homepage
static/             # Static assets
docs/               # Production output (GitHub Pages)
```

## Deployment

GitHub Pages serves from `docs/` directory. Push to main branch to deploy.
