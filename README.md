# AL ASAS Staging Assets

This repository stores public, immutable image assets for the AL ASAS Staging website.

## Layout

- `staging/YYYY-MM-DD/` — assets uploaded by the protected Staging media backend.
- `README.md` — repository documentation only; no credentials or test images are committed.

Uploads must be performed by the approved GitHub App installation for `NAJF8/al-asas-assets`. The app private key is never stored in this repository, Firestore, or browser code.