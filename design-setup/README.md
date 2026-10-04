# Design setup: guardrails for building better design with AI

This folder is the design setup for TareCount (tarecount.com), a small web product built and shipped by one founder directing AI coding agents, with no contractor. It holds the rules the design is built to, written so that a person or an AI builder can apply them without asking.

How it is used: every page is built against `design/` (what it looks like, what it says, what its images may show) and checked against `guardrails/` (how a change reaches production) before anything goes live. The files are plain markdown and CSS so that any no-code or AI tool can read them as instructions.

```
design-setup/
  README.md               this file
  design/
    BRAND.md              the look: palette roles, typography, spacing, corners, shadow, motion
    tokens.css            the same rules as CSS custom properties, the only place values live
    copy-rules.md         what the text may and may not say, and how it is enforced
    imagery.md            what generated images and films may and may not show
  guardrails/
    AGENTS.md             rules for an AI coding agent working on this design
    CHECKLIST.md          the path from a change to production, in order
  examples/
    README.md             what the screenshots show (add your own)
```

The idea in one sentence: the rules live in files, the values live in tokens, and every change is looked at on a phone before it is live.
