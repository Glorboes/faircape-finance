# Fair Cape Finance

A responsive, multi-page website for Fair Cape Finance in Pinelands, Cape Town.

## Preview

https://faircape-finance.wxzpdsh88y.chatgpt.site/ (private Sites preview)

## Run locally

No build step or dependencies are required. From this directory:

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173.

## Structure

- `dist/index.html`: cinematic homepage
- `dist/about.html`: about the business
- `dist/learn.html`: learning centre and compound-growth calculator
- `dist/documents.html`: printable preparation checklists
- `dist/contact.html`: contact placeholders and Howard Centre map
- `dist/style.css` and `dist/app.js`: shared styling and interactions
- `dist/assets/`: supplied company logo
- `.openai/hosting.json`: existing Sites deployment configuration
- `MEDIA-CREDITS.md`: media sources and design reference

## Accessibility

Visible mobile navigation, readable text, keyboard focus states, a skip link, optional larger text and high contrast, and browser-supported read-aloud. Background film is muted and pausable; mobile and reduced-motion visitors choose whether to play it.

## Before public launch

Confirm company information, services and regulatory disclosures; provide WhatsApp and email details, office suite and visiting hours; replace draft content and supply approved company documents. Educational material is general information, not personalised advice.

## Hosting

Serve `dist/` as the static site root. The current preview is hosted through Sites. Pushing to GitHub does not automatically deploy changes to Sites. Video, photography, fonts and Google Maps are externally hosted and require connectivity.
