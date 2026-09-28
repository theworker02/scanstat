# Acquisition notes — scanstat

## Product

`scanstat` is a focused `validate` toolkit: Scan validation gates for stat inputs before they hit prod.

## Assets

- Source: `src/index.js`, `src/cli.js`
- Docs site: `docs/` (GitHub Pages)
- Tests: `src/index.test.js` (node:test)

## Integration

Zero runtime dependencies. Suitable as a CLI in CI or a small library import in Node 18+.

## License

MIT
