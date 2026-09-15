# Website design and verification — 2026-09-15

References: existing AirGiggle and Julsai public app/support/privacy structures. Implementation: static semantic HTML and shared CSS; no JavaScript or build dependencies.

## Fidelity ledger
- Layout: retained the generated concept’s two-column hero, single phone, three feature labels, numbered instructions, and privacy section.
- Typography: large system sans-serif title, restrained secondary copy; Korean and English layouts reviewed at mobile widths.
- Palette: near-black #080a0b, ivory #f3f4f2, mint #b6f9d0, muted green-gray text and rules.
- Assets: used the actual industrial hilt and approved app icon. The phone is a presentation frame, with a subtle CSS emitter glow.
- Spacing: generous hero spacing and separated editorial sections; mobile stacks content in reading order.
- Intentional changes: initially omitted the concept’s photo of two players. Restored on user request with a dedicated image derived from that concept. Corrected copyright year to 2026, localized navigation, and made privacy statements precise to implementation. No public download link is available yet.

## Verification
- All six pages checked at widths 1440, 390, and 320 CSS pixels: no horizontal overflow or missing images; no page errors.
- Local navigation and asset paths resolve, including language-specific policy and support routes.
- Desktop and mobile full-page renders visually inspected against the concept.
- Ego browser loaded and inspected the DOM; its screenshot endpoint timed out twice. Playwright was used as the rendering fallback.
- Privacy audit delegated to a read-only reviewer, then checked and integrated by the main agent. No source code or distribution files were copied into this public repository.

## Maintenance
Replace Coming soon with a verified App Store destination after release. Update both languages whenever app behavior changes. Privacy wording describes the current app, not a certification of legal compliance.

## Nearby image correction
Restored the two-player photograph in both language homepages. Desktop places copy beside the image; mobile stacks the complete image below the copy. Original app assets remain unchanged.
