# TwitchTikTok information site

A small English static website for the personal Windows project TwitchTikTok. It is not the desktop application, its source code, or a download service. No public access, TikTok approval, or functioning OAuth integration is claimed.

## Files

- `index.html`: project overview and implemented/planned features.
- `terms.html`: Terms of Service.
- `privacy.html`: Privacy Policy.
- `style.css`: shared responsive styling; system fonts only.
- `README.md`: review and manual publication instructions.

No framework, build, JavaScript, installation, account, media file, analytics, or external asset is required. Open `index.html` locally to review. Links are relative and work under the repository's GitHub Pages subdirectory. The legal links remain visible without a menu on mobile.

## Review before publication

1. Supply the operator's appropriate public identity and a real privacy/support contact. No name, email address, postal address, jurisdiction, or company details have been invented. Review any legally required publisher details for the operator's situation.
2. Confirm the text against the actual software. OAuth, `video.upload`, token storage, revocation, and disconnect controls are explicitly future work. Do not label them implemented until they are.
3. Before enabling integration or accepting other users, decide and document the applicable legal basis, retention, credential protections, deletion process, and rights/contact procedure. There is no implemented guarantee of encrypted token storage or automatic deletion.
4. Review platform naming and branding rules: the current project name contains platform names. The site uses no platform logos or approval badges.
5. Confirm the final public URLs and review the document dates when publishing. These documents need review for the operator's actual legal circumstances; they are not a certification of compliance.

## Important TikTok developer limitation

The current official review criteria exclude private/personal apps and apps still in development from production approval. A website alone does not resolve this eligibility issue. Preserve the truthful project description; do not claim public availability or completion merely to satisfy a review. Check naming rules and approved testing options with TikTok before a submission.

Official references checked for this draft on 16 October 2026:

- [App review criteria](https://developers.tiktok.com/docs/en/app-review-guidelines)
- [Video upload without automatic posting](https://developers.tiktok.com/docs/en/content-posting-api-reference-upload-video)
- [OAuth access-token management](https://developers.tiktok.com/docs/en/oauth-user-access-token-management)
- [GitHub Pages and host IP logging](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)

The intended `video.upload` flow sends a selected video to TikTok; the user then follows an inbox notification to continue editing and finish posting. This site does not implement that flow, an OAuth redirect, or automatic publication.

## Publish manually to the existing `twitch-clips-site` repository

No upload or publication has been performed for you.

1. Open the **existing public** `twitch-clips-site` repository on GitHub. Check any existing content first; do not overwrite work blindly.
2. Choose **Add file > Upload files**. Upload only the five files listed above to the repository root, then review and commit those site files. Do not upload the parent folder or any desktop-project files.
3. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, the branch containing the files (normally `main`), and **/(root)**. Save. No paid plan, custom domain, build tool, or workflow file is needed for this plain public site.
4. Wait for the Pages deployment and use the exact HTTPS address GitHub displays. Enable/enforce HTTPS when that option is available.
5. Open all three pages in a private browser window and on a phone. Check visible legal links, relative CSS, readability, and the project status. Do not submit local file paths to TikTok Developers.

Official [GitHub Pages publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

For a standard project site, the three URLs will follow this pattern. Replace `YOUR-USERNAME` with the actual repository owner; no username has been assumed:

- Overview: `https://YOUR-USERNAME.github.io/twitch-clips-site/`
- Terms: `https://YOUR-USERNAME.github.io/twitch-clips-site/terms.html`
- Privacy: `https://YOUR-USERNAME.github.io/twitch-clips-site/privacy.html`

Use GitHub's displayed URL if the account or repository has a different Pages configuration. Domain/URL verification, any necessary developer access, and OAuth configuration are separate tasks, not provided by this website.

## Publication safety

Upload only this site's five files. Never copy videos, audio, transcripts, annotations, account data, `.env` files, credentials, private keys, model weights, or the desktop project source into the public repository. This site contains no local personal paths or private contact details. Do not create a link to a private media directory.

There is no site-authored data collection. GitHub Pages itself logs IP addresses for security; the Privacy Policy discloses that hosting distinction. External links load only when a visitor chooses them.

## Local validation completed

- Internal page links, stylesheet links, fragment targets, unique IDs, English language tags, viewport metadata, and one main heading per page checked.
- No scripts, forms, embedded media, browser storage, remote stylesheet/font/image requests, credentials, personal contact details, or personal filesystem paths included in the five files.
- Actual isolated Chrome rendering checked: overview at 320, 390, 768, and 1440 CSS pixels wide; Terms and Privacy at 390 pixels. Navigation remains visible and all checked pages fit horizontally without overflow.
- Mobile screenshots of the overview and Privacy Policy and a full desktop overview were visually inspected. This is browser viewport emulation, not a test on a physical iPhone.
- No site publication, repository push, account login, API integration, or change to the desktop project was performed.

Retest the deployed HTTPS URLs after manual publication; local rendering does not prove GitHub Pages deployment or TikTok approval.
