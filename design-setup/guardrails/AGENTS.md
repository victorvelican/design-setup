# Rules for an AI coding agent working on this design

1. Values live in `design/tokens.css`. Never write a colour, radius, shadow or duration literal in a component.
2. The page loads nothing from a third party: no analytics, no tag manager, no session recorder, no fonts from another host, no external script. A content security policy enforces it; do not loosen it.
3. The copy rules in `design/copy-rules.md` are tests, not advice. Rendered text is swept before every release.
4. Every page fits from 320 to 1920 px wide with no horizontal scroll, signed in and signed out, and reads with every image removed.
5. Motion follows `design/BRAND.md`: 150 to 220 ms, opacity and transform only, off under reduced-motion. No parallax, no scroll reveals, no animated backgrounds.
6. Nothing goes to production without a preview the founder has looked at on a phone. The agent uploads previews under an alias; it never deploys production on its own initiative.
7. Secrets never appear in chat, in a script's output or in a record. They are set by a person from a terminal.
8. Every change is diffed against the live commit before release; any earlier fix that shows as reverted stops the release.
9. Every release names its rollback and what that rollback is bound to (database, storage), in the record.
10. Report in facts: version id, what was measured, what was checked, what was not. "Done" without evidence is not done.
