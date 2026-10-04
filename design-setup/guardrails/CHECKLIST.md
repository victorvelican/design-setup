# From a change to production, in order

1. Build on a preview alias, never on production. Tests green: unit, browser, the rendered-text sweep, the fit sweep 320 to 1920 in both states.
2. The rendered text of every touched page, pasted in full, for the text check against `design/copy-rules.md`.
3. Screenshots at 390 and 1280 of every touched page.
4. The founder looks at the alias on his phone and says what is wrong, page by page, or that it is good.
5. The text check: never-say list, locked numbers, locked sentences, one vocabulary.
6. The GO, in writing, naming the commit.
7. Before the version: the delta diffed against the live commit; the rollback version named with its bindings; migrations listed with what they delete (a fresh count of any table a migration drops).
8. The release, then the live checks: every public page answers, no accidental `noindex`, headers unchanged, the one real action tried by a person (a booking, a kept statement).
9. The record: version id, timestamps, row counts before and after, arrival sizes per page, the credits line, the never-say line.
10. The mirror pushed fast-forward only, after the live checks.
