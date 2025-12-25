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

Scaffolding + contracts in place.  
This repo defines the expected data contracts and review flow for Frank app content. A working reference implementation (with validator and preview) lives in the `frank-content` repo.


## How to review in 3 min

1. Open `content/frank_sample_content.json` to see the example input.  
2. Run the validator and preview:  
   ```bash
   node scripts/validate_and_preview.js

