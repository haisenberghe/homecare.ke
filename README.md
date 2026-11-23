# HomeCare Kenya prototype

A responsive, clickable care-team prototype using fictional data. This is a product demonstration only; it is not a production clinical system and must not be used to make care decisions or store real patient information.

## Preview

Requires Node.js 18 or newer. From this folder run:

```bash
npm start
```

Or run `node server.js` if npm is not available.

Then open [http://127.0.0.1:4173](http://127.0.0.1:4173). No dependencies or account setup are required. You can also open `index.html` directly in a browser.

## Try the demo

- Search the assigned caseload by patient name or HomeCare ID and open a dossier.
- Turn dossier modules on or off, then open their sample sections.
- Add a visit report. It is submitted once to the supervisor; a family update is prepared only after review and only for a patient marked as authorised.
- Switch to the supervisor demo role to approve a report or return it to draft.
- Simulate offline mode to see queued sync status. Prototype state is stored in this browser's local storage; use **Reset demo data** in the sidebar to restore the original sample state.

Everything is simulated in the browser. Role switching and authorisation labels demonstrate the intended experience and are not security controls.
## Hosted demo

The live prototype is published at https://haisenberghe.github.io/homecare.ke/.

