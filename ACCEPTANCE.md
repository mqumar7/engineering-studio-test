# Engineering Studio GitHub acceptance

This branch exercises Engineering Studio on official DeepSeek Harness 0.2.1-rc.5. Model replies and the reviewer verdict are emulated locally; file tools, isolated worktrees, Git commits, Node tests and Chrome interactions are real. It is an integration test, not a benchmark of a paid model.

Open `index.html` in a browser. Run the arithmetic tests with Node.js 22.19 or newer:

```bash
node --test calculator.test.mjs
```

The existing repository README is preserved. No dependencies, CI workflow, backend or production deployment are added.
