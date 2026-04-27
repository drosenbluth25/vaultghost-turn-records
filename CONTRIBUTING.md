# Contributing

Thank you for your interest in this repository. The contribution process below is intentionally narrow because of the nature of the contents.

## Nature of This Repository

This repository publishes example turn records that follow the `VaultGhost.TurnRecord.v1` schema. The artifacts (`turn*.json`, `latest_turn_hash.txt`, `latest_turn_hash.txt.ots`) are reference material associated with a protocol filing. They contain placeholder digest material and simulated proof metadata, as documented in `README.md`.

**The artifact files are not modifiable through ordinary contributions.** Pull requests that change the JSON records, the hash text file, or the OpenTimestamps receipt will not be accepted, because altering them after publication would defeat their purpose as a fixed reference point.

## What Contributions Are Welcome

- Documentation clarifications in `README.md`, `SECURITY.md`, or this file, where the existing wording is inaccurate, unclear, or misleading.
- Corrections to broken links.
- Typographical or grammatical fixes that do not change technical meaning.

## What Contributions Are Out of Scope

- Edits to `turn1_perplexity.json`, `turn2_grok.json`, `turn3_grok_extension.json`.
- Edits to `latest_turn_hash.txt` or `latest_turn_hash.txt.ots`.
- Adding a `LICENSE` file. The license decision is pending and is reserved to the repository owner.
- Changes to repository settings, tags, releases, security settings, or visibility.
- Claims about the evidentiary status of any record, or any wording that asserts that placeholder/simulated material constitutes a real Bitcoin/OpenTimestamps proof of real evidence content. See the Evidence Boundary section below.

## How to Contribute

1. Fork the repository.
2. Create a topic branch off `master` (do not push directly to `master`).
3. Make a small, focused change limited to the documentation files listed above.
4. Open a pull request describing what changed and what was deliberately left unchanged.
5. The repository owner will review.

## Evidence Boundary

VaultGhost verifies records within a captured boundary. It can verify hashes, signatures, schemas, timestamps, declared metadata, and replayable artifacts. It does not claim visibility into hidden model weights, provider-side logs, undisclosed system prompts, or private infrastructure.

A valid signature is not trusted identity. Internal consistency is not provenance.

Documentation contributions must remain consistent with this boundary. Do not introduce wording that overstates what the repository’s artifacts establish.

## Code of Conduct

Be respectful and on‑topic. Off‑topic, abusive, or disruptive contributions will be closed without review.
