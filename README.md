# letsconnect-alt

Alternate, dark AI-First edition of Jeff Danley's NFC tap-card contact page.

- Live preview: https://jarvisdanley.github.io/letsconnect-alt/
- Single static `index.html` (inline CSS and JS, no build step) plus `assets/`.
- Same facts, links and Save-to-contacts vCard as the original card.

## Motion

Three motion components were ported to vanilla JS from
[Rare UI](https://rareui.com) (source: github.com/swamimalode07/rare-ui):

- **Fluid Orb**: WebGL fbm shader glowing behind the headshot, recolored violet, cyan and orange.
- **Gravity Letters**: the name drops in letter by letter with Rare UI's gravity, bounce and squash. Tap the name to replay.
- **Toast**: success confirmation after Save to contacts.

All motion is disabled under `prefers-reduced-motion`, and the orb pauses when the tab is hidden or the orb is off screen.

## Credit and license

Motion components by [Rare UI](https://rareui.com).
Copyright (c) 2026 Swami Malode. Used under the MIT + Commons Clause License Condition v1.0 + Attribution
([license](https://github.com/swamimalode07/rare-ui/blob/main/LICENSE)). The ported code is part of this
page only and is not redistributed as a component library.
