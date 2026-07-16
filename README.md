# Property Funding Email Options

Static GitHub Pages-ready project for building and hosting Property Funding email template options.

## Structure

- `index.html` - client-facing one-page email builder with name input, live preview and copy controls.
- `options/01-universal-website-design.html` - 01 Universal (Website Design), rebuilt to mirror the current Invest page design.
- `assets/` - shared images. `website-*` files are the Website Design option's imagery: section photos and diagrams reused from the site, plus photo banners (hero, governance, footer CTA, landscape) cropped from the Invest page screenshot with the headline text baked in.

## Local Use

Open `index.html` in a browser.

Current active templates:

- 01 Universal (Website Design)

Website Design notes:

- Investment terms use the supplied PFL icon set from `reemailhtmlupdates`, converted to email-safe PNG assets.
- The governance and footer CTA banners have their buttons baked into the image; the whole banner links to the invest/contact page.
- Footer Privacy Policy, Complaints and LinkedIn links are `#` placeholders until the final URLs are confirmed.

Future direction:

- Add builder flows for different investor types such as individual, trust and company.
- Add builder flows for form-specific and document-specific follow-ups.
- Keep preview, copy body, copy source and download controls for each active template.

## GitHub Pages

This project can be hosted from the repository root with GitHub Pages.

Recommended Pages settings:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

## Before Sending

- Replace staging URLs with final live URLs.
- Check links in each email option.
- Send a test email to Gmail, Outlook, and Apple Mail.
- Confirm all financial/risk wording with Property Funding.
