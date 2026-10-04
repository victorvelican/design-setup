# Copy rules

## Only what is on record
Every number on a page comes from a record that can be shown. Example figures from a constructed sample are labelled "Example, not a finding". No percentage is printed except on the constructed sample. No claim about "typical" customers, averages or industry standards.

## Never-say list
These words do not appear in the product's voice: verified, average, typical, save, catch, containment, success fee, commission, contingency, guarantee, industry standard, instant, in seconds, upload, slot, scheduled, calculator, ROI, trusted by, up to, no savings no fee, pay only if. A quoted document (a published standard) is exempt and is pinned by a checksum so nobody edits it silently.

## Punctuation and tone
No em-dash, no exclamation mark, no emoji. One vocabulary for one thing: Sign in, Sign out, Create account; Keep, Kept; "time" and "booked", never "slot" or "scheduled". Short sentences. Say what the thing does, never what it will do for someone.

## How it is enforced
A test runs the never-say list over the rendered text of every public page and every transactional mail, not over source files, so a word that reaches the screen fails the build. Locked sentences (pricing, neutrality, the fixed-fee line) are pinned by tests that fail on any edit.
