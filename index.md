:::writing{variant="document" id="61427" title="Privacy Policy — WhatsApp Privacy Guard"}
# Privacy Policy — WhatsApp Privacy Guard

**Last Updated: August 19, 2026**

## 1. Overview

WhatsApp Privacy Guard is a Microsoft Edge browser extension designed to help users protect their privacy while using WhatsApp Web.

The extension applies visual blur effects to selected content displayed on WhatsApp Web, including profile pictures, contact names, message previews, conversation messages, and media.

WhatsApp Privacy Guard is designed with a local-first approach. WhatsApp content is processed within the user's browser and is not intentionally transmitted to the developer or to external servers.

## 2. Local Processing

WhatsApp Privacy Guard processes WhatsApp Web content locally within the browser to provide its privacy and blur features.

The extension does not use an external server to process WhatsApp messages or other WhatsApp Web content.

The extension does not use external AI services, analytics services, advertising trackers, or remote processing services.

Message classification, including the optional Smart Message feature, is performed locally using a deterministic pattern-based detection system.

## 3. Information Accessed

To provide its functionality, the extension operates only on WhatsApp Web.

Depending on the user's enabled settings, the extension may process content displayed on WhatsApp Web, including:

- Profile pictures
- Contact and group names
- Message previews
- Conversation message text
- Images and videos displayed in conversations

This information is processed in the browser to apply visual blur effects.

## 4. Smart Message Detection

The Smart Message feature can locally analyze message previews and conversation text for predefined romantic expressions, words, nicknames, and emojis.

The detection system operates within the browser.

Message content used for detection is not intentionally sent to the developer, an external server, an external API, or an external analytics service.

## 5. Data Storage

The extension uses the browser's `chrome.storage.sync` API to store user preferences.

The stored preferences include:

- `blurProfile`
- `blurName`
- `blurMessage`
- `blurConversation`
- `blurIntensity`

These values are configuration settings used to remember the user's selected privacy preferences.

WhatsApp message content, profile pictures, contact names, conversation history, or media are not stored by the extension.

## 6. Data Transmission

WhatsApp Privacy Guard does not intentionally transmit WhatsApp message content, contact names, profile pictures, conversation content, or media to the developer or to external servers.

The extension does not operate its own backend server or database for collecting WhatsApp content.

## 7. Analytics, Advertising, and Tracking

WhatsApp Privacy Guard does not use:

- Analytics services
- Advertising networks
- Advertising trackers
- User activity tracking services
- External data collection services

The extension does not intentionally track users' browsing activity outside the functionality required to operate on WhatsApp Web.

## 8. Permissions

The extension requests the following permissions:

### Storage

The `storage` permission is used to save the user's privacy and blur preferences.

### WhatsApp Web Access

The extension operates on:

`https://web.whatsapp.com/*`

This access is required to apply the privacy and blur functionality to WhatsApp Web content.

The extension does not request access to unrelated websites.

## 9. Data Sharing and Sale

We do not sell, rent, or intentionally share users' WhatsApp content or personal information with third parties.

The extension is designed to process WhatsApp Web content locally in the browser rather than sending that content to an external service.

## 10. Third-Party Services

WhatsApp Privacy Guard does not rely on external APIs, AI services, analytics platforms, advertising services, or external databases to provide its core functionality.

## 11. Security and Privacy Design

WhatsApp Privacy Guard follows a local-first privacy design:

**WhatsApp Web → Edge Extension → Local browser processing → Visual blur**

There is no developer-controlled server involved in processing WhatsApp content.

However, users should understand that Microsoft Edge, WhatsApp Web, and other browser or platform services are separate services governed by their own policies and practices.

## 12. Changes to This Privacy Policy

This Privacy Policy may be updated if the extension's functionality, permissions, or data practices change.

The latest version of this Privacy Policy will be published in this repository.

## 13. Contact

For questions or feedback regarding WhatsApp Privacy Guard or this Privacy Policy, users may contact the developer through the Microsoft Edge Add-ons support channels or the project's GitHub repository.

## 14. Trademark Disclaimer

WhatsApp Privacy Guard is an independent third-party Microsoft Edge extension.

It is not affiliated with, sponsored by, or endorsed by WhatsApp or Meta Platforms, Inc.

"WhatsApp" is a trademark of Meta Platforms, Inc.

---

**Privacy principle:** WhatsApp Privacy Guard is designed to keep WhatsApp content processing inside the user's browser and does not intentionally send WhatsApp content to external servers or third parties.
:::
