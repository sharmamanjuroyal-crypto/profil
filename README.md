name: profile-card-site
description: "[TODO: Briefly describe what this skill does and when it applies.]"
name: profile-card-site
description: Create polished, responsive personal profile-card websites from a person's supplied details. Use for one-page personal cards, mini portfolios, and digital business cards; not for full multi-page portfolio sites.
---

# Profile Card Site

[TODO: Add the task-specific guidance Codex needs. Reference supporting files only when they are relevant.]
# Profile Card Site

Create a self-contained, attractive profile-card webpage that works by opening a single `index.html` file in a browser.

## Build guidance

- Start with the person's supplied name, role, location, email, biography, links, and preferred style. Do not invent contact details or social URLs.
- Use inline HTML, CSS, and small JavaScript so the result has no build step. External web fonts are optional; make the layout still readable if they do not load.
- Make the composition responsive. On small screens, stack the card's sections vertically and allow page scrolling.
- Include only useful interactions. Good defaults are a mailto contact button and an email-copy button with a short visible confirmation.
- Use decorative CSS artwork or a user-provided image for the portrait. Do not represent a generated illustration as an actual photo of the person.
- Keep color tokens in `:root` and close every HTML element. If editing supplied code, preserve existing working content while repairing malformed nesting, undefined CSS custom properties, stale contact details, or duplicate closing tags.

## Delivery

- Save the completed site as `index.html` in the requested output location.
- Verify that the document has a single `html`, `head`, and `body` element; contact actions use the supplied email; and the narrow-screen layout does not depend on `overflow: hidden`.
- Clearly identify the exact text and links the person can customize after delivery.
