# frank-app


**What it is:**

The product code. UI, routing, local storage behavior, scoring logic, and how the app loads content. 

**What’s real vs planned:**

Real: 
initial JSON placeholders and draft structure.

Planned: 
populate JSON with final content, add one-click demo path.

**Not included on purpose:**

App code, any backend or UI implementation, any real user data.

## Purpose

This repo stores FRANK APP content as data so it stays editable and auditable without changing app code.

## Status

Scaffolding + contracts in place. This repo defines the expected data contracts and review flow for Frank app content. A working reference implementation (with validator and preview) lives in the `frank-content` repo.


## How to review in 3 min

1. Open the `frank-content` repo.
2. Review `content/frank_sample_content.json` to see example app input.
3. Run the demo script to generate a rendered preview:
   ./demo.sh
4. Open `preview.md` to see the output a user would experience.


