# Dramameme GitHub Pages Site

This folder is ready to upload to a public GitHub repository named `dramameme`.

Expected live URLs after GitHub Pages is enabled:

- Web/Desktop URL: `https://charlieevert.github.io/dramameme/`
- Terms of Service URL: `https://charlieevert.github.io/dramameme/terms.html`
- Privacy Policy URL: `https://charlieevert.github.io/dramameme/privacy.html`

## Upload steps

1. Create a public GitHub repo named `dramameme`.
2. Upload all files in this folder to the repo root.
3. Go to **Settings → Pages**.
4. Set source to **Deploy from a branch**.
5. Choose branch `main` and folder `/root`.
6. Save and wait for GitHub Pages to publish.

## TikTok verification file

When TikTok gives you a URL verification/signature file, upload that exact file to this same repo root.

For example, if TikTok gives you `tiktok-developers-site-verification-abc123.txt`, upload it next to `index.html` so it is reachable at:

`https://charlieevert.github.io/dramameme/tiktok-developers-site-verification-abc123.txt`

Then return to TikTok Developer Portal and click verify.

## TikTok app form copy

App description, max 120 characters:

`Dramameme helps creators generate AI-assisted meme drama videos and publish approved clips to TikTok.`

App review explanation:

`Dramameme is a web app that helps creators generate short AI-assisted meme drama videos, review the final video and caption, and publish approved content to their own TikTok account. Login Kit is used so a creator can securely connect their TikTok account to Dramameme through TikTok OAuth. The user.info.basic scope is used only to confirm the connected TikTok account and display basic account information during the connection flow. The Content Posting API is used after the creator reviews and approves a generated video. Dramameme shows the video, caption, privacy options, and posting controls before anything is sent to TikTok. The video.publish scope is used only to publish the creator-approved video to the creator’s own TikTok account. Users remain in control of whether a video is posted.`

## Important

Do not commit TikTok client secrets, refresh tokens, access tokens, API keys, or user tokens to this repo. This is only the static public website and legal/policy surface.
