# Coordination Structural Integrity Suite - Site

The public site for the [Coordination Structural Integrity Suite](https://github.com/coordination-structural-integrity-suite/suite): ten open standards for coordination systems.

**Live site:** https://coordination-structural-integrity-suite.github.io/ai

The site is three pages, one per reader:

- **The Structure** (`index.html`): the landing page. What the suite solves, the tensegrity model behind it, one worked repair, the foundational commitments, and the honest edges. For the general reader.
- **Use the Suite** (`use.html`): the practitioner tools. Three ways in (explore, five-stage gap analysis, resume), guided routing from your situation, and the full prompt library across all ten standards. Every copy button fetches the current published prompt from the standards repository, so what you copy is always the canonical release.
- **The Standards** (`standards.html`): the researcher page. All ten standards at their current versions, each quoting its own statement of purpose and linking to its canonical text, plus the architecture documents and the Dimensional Frame Language substrate.

No accounts, logins, or credits are required. You use your own AI: copy a prompt, open your AI in a new tab, paste, send, then describe your situation. The copy-first sequence is intentional: the prompt must reach the AI before any documents or context, so the diagnostic frame is adopted before material arrives.

## Design

Color is solved by [TEMPER](https://github.com/Polymathie-Studio/temper), a five-mode semantic palette system (System, Light, Soft Light, Soft Dark, Dark; the switcher is in the nav). The suite's two member classes carry the site's two inks: iron for the compressive standards, oxblood for the generative, both held to their hue in every mode. The pages are static single files with no build step; `temper-theme.css` is vendored from the TEMPER repository.

## Standards repository

All standards, prompts, skills, and suite documents live in the [standards repository](https://github.com/coordination-structural-integrity-suite/suite), CC BY 4.0.
