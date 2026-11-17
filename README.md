# Website (GitHub Pages)

The public pages App Store Connect asks for: `index.md` (home), `privacy.md` (Privacy Policy URL) and `support.md` (Support URL). GitHub Pages turns the Markdown into web pages; no build step.

`privacy.md` must stay identical to `docs/privacy.md` and the copy in the app (`ysn/Account/Legal/PrivacyPolicy.md`); `LegalTests` checks this.

## Publish
1. On github.com, create a new **public** repository, for example `youthsportshub`. (Keep the app's own repository private; only these files need to be public.)
2. Upload `index.md`, `privacy.md`, `support.md` and `_config.yml` (Add file › Upload files › Commit).
3. Settings › Pages › Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** › Save.
4. After a minute or two the site is at `https://<your-username>.github.io/youthsportshub/`.

In App Store Connect:
- Privacy Policy URL: `https://<your-username>.github.io/youthsportshub/privacy.html`
- Support URL: `https://<your-username>.github.io/youthsportshub/support.html`
- Marketing URL (optional): `https://<your-username>.github.io/youthsportshub/`

When the policy changes, edit `docs/privacy.md`, copy it to the other two places, and upload the new `privacy.md`.
