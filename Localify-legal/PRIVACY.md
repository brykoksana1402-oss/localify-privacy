# Privacy Policy

**Effective date:** 2 May 2026
**App:** Localify (macOS)
**Publisher:** Oksana Bryk

This is the privacy policy for Localify, a macOS app for translating iOS app strings and comparing App Store listings. It explains what data the app handles, what leaves your Mac, and what doesn't.

The short version: **Localify does not collect, store, or transmit any personal data about you.** The app runs entirely on your Mac, with no account, no analytics, no telemetry, and no third-party trackers.

If you only read one thing, that's it. The rest of this document explains the details.

---

## 1. Who we are

Localify is built and maintained by Oksana Bryk (the "Publisher"). You can reach the Publisher at **support.ourmap@gmail.com** for any privacy-related questions or requests.

## 2. Data Localify does not collect

Localify does not collect, store, or transmit:

- Your name, email address, or any other personal identifier
- Your Apple ID, iCloud account, or any sign-in credentials
- Your translation source text or translated output
- Your tracked apps, competitor lists, or app metadata
- Your screenshots, brand voice notes, or glossary terms
- Usage analytics, screen views, button taps, or session telemetry
- Crash reports, error logs, or diagnostic data
- IP addresses, device identifiers, or advertising identifiers
- Location data of any kind

There is no Localify account. There is no server you sign into.

## 3. What stays on your Mac

The following data is created by Localify and stored locally on your device only:

- **Tracked apps and competitors** — stored in a SwiftData database in the app's sandbox container
- **Snapshots** — historical metadata fetched from public App Store sources, stored locally
- **String Catalog (`.xcstrings`) edits** — written to the file you opened, on your Mac
- **App Store listing drafts and translations** — held only in memory during a session
- **Brand voice text and glossary** — stored in `UserDefaults` (local app preferences)
- **Onboarding state, theme preference, and other UI settings** — `UserDefaults`

You can erase all of the above at any time via **Settings → Privacy & Data → Clear all tracked apps**, or by deleting the app.

## 4. What leaves your Mac

Localify makes a small number of network requests, all to publicly accessible Apple endpoints, all triggered by your direct actions (adding or refreshing an app, scraping a subtitle):

- **`itunes.apple.com`** — public iTunes Search API. Used to fetch publicly available metadata about an app (title, description, version, ratings, screenshots) by App Store ID. The same data is available to anyone who knows the app's ID.
- **`apps.apple.com`** — public App Store web page. Used to extract the **subtitle** field for an app, which the iTunes Search API does not expose. This is the same content rendered when you visit the app's page in Safari.

These requests **do not include any identifier that ties the request to you personally.** They are equivalent to a regular web browser request.

Localify does not contact any other server. There is no analytics endpoint, no error-reporting endpoint, no third-party SDK that phones home.

## 5. Translation runs on-device

All translation in Localify happens on your Mac:

- **Apple Translate** (Apple's Translation framework) is used for the 19 languages it supports. Models are downloaded by macOS itself, not by Localify, and run on-device.
- **Apple Intelligence** (Apple's Foundation Models framework) is used as a fallback for languages Apple Translate does not cover. It runs on-device on Apple Silicon.

**Your source strings, brand voice, and translated output never leave your device** as part of translation. Apple's frameworks operate locally.

If a future version of Localify adds optional cloud translation models (e.g., DeepL, Anthropic, OpenAI — currently shown as "Coming soon"), they will require you to provide your own API key and will be clearly labelled. Their use will send the relevant text to that provider, governed by that provider's own privacy policy. This will be opt-in only.

## 6. Subscriptions

Pro subscriptions are processed by **Apple's App Store** via StoreKit. The Publisher does not receive your name, email, payment method, or any other Apple ID information.

Apple shares **aggregate, anonymised sales and conversion reports** with the Publisher via App Store Connect — this is standard for every app on the App Store. These reports do not identify individual users.

Apple's own [privacy policy](https://www.apple.com/legal/privacy/) governs your purchase data.

You can manage or cancel your subscription at any time via **System Settings → Apple ID → Subscriptions** on your Mac, or via **Settings → Subscription → Open App Store** inside Localify.

## 7. Children

Localify is a developer tool. It is not directed at children under 13, and the Publisher does not knowingly handle data from children.

## 8. Your rights

Because Localify does not collect or process personal data about you, there is generally nothing for the Publisher to access, correct, or delete on your behalf. All your data lives on your Mac and is under your direct control.

If you are in the **European Economic Area, United Kingdom, or California**, you nonetheless retain the rights granted to you under GDPR, UK GDPR, and the CCPA respectively — including the right to confirm we hold no data about you. Contact **support.ourmap@gmail.com** with any such request.

## 9. Changes to this policy

If this policy changes, the effective date at the top of this document will be updated. Material changes (e.g., adding a third-party service, beginning to collect any data) will be communicated inside the app before the change takes effect.

## 10. Contact

For any privacy-related questions, requests, or concerns:

**support.ourmap@gmail.com**

---

*This policy was last reviewed on 2 May 2026.*
