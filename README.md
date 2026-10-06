# First Contract (public artifacts)

The public, redacted half of **First Contract**, an entry in the [Zo Build Challenge](https://ambassador.zo.space/build-challenge) for October 2026.

First Contract is the account of using Zo to turn one informal conversation into a real contracting engagement: researching the client and the market, working out what it actually takes to bill as an independent contractor, reading the client's supplier terms, and drafting the statement of work, the milestone schedule, the acceptance criteria, the commercial terms, and the IP and data boundaries. The engagement was priced as a fixed-fee pilot with milestone payments, and the draft terms are not yet signed.
The client is deliberately unnamed. This repository is a public surface for the challenge, and the client's identity adds nothing to the entry. Only publicly published, non-confidential material from that engagement appears here; nothing proprietary is reproduced.

The review page is a single HTML file in this repository (`review/index.html`), plus the brand marks it uses. It is published with GitHub Pages at <https://ethanthatonekid.github.io/zocomputer-first-contract/>: the site root and `/review/` serve the same page, and `.github/workflows/pages.yml` republishes it on every push to `main`.

## What is in here

| Path | What it is |
| --- | --- |
| `review/index.html` | The client-facing review page, redacted: the scope, acceptance criteria, assumptions, and open decisions. |
| `review/assets/zo-pegasus.svg` | The Zo pegasus mark, downloaded from <https://www.zo.computer/brand>. Used as the page favicon and in the footer credit. |
| `review/assets/zo-wordmark.svg` | The Zo wordmark, from the same source. Used in the footer credit. |

## Brand

The page is built on the Zo brand system rather than its own visual language.

- **Color.** The page tokens are the published light values from <https://www.zo.computer/design/tokens>, converted from OKLCH to sRGB: background, card, muted surface, foreground, muted foreground, primary, accent, accent foreground, border, success, and warning. The brand radius scale (0.625rem, times 0.5, 0.75, 1, 1.5, 2, and 4) replaces the page's earlier ad-hoc corner radii.
- **Type.** EB Garamond, the brand serif for the wordmark and section headings, carries the page title and section headings. MonoLisa Text, the brand sans, is commercially licensed and is not redistributed here, so body copy falls back to the system sans stack.
- **Marks.** The pegasus and wordmark SVGs are vendored from <https://www.zo.computer/brand> and are used unmodified: the pegasus as the page favicon, and both marks in the footer credit that links to <https://www.zo.computer>.

## Redaction

This copy carries the shape of the engagement and none of its confidential specifics. Removed or generalized:

- **Money.** Every figure is gone: the pilot fee, the milestone amounts, the ceiling, the contingency, the hourly rate, and the nominal planning hours in currency terms.
- **The client.** Named in the private pack only. Here it is "the client", with no company name, location, or identifying product terminology.
- **Commercial terms.** The fee schedule lives in the private pack; the public page keeps only the commercial structure (fixed fee, milestone releases, not-to-exceed ceiling, change-order rule).

The private half, with the real figures and the client name, lives in a private companion repository and goes to the judges privately. Nothing here has been sent or published on its own.

## Open decisions

The public page is live, but the entry's build link does not point at it yet, and whether the submission video is produced at all is still open. Both are listed at the end of the private submission pack.
