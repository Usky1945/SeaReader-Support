# SeaReader Support website

Static multilingual support / privacy pages for SeaReader (海阅笔记).

## Publish using GitHub Pages

1. Create a **Public** repository named `SeaReader-Support` in `Usky1945`.
2. Upload **the contents of this directory** (not the enclosing folder) to the `main` branch.
3. Open **Settings > Pages > Build and deployment**; choose **Deploy from a branch**, `main`, `/(root)`, **Save**.
4. Verify all support and privacy URLs load over HTTPS. Do not paste them into App Store Connect until verified.

Support URLs:
- https://usky1945.github.io/SeaReader-Support/zh-CN/
- https://usky1945.github.io/SeaReader-Support/zh-TW/
- https://usky1945.github.io/SeaReader-Support/en/

Privacy URLs use `/privacy.html` inside each language directory.

## Required release review

- Add a real, monitored contact email (and update each language's support and privacy pages). GitHub Issues is the only contact method currently included.
- Verify all privacy statements against the final compiled app, SDKs, network behavior, data retention, and Apple App Privacy questionnaire. Text currently uses conditional wording where not source-verified.
- Confirm the in-app Restore Purchases UI exists and update the FAQ if it does not.
- Replace any wording that misstates the shipped app's capabilities.
- No app source code, keys or confidential documents belong in this **public** repo.
