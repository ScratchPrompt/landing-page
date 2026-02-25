# ScratchPrompt — Privacy Policy

**Chrome Extension for Saving Snippets and Composing AI Prompts**

*Last Updated: February 25, 2026*

---

> **Summary:** ScratchPrompt does not collect, track, or transmit your personal data. All snippet data is stored locally on your device. Optional Google Drive sync writes only to a hidden app-specific folder that ScratchPrompt cannot use to access your other files.

---

## 1. Introduction

This Privacy Policy describes how ScratchPrompt ("the Extension," "we," "our," or "us") handles information when you use our Chrome browser extension. We are committed to protecting your privacy and being transparent about our data practices.

By installing and using ScratchPrompt, you agree to the practices described in this Privacy Policy. If you do not agree, please uninstall the Extension.

## 2. What ScratchPrompt Does

ScratchPrompt is a productivity tool that allows you to:

- Save highlighted text snippets from any webpage, along with personal notes
- Organize snippets into scratches and categories
- Compose and edit drafts using a rich text editor
- Paste composed text directly into AI chatbot interfaces (ChatGPT, Claude, Gemini, Grok)
- Optionally sync your data to your personal Google Drive for backup

## 3. Data We Collect

### 3.1 Data You Explicitly Provide

ScratchPrompt stores only the data you actively choose to save:

- **Text snippets** — highlighted text you save from webpages
- **Notes** — personal annotations you attach to snippets
- **Source URLs** — the webpage address where a snippet was saved (for your reference)
- **Scratch and category names** — organizational labels you create
- **Composed drafts** — text you write in the built-in editor
- **Extension settings** — your theme preference, layout choices, and other configuration

### 3.2 Data We Do NOT Collect

ScratchPrompt does **not** collect any of the following:

- Browsing history or browsing activity
- Personal information (name, email address, phone number, etc.)
- Authentication credentials or passwords
- Financial information
- Health information
- Location data
- Web content you do not explicitly save
- Usage analytics or telemetry
- Advertising identifiers
- Keystroke data or form inputs

## 4. How Data Is Stored

### 4.1 Local Storage (Default)

All snippet data and settings are stored locally on your device using the Chrome `chrome.storage.local` API. This data remains entirely on your computer, is associated with your Chrome profile, and is never transmitted to any server operated by us.

You can delete all locally stored data at any time by uninstalling the Extension or clearing the Extension's data through Chrome's settings.

### 4.2 Google Drive Sync (Optional)

ScratchPrompt offers an **optional, user-initiated** Google Drive sync feature for backup and cross-device access. This feature:

- Is **disabled by default** — you must explicitly enable it and authorize access
- Uses the `drive.appdata` OAuth scope, which grants access **only** to a hidden, app-specific folder on your Google Drive
- Cannot read, modify, or access any of your other Google Drive files or folders
- Syncs only the snippet data and settings you have saved within ScratchPrompt
- Transfers data directly between your browser and Google's servers — our servers are never involved

You can revoke ScratchPrompt's access to Google Drive at any time through your [Google Account permissions](https://myaccount.google.com/permissions) page.

## 5. How Data Is Used

Your data is used solely to provide the Extension's core functionality:

- Storing and displaying your saved snippets and notes
- Organizing snippets into scratches and categories
- Composing drafts and pasting them into AI chatbot interfaces
- Backing up data to your Google Drive (only when you initiate sync)
- Preserving your settings and preferences across browser sessions

Your data is **never** used for advertising, profiling, analytics, or any purpose unrelated to the Extension's stated functionality.

## 6. Data Sharing and Third Parties

ScratchPrompt does **not** share, sell, rent, trade, or transmit your data to any third parties. Specifically:

- No data is sent to our servers (we do not operate data-collection servers)
- No data is shared with advertisers
- No data is shared with data brokers
- No data is sold to any party
- No third-party analytics, tracking, or telemetry services are used

The only external service ScratchPrompt communicates with is the **Google Drive API**, and only when you explicitly initiate a sync. This communication is directly between your browser and Google's servers, governed by [Google's Privacy Policy](https://policies.google.com/privacy).

## 7. Permissions and Their Purpose

ScratchPrompt requests only the Chrome permissions necessary for its core features. Below is a complete explanation of each permission:

| Permission | Why It's Needed |
|---|---|
| `storage` | Save your snippets, drafts, categories, and settings locally on your device. |
| `unlimitedStorage` | Allow you to save large collections of snippets without hitting Chrome's default storage quota. |
| `activeTab` | Read the text you highlight on the current page so it can be saved as a snippet. |
| `scripting` | Inject the save dialog overlay when you save a snippet and the view panel when you browse your collection. |
| `contextMenus` | Add a "Save to ScratchPrompt" option to the right-click context menu. |
| `identity` | Authenticate with Google OAuth so you can optionally sync data to Google Drive. |
| `tabs` | Find open AI chatbot tabs (ChatGPT, Claude, Gemini, Grok) so composed text can be pasted into them. |
| `<all_urls>` | Enable the save dialog to appear on any webpage you visit and allow the paste content script to run on AI chat sites. |
| `googleapis.com` | Communicate with the Google Drive API for optional cloud sync. |

## 8. Remote Code

ScratchPrompt does **not** use remote code. All JavaScript, HTML, and CSS is bundled within the Extension package. No code is loaded from external servers at runtime.

## 9. Data Security

Your locally stored data is protected by Chrome's built-in extension sandboxing and your operating system's user-account protections. When Google Drive sync is used, data is transmitted over HTTPS (TLS-encrypted connections) directly to Google's servers.

While we take reasonable measures to protect your data, no method of electronic storage is 100% secure. We encourage you to keep your operating system and browser up to date.

## 10. Data Retention and Deletion

Your data is retained only as long as you choose to keep it:

- **Local data:** Persists until you delete individual items within the Extension, clear the Extension's data in Chrome settings, or uninstall the Extension.
- **Google Drive data:** Persists in your Google Drive's hidden app folder until you delete it through the Extension, revoke the Extension's access, or delete it from Google Drive directly.

We do not retain any copy of your data on any server. Once deleted from your device and/or Google Drive, the data is gone.

## 11. Your Rights

You have full control over your data at all times:

- **Access:** View all your saved data within the Extension's dashboard at any time.
- **Modification:** Edit any snippet, note, category, or draft at any time.
- **Deletion:** Delete individual items or all data at any time.
- **Portability:** Export your data via Google Drive sync.
- **Revocation:** Revoke Google Drive access at any time through your Google Account settings.

## 12. GDPR Compliance (European Users)

For users in the European Economic Area (EEA), the United Kingdom, or Switzerland, we are committed to compliance with the General Data Protection Regulation (GDPR):

- **Lawful basis:** We process data based on your explicit consent (you choose what to save) and legitimate interest (providing the Extension's functionality).
- **Data minimization:** We store only the data you explicitly provide, and nothing more.
- **No cross-border transfers by us:** Your data stays on your device. If you enable Google Drive sync, data transfers to Google's servers are governed by Google's own GDPR commitments and data processing agreements.
- **Right to erasure:** You can delete all your data at any time (see Section 10).
- **Right to access and portability:** All your data is visible and accessible within the Extension.
- **No automated decision-making:** We do not perform profiling or automated decision-making with your data.

## 13. CCPA Compliance (California Users)

For users in California, under the California Consumer Privacy Act (CCPA):

- We do **not** sell your personal information.
- We do **not** share your personal information for cross-context behavioral advertising.
- You have the right to know what data is stored — all of it is visible within the Extension.
- You have the right to delete your data at any time.

## 14. Children's Privacy

ScratchPrompt is not directed at children under the age of 13 (or the applicable age of digital consent in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided data through the Extension, please contact us so we can assist with deletion.

## 15. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last Updated" date at the top of this page and, where appropriate, provide notice through the Extension or Chrome Web Store listing.

We encourage you to review this Privacy Policy periodically. Your continued use of the Extension after changes are posted constitutes acceptance of the updated policy.

## 16. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us at:

**Email:** [your-email@example.com](mailto:your-email@example.com)

---

© 2026 ScratchPrompt. All rights reserved.
