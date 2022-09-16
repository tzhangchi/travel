# deckjs

Presentation like writing a doc, deckjs is written by react+ lit + yjs + vite + tailwind.css


## Development

Setting up basic local environment:

```bash
# install dependencies
pnpm i

# start vite playground
pnpm dev
```

To test locally, please make sure browser binaries are already installed via `npx playwright install` and Vite playground is started with `pnpm dev`. Then there are multi commands to choose from:

```bash
# run tests in headless mode in in another terminal window
pnpm test

# or run tests in headed mode for debugging
pnpm test:headed
```

In headed mode, `await page.pause()` can be used in test cases to suspend the test runner.

# Useful Links

We would also like to give thanks to open-source projects that make deckjs possible:

- [yjs
  ](https://github.com/yjs/yjs) & [Yrs](https://github.com/y-crdt/y-crdt) -- Fundamental support of CRDTs for our implementation on state management and data sync.
- [React](https://github.com/facebook/react) -- View layer support and web GUI framework.
- [Lit](https://lit.dev/) -- Simple. Fast. Web Components..
- [quilljs](https://quilljs.com/) - powerful rich text editor.
- [vite](https://vitejs.dev/) -- Next Generation Frontend Tooling.
- Other [dependencies](https://github.com/tzhangchi/deckjs/network/dependencies)

## License

[Apache 2.0](./LICENSE)
