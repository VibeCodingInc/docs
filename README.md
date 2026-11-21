# /vibe documentation

Public source for [docs.slashvibe.dev](https://docs.slashvibe.dev).

The docs have one job: help someone install `/vibe`, understand its honest boundaries, and
send a real message from a coding session. Product facts must match released behavior; do
not add a promise because an experiment or private substrate exists.

## Preview

```sh
npx mint dev
```

Mintlify serves the preview at `http://localhost:3000` by default.

## Contribution rules

- Prefer one clear instruction over a menu of equivalent paths.
- `/vibe` runs in Claude Code. Do not present another host as supported, and do not call an
  old native app the terminal product.
- Do not copy the tool or command list here. It lives in the package README and llms.txt in
  `VibeCodingInc/vibe-mcp`, beside the code; link to them.
- Never claim that presentation proves delivery or human read state.
- Never claim that work context, code, prompts, or transcripts travel with a message.
- Do not document backend HTTP routes as a public API without a reviewed public contract.
- Delete stale pages and redirect their URLs. Hiding a page from navigation still leaves a
  second definition for search and assistants to find.

## Publishing

The Mintlify GitHub integration deploys the default branch. A merged documentation change
is therefore a public product change; preview it and obtain review before merge.

Slash Vibe, Inc. · made in Tucson
