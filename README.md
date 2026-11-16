# Steps to Grow

A free, English-language, mobile-friendly educational website by [@katerinaramm1](https://x.com/katerinaramm1), focused on practical growth without an advertising budget.

## What's included
- Three-phase guide: **Find → Convert → Improve**
- Interactive challenge selector
- Customer persona worksheet with `.txt` download
- Sales workflow checklist with `.txt` download
- 30-day checklist (progress stored in browser localStorage)
- Starter CSV lead tracker, email templates and monthly review worksheet
- Responsive design, blue logo, light/dark mode
- Email contact form using `mailto:` (see setup below)
- No backend, account, analytics tracker or external dependency

## Publish with GitHub Pages

1. On GitHub, click **New repository** and name it `steps-to-grow` (or any available name). Set it to **Public**.
2. Upload **all four files** from this folder to the **root** of your repository: `index.html`, `styles.css`, `script.js`, and `favicon.svg` (you may include this README too).
3. Commit the changes.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Set branch to `main` and folder to `/ (root)`, then **Save**.
5. After GitHub finishes publishing, open `https://YOUR-USERNAME.github.io/steps-to-grow/` (replace the username and repository name with yours).

GitHub Pages settings and naming can change; consult GitHub's documentation if the settings appear differently.

### Configure contact email (IMPORTANT)

By default, the contact form **does not send messages**. It displays a setup notice rather than guessing your personal email.

In `script.js`, at the very top, edit:

```js
const CONTACT_EMAIL = 'katerinaramm@zohomail.eu';
```

to:

```js
const CONTACT_EMAIL = 'katerinaramm@zohomail.eu';
```

The form then opens the visitor's email app with a prefilled message. They **must press Send** in that app. This method does not work for visitors who have not configured an email app. It also exposes your email address in public source code.

To use a proper hosted contact form later, choose a service that handles spam prevention, validation, privacy and delivery; do not publish private API keys in the site's JavaScript. Inform visitors about your data processing and privacy practices.

## Customize
- Change text in `index.html`.
- Change blue colors in the CSS variables at the start of `styles.css`.
- Replace the self-contained blue SVG `favicon.svg` for a different mark.
- There are no external libraries or build steps.
- Test by opening `index.html` in your browser. The downloads and interactive tools work offline.

## Privacy and limitations
- The guide and tools are educational, not a guarantee of business results.
- 30-day checklist, theme, and chosen workflow steps are stored only in the visitor's own browser using `localStorage`.
- Persona information is not transmitted to the website; the visitor can generate and save it as a local file.
- The lead-tracker spreadsheet is a blank starter template with a clearly labeled sample row. Keep real customer data secure and comply with applicable laws (e.g. GDPR for EU businesses).
- No cookies for analytics, visitor counter, or backend are included.
- The contact form uses `mailto:`; it doesn't send or log form submissions on the website.

## Credits
Created by @katerinaramm1 on X with the help of ChatGPT.
