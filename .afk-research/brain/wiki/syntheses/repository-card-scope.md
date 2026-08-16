---
title: RTTJogja repository card scope
date: 2026-08-16
---

# RTTJogja Repository Card Scope

The project is a compact repository card for the RTTJogja GitHub organization.
Its root `README.md` is the project definition and should introduce RTTJogja,
link its public destinations, and briefly reference work in its public
repositories.

The project is not a standalone website implementation or a replacement for
documentation in the referenced repositories.

## Publishing Decision

The card will follow GitHub's public organization profile convention. This
workspace must be published as a public `RTTJogja/.github` repository, and the
rendered card lives at `profile/README.md`. The root `README.md` remains the
project definition.

Source: [GitHub Docs: Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)

On 2026-08-16, the workspace was published as the public
[`RTTJogja/.github`](https://github.com/RTTJogja/.github) repository. GitHub
renders `profile/README.md` on the RTTJogja organization Overview page.

The `https://rttjogja.github.io/` website is actively being developed and will
be published when it is ready. The organization card uses the neutral label
"Website" and does not expose its internal delivery state.

## Visual Direction

The organization profile card uses a colorful, warm visual system built from
deep teal, coral, gold, and cream. A local SVG banner provides the primary
identity, with high-contrast navigation badges and two concise public-work
panels. Text and alt attributes preserve meaning if images do not load.

## Continuity

The blanket `.afk-research/` Git ignore was removed. The shareable
`.afk-research/project.json` identity file is versioned so AFK Research
sessions can recognize the project. App-owned Brain files remain unstaged as
required by the Brain workflow; the root README and Git history provide the
public continuation record.
