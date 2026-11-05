# AGENTS.md — Rules for working on this site (Julian Mateus)

This is a personal professional homepage (GitHub Pages: jcmateusg.github.io).
Source of truth for content: `CV Julian Mateus_LV.pdf`. Photo: `photo.jpg`.

## Never publish
- Phone number, home address, date of birth, or any other personal identifier not already intended for public use.
- Anything not in the CV or explicitly provided by Julian. No invented facts, metrics, titles, dates, links, or testimonials.
- Confidential or non-public material from Banco de la República or any employer or client.
- Credentials, tokens, API keys, or private files (this folder may contain others).
- Third-party content (logos, images, text) without permission or a clear license.
- Fabricated URLs. If a link (e.g. a publication PDF) is unknown, show plain text instead of guessing.

## Ask Julian first
- Before any `git` push, commit to a remote, deploy, or other publishing action. Nothing goes to GitHub without an explicit go-ahead.
- Before adding contact details (email, phone), or changing which ones appear.
- Before adding, removing, or rewording CV content, or changing section order (it must follow the CV).
- Before adding third-party scripts, analytics, trackers, fonts or assets loaded from external servers.
- Before renaming or deleting existing files, or overwriting anything not created by the agent.
- When a CV claim is ambiguous or looks outdated (e.g. "May 2027", "2025-2027").

## Style
- Tone: professional, concise, factual. First person is avoided; neutral CV voice.
- Visual: Banco de la República blue palette (navy `#003A70` primary, mid-blue accent, light blue-gray surfaces), white backgrounds, generous whitespace.
- Navigation: single page, sticky top bar with anchor links, in CV section order: Education, Experience, Additional Information, Publications.
- Content: all CV information is included, in CV order; tiles/cards used for scanability.
- Tech: plain HTML + CSS (+ minimal JS only if needed), no build step, no external dependencies, responsive, accessible (semantic tags, alt text, sufficient contrast, keyboard focus).
- Language: English for the page; Spanish publication titles kept in original with English translation, as in the CV.
- Keep the repo simple: files at the root, descriptive names.
