# gcp-goog-connector

This repository contains the public information pages for `gcp-goog-connector`, a private Google OAuth application operated by DenIT.

The application exists only to let the operator's self-hosted n8n instance, running on a private NAS, connect to the operator's Google Drive account. It is not a public product and does not offer user registration.

This repository contains no application source code, OAuth credentials, access tokens, Google user data, or n8n workflows.

## Public pages

- [Application homepage](https://n8n-google-drive.pastuszka.me/)
- [Privacy Policy](https://n8n-google-drive.pastuszka.me/privacy/)
- [Terms of Service](https://n8n-google-drive.pastuszka.me/terms/)

## Hosting

The pages are published from the `main` branch with GitHub Pages. The custom domain is declared in [`CNAME`](CNAME).

The DNS configuration for `n8n-google-drive.pastuszka.me` must contain this record:

```text
Type: CNAME
Name: n8n-google-drive
Target: ppastuszka.github.io
```

After the DNS record and GitHub Pages are active, use these values in Google Auth Platform → Branding:

```text
Application home page: https://n8n-google-drive.pastuszka.me/
Application privacy policy link: https://n8n-google-drive.pastuszka.me/privacy/
Application terms of service link: https://n8n-google-drive.pastuszka.me/terms/
Authorized domain: pastuszka.me
```
