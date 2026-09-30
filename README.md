# Cohavira website

A responsive, bilingual one-page website for Cohavira. It uses the supplied logo and follows its warm cream, deep green, yellow and orange visual language.

The current version includes a fully translated brand panel, a detailed “Life at Cohavira” journey, service booking through a reception terminal or in-room tablet, optional care, and an illustrative Care Grade 1 cost comparison.

## Open locally

Open `index.html` directly in a browser, or serve the folder with any static web server.

For example:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Before publishing

1. Replace `kontakt@cohavira.de` in `app.js` if this address is not active.
2. Create and link final imprint and privacy pages. Their current footer links are intentionally inactive.
3. Connect the contact form to a consent-compliant form backend if you do not want to use the visitor's email application.
4. Review all contractual, care and reimbursement statements with specialist legal counsel before launch.
5. Replace the illustrative cost assumptions with verified pilot-location prices before using the comparison in public advertising.
6. Optimise the supplied JPG logo or replace it with an official SVG/transparent PNG when available.

## Languages

German is the default. Visitors can switch to English via the DE/EN control; the preference is stored locally in the browser.
