# KitUp legal site (GitHub Pages)

Official website for the **KitUp** TikTok / Meta developer app review.

**Live:** https://bilalgurkansanli.github.io/kitup-legal/

## TikTok Developer Portal — exact values

| Field | URL |
|-------|-----|
| **App name (Basic Info)** | `KitUp` |
| **App icon (Basic Info)** | Upload `app-icon.svg` exported as **1024×1024 PNG** (same file as favicon) |
| **Website URL** | `https://bilalgurkansanli.github.io/kitup-legal/` |
| **Privacy Policy URL** | `https://bilalgurkansanli.github.io/kitup-legal/privacy.html` |
| **Terms of Service URL** | `https://bilalgurkansanli.github.io/kitup-legal/terms.html` |
| **Redirect URI (Web)** | `https://bilalgurkansanli.github.io/kitup-legal/callback.html` |

**Do not** use `callback.html` as Website URL. Redirect URI must **not** contain the word `tiktok`.

## Before resubmit

1. Export `app-icon.svg` → PNG 1024×1024 and upload to TikTok **Basic Info → App icon**.
2. Verify favicon + header logo match that icon on all pages.
3. **Verify URL properties** for Website, Privacy, and Terms (Production).
4. Demo video must open **index.html** (KitUp home), not the OAuth callback page.

## Deploy

Copy all files to `bilalgurkansanli/kitup-legal` repo root and push to `main`.
