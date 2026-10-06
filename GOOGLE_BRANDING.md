# Google branding: published website values

## Current status

The website was published on 6 October 2026. GitHub Pages reported it live,
and the public homepage, Privacy Policy, Terms and logo were visible.
Google Search Console ownership and Google OAuth branding verification
have not yet been completed by this deployment.

Account: https://github.com/muhammadhusnain0925-beep
Repository: https://github.com/muhammadhusnain0925-beep/muhammadhusnain0925-beep.github.io

## Exact values

| Field | Value |
| --- | --- |
| App name | AquaFlow Manager |
| User support email | The developer's monitored email available in the dropdown. If the existing developer account is used, choose muhammadhusnain0904@gmail.com when available. |
| Developer contact email | The same monitored developer email. |
| App logo | images/aquaflow-logo.png |
| Application home page | https://muhammadhusnain0925-beep.github.io/ |
| Application privacy policy | https://muhammadhusnain0925-beep.github.io/privacy.html |
| Application terms of service | https://muhammadhusnain0925-beep.github.io/terms.html |
| Authorized domain | muhammadhusnain0925-beep.github.io |

## Ownership and Google verification

1. Deploy the informational site from the intended GitHub account. Wait until
   GitHub reports that deployment has succeeded.
2. In Google Search Console, use an Owner/Editor Google account of the
   existing AquaFlow Cloud project. Add a URL-prefix property:
   `https://muhammadhusnain0925-beep.github.io/`.
3. Select HTML tag verification and copy Google's exact meta tag into
   `index.html` inside `<head>`. Do not substitute an invented token.
4. Publish that file update, then click Verify in Search Console.
5. Open AquaFlow's Google Auth platform > Branding. Fill the values above,
   save, run Verify Branding and fix any issues Google reports.
6. When Ready to publish, click Publish branding. In Audience, confirm
   External and In Production, completing the console's remaining steps.
7. Reconnect Google Drive in the desktop application after publication.

The selected GitHub account hosts the pages; the existing Google Cloud
project still identifies the desktop app. A client's backup account is
chosen separately through Connect Google Drive in the desktop application.

## Official guides

- https://docs.github.com/en/pages/quickstart
- https://support.google.com/webmasters/answer/9008080?hl=en
- https://developers.google.com/identity/protocols/oauth2/production-readiness/brand-verification
- https://support.google.com/cloud/answer/15549945?hl=en
