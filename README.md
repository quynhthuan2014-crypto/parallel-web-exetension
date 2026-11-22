<div align="center">
  <img src="assets/readme-hero.svg" width="100%" alt="PARALLEL//WEB Global Voice and Calls - a private social network above every website">

  <br>

  <img alt="Version" src="https://img.shields.io/badge/Version-0.5.4-7C3AED?style=for-the-badge">
  <img alt="Chrome" src="https://img.shields.io/badge/Chrome-138%2B-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white">
  <img alt="Architecture" src="https://img.shields.io/badge/Architecture-Local--first_P2P-0891B2?style=for-the-badge">
  <img alt="License" src="https://img.shields.io/badge/License-Proprietary-E11D48?style=for-the-badge">

  <h1>PARALLEL//WEB</h1>
  <p><strong>A global social layer above the web.</strong></p>
  <p>Turn any page into a private room for posts, chat, voice notes, calls, games, annotations, memes, polls and portals.</p>
</div>

> **COPYRIGHT — NOT MIT — NOT OPEN SOURCE**
> Copyright © 2026 Sio Ca. **ALL RIGHTS RESERVED.** See [LICENSE.md](LICENSE.md).

---

## v0.5.4 VIP group chat and PARALLEL AI

- Every Online Room includes **✨ PARALLEL AI** as a permanent member.
- AI remains silent unless a user explicitly calls `@AI`.
- Type `@` to pick `@AI`, `@All`, or a human member with keyboard, mouse, or touch.
- Each message has reply, share, copy, local pin, local bookmark, multi-select, details, sender recall, and delete-for-me actions.
- A human display name of 2–32 characters is required before creating, inviting, joining, reconnecting, chatting, gaming, or posting in a shared room. Anonymous identities are rejected.
- AI prefers the browser Prompt API and can optionally use a Gemini API key entered on a secure extension-origin page, stored only in local extension storage, and never inserted into the website overlay DOM.
- Chat context is sent to an AI provider only after a user sends a message that explicitly contains `@AI`.

The **✨ AI** button in Chat controls the provider, model, enable state, and 10/30/100-message context limit. **Manage API key securely** opens a dedicated extension-origin page. Google AI Ultra does not automatically provide a Gemini API key; Gemini API usage requires the user's own key.

## v0.5.4 Cốc Cốc Gmail Profile

- A dedicated Cốc Cốc profile card now appears in the popup when the extension runs in Cốc Cốc Browser.
- Use the browser-provided primary profile, retry after signing in, or open the official Cốc Cốc account page.
- The bridge remains explicitly browser-provided and is not presented as third-party Cốc Cốc OAuth verification.
- Detection can use a bounded extension-context hint when the background service worker exposes only a generic Chromium user agent.

### Gmail on Cốc Cốc profile action

The room profile card now exposes **Sign in with Gmail on Cốc Cốc** directly beside the Chrome Google and profile-edit actions. The explicit user action can import the primary browser identity even when Cốc Cốc branding is hidden by Chromium user-agent reduction. Imported profiles remain browser-provided and are never labeled OAuth-verified.

## v0.5.2 runtime recovery hotfix

- Contains stale content-script contexts after an unpacked extension reload.
- Replaces uncaught `Extension context invalidated` failures with a safe page-reload notice.
- Preflights Chrome Translator language support before invoking the local API.
- Keeps rare languages available for community interface packs without sending unsupported options to Chrome Translator.

## The web was built for pages. PARALLEL//WEB makes it feel inhabited.

A normal website is still a normal website. PARALLEL//WEB adds an encrypted, local-first social space above it:

```text
website + private room + shared artifacts + social feed + live communication
```

Each installation is both a client and a replica. Room data is stored locally, synchronized peer-to-peer when possible, and can use encrypted lightweight relay fallback for supported operations when direct data connectivity is blocked.

## Why this release matters

v0.5.4 keeps the global communication layer and adds a visible, safer Cốc Cốc Browser profile bridge.
