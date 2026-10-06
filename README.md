# AquaFlow Manager: public product information

Static pages for AquaFlow Manager by DevAxis (Pvt.) Ltd. These pages describe
the desktop software and its Google Drive data handling. They are separate
from the business database and the desktop software source.

## Files to publish

- `index.html`: app introduction and developer contacts.
- `privacy.html`: Google user data, local storage, backups and deletion.
- `terms.html`: application and backup usage terms.
- `styles.css`: responsive layout.
- `images/aquaflow-logo.png`: the supplied AquaFlow logo.
- `.nojekyll`: serve the static files without a Jekyll build.

Publish only this directory. The application source, local business data,
backups, OAuth configuration and Google tokens are not website assets.

## GitHub Pages

GitHub owner: `muhammadhusnain0925-beep`, explicitly selected by the user.
Repository: https://github.com/muhammadhusnain0925-beep/muhammadhusnain0925-beep.github.io
The public site was published on 6 October 2026 from `main` and `/(root)`.
GitHub reported a successful deployment, and the homepage, Privacy Policy,
Terms and supplied logo were visible on the public site.

1. With the intended account, create a public repository named
   `muhammadhusnain0925-beep.github.io`, unless that user site already exists.
   Inspect an existing repository and website before proposing changes.
2. Add these static files to the repository's default branch, usually `main`.
3. Open Settings > Pages > Build and deployment.
4. Choose Deploy from a branch, the default branch and `/(root)`, then Save.
5. Confirm GitHub's reported deployment URL and the published pages. The
   published URL is `https://muhammadhusnain0925-beep.github.io/`.

Google Search Console ownership and OAuth brand verification are separate
steps and have not yet been completed by this website deployment.

## Google Search Console

Use a Google account that is an Owner or Editor of the AquaFlow Google Cloud
project. Add a URL-prefix property for the actual published site URL. Choose
HTML tag verification. Add Google's exact `google-site-verification` meta
tag inside `index.html`'s `<head>`, publish the change, and then click Verify
in Search Console. Keep the verified tag present.

Google's verifier must be able to access the public homepage and privacy
policy. Approval is determined by Google's checks; deployment alone does
not confirm OAuth brand verification.

## Google Auth platform > Branding

- App name: `AquaFlow Manager`.
- User support email: the developer's monitored email available in the
  dropdown; keep it consistent with the actual project account.
- Developer contacts: the monitored developer email.
- Logo: the supplied AquaFlow PNG.
- Homepage: `https://muhammadhusnain0925-beep.github.io/`.
- Privacy: `https://muhammadhusnain0925-beep.github.io/privacy.html`.
- Terms: `https://muhammadhusnain0925-beep.github.io/terms.html`.
- Authorized domain: `muhammadhusnain0925-beep.github.io`, without a scheme
  or path, after ownership verification.

Save, run Verify Branding and resolve any reported issues. On Ready to
publish, use Publish branding. In Audience, confirm External and change the
publishing status to In Production when the console requirements are met.
Reconnect Google Drive in the desktop application after production publishing.

Before client delivery, make the published Privacy Policy accessible from
inside the desktop application as required by Google's policy. Use the
published Privacy Policy address above.

## Preparation status

Content was prepared from the existing Google Drive integration source on
6 October 2026. Publication was checked in GitHub Pages and the public
browser pages. No automated tests or desktop app workflow tests have been
run. A new EXE has not been built as part of this website task.
