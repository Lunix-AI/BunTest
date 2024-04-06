# buntest

Test with bun:

```bash
bun install
```

To run:

```bash
bun dev
```

Now change a/src/index.ts, see watch working well.
Now change b/src/index.ts, see watch not working well.

To contrast with, run vite node:

```bash
bun dev:vite-node
```

Now change a/src/index.ts, see watch working well.
Now change b/src/index.ts, see watch working well also.

This is the expected behaviour.

