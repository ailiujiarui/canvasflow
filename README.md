# CanvasFlow

CanvasFlow is a focused workflow editor built with React, TypeScript, Vite and React Flow. It demonstrates editor-level interactions and explicit graph validation without allowing arbitrary code execution.

## Included

- Infinite canvas pan, zoom, minimap and fit view
- Start, HTTP request, condition, transform, delay and output node palette
- Node creation, selection, connection, deletion and configuration editing
- Undo/redo for graph edits, save and run-test states
- Validation for start node, configuration and unreachable nodes
- Inline validation panel with node selection and simulated run status

## Run

```bash
npm install
npm run dev
npm run build
```

The current demo is intentionally client-only. Run-test uses controlled simulated statuses; it does not execute arbitrary JavaScript or issue unrestricted network requests.

## Performance notes

React Flow owns viewport and connection mechanics. Node state is kept in local editor state and validation is deferred to explicit validation/run actions. Measure a 500-node fixture with React Profiler before publishing performance claims.
