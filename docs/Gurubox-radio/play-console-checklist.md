# GuruBox Radio - Google Play Console Checklist

Last reviewed: 20 October 2026

This checklist reflects GuruBox Radio package `net.gurubox.radio` as currently implemented. Recheck every answer whenever features or SDKs change.

## Public URLs

- Document hub: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/
- Privacy policy: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/privacy-policy.html
- Support: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/support.html
- Terms of Use: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/terms-of-use.html
- Data safety explanation: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/data-safety.html
- Content and copyright: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/content-rights.html
- Local data deletion: https://sirfcode.github.io/nzkosh/docs/Gurubox-radio/data-deletion.html

## App content declarations

- Ads: No. The app contains no ad SDK or advertising.
- App access: All functionality is available without login, membership, location restriction, or special access instructions.
- Accounts: The app does not create user accounts.
- News app: No.
- Government app: No.
- Financial features: No.
- Health features: No.
- User-generated content: No comments, chat, uploads, profiles, or public submissions.
- Purchases: No in-app purchases or subscriptions.
- High-risk permissions: None. Current permissions are internet, wake lock, foreground service, and media-playback foreground service.
- Content rating: Complete the IARC questionnaire accurately for devotional audio and lyrics. There is no violence, gambling, sexual content, user interaction, or unrestricted web browsing built into the app.
- Target audience: Select the genuine intended age groups. Do not select child age groups merely because the content is family-friendly; doing so invokes Families policy obligations.
- Privacy policy: Supply the public privacy-policy URL above and keep the matching policy available inside the app.

## Data safety review

Current implementation:

- No analytics, advertising, crash-reporting, account, or tracking SDK.
- No name, email, phone, contacts, location, photos, microphone, advertising ID, payment data, or user files requested.
- Technical playback diagnostics are stored locally and shared only after the user deliberately invokes Android's share sheet.
- GuruBox and third-party audio hosts receive ordinary network request information, including IP address and request metadata, while serving content.

Before answering the Data safety form, verify the current behaviour and policies of every content host and dependency. Google Play makes the developer responsible for accurate declarations, including third-party code.

## Store listing checks

- App name and descriptions accurately describe radio, satsang, Vani, bhajan, and lyrics.
- Screenshots show actual app screens and do not promise unavailable features.
- Contact details and support URL are current.
- App icon, feature graphic, phone screenshots, and release notes are supplied.
- Privacy policy URL loads publicly without sign-in.
- Android App Bundle uses a unique, increasing version code.
- Complete internal and closed testing requirements applicable to the developer account.
