# MemoSip — App Store Connect Submission Copy

Prepared in English on July 19, 2026. Verify every answer against the exact binary submitted to Apple.

## App Information

- **Name:** MemoSip
- **Subtitle:** Remember Every Sip
- **Primary language:** English (U.S.)
- **Bundle ID:** `com.memosip.app`
- **SKU:** `MEMOSIP-IOS-001`
- **Primary category:** Food & Drink
- **Secondary category:** Social Networking
- **Made for Kids:** No
- **Content rights:** The app displays user-generated content and product/venue references. Confirm **Yes, the app has the necessary rights**; MemoSip's Terms require uploaders to own or have permission for their content.
- **License agreement:** Apple's Standard EULA, supplemented by `https://mustafakuk.github.io/terms/memosip.html`
- **Copyright:** © 2026 Mustafa Kuk
- **Price:** Free
- **In-App Purchases:** None

## URLs

- **Support URL:** `https://mustafakuk.github.io/support/memosip.html`
- **Privacy Policy URL:** `https://mustafakuk.github.io/privacy/memosip.html`
- **User Privacy Choices URL:** `https://mustafakuk.github.io/support/memosip.html#privacy-choices`
- **Terms of Use URL:** `https://mustafakuk.github.io/terms/memosip.html`
- **Community Guidelines URL:** `https://mustafakuk.github.io/community-guidelines/memosip.html`
- **Marketing URL:** Leave blank for version 1.0 unless a dedicated marketing page is published.

## App Store Product Page

### Promotional Text

Rate the drink, not just the place. Build a visual taste journal, discover new favorites, and remember every sip with MemoSip.

### Description

MemoSip is your visual drink journal and taste community.

Rate the drink—not just the venue. Save the coffee, tea, lemonade, cocktail, or any other beverage you tried, remember where you had it, and build a personal taste profile over time.

RECORD EVERY SIP
• Add a photo from your camera or library
• Rate each drink and write tasting notes
• Track sweetness, bitterness, acidity, and intensity
• Save serving size, price, temperature, venue, and time
• Choose Public, Friends, or Only Me for every entry

DISCOVER YOUR TASTE
• Explore drinks shared by the community
• Find new products, brands, and venues
• Build favorites and themed lists
• See your journal, taste profile, and estimated insights
• Revisit the places connected to your favorite drinks

A SAFER COMMUNITY
• Report inappropriate entries
• Block users you do not want to see
• Delete your account and associated data from inside the app

MemoSip has no premium subscription and no live messaging. Nutrition, caffeine, sugar, calorie, and alcohol values may be estimates and are not medical advice.

Remember what you drank. Discover what you love.

### Keywords

`drink diary,coffee,taste tracker,beverage,cafe,ratings,flavor,journal,discover,social`

### What's New

Welcome to MemoSip 1.0. Start your visual drink journal, rate every sip, discover new favorites, and build your personal taste profile.

## Screenshot Order and Captions

Upload real screenshots from the submitted build. Do not place claims in screenshots that are not available in the binary.

1. **Rate the drink, not just the place** — Add-entry or drink-detail screen.
2. **Remember every sip** — Visual journal screen.
3. **Discover your next favorite** — Discovery screen.
4. **Build your taste profile** — Insights screen.
5. **Save the places behind the flavor** — Map screen.
6. **Share on your terms** — Visibility controls or profile screen.

## App Privacy Answers

Select **Yes, we collect data from this app**.

For every data type below: **Linked to the User: Yes**; **Used for Tracking: No**.

| App Store data type | Purpose |
| --- | --- |
| Contact Info → Name | App Functionality |
| Contact Info → Email Address | App Functionality |
| Location → Precise Location | App Functionality; only when the user grants permission and uses venue/map features |
| User Content → Photos or Videos | App Functionality |
| User Content → Other User Content | App Functionality; ratings, notes, profile, lists, reports, and drink details |
| Identifiers → User ID | App Functionality |
| Usage Data → Product Interaction | App Functionality; likes, follows, favorites, blocks, and visibility choices |

Do **not** select advertising data, browsing history, search history, contacts, purchases, financial information, health data, diagnostics, or tracking unless the submitted binary begins collecting them.

## Age Rating Questionnaire

Answer against the current version:

- Parental Controls: No
- Age Assurance: No
- Unrestricted Web Access: No
- User-Generated Content: Yes
- Social Media: Yes
- Social Media Disabled for Users Under 13: No
- Messaging and Chat: No
- Advertising: No
- Alcohol, Tobacco, or Drug Use or References: Frequent (beer, wine, and cocktail categories can appear throughout the app)
- Profanity or Crude Humor: Infrequent or Mild (possible in user-generated notes)
- Health or Wellness Topics: Infrequent or Mild (estimated caffeine, sugar, calorie, and alcohol information with disclaimers)
- Medical or Treatment Information: None
- Gambling, contests, loot boxes, violence, horror, sexual content, nudity, and graphic content: None

Let App Store Connect calculate the final regional age rating from these answers; do not manually promise a specific rating.

## App Review Information

- **First name:** Mustafa
- **Last name:** Kuk
- **Email:** `mstfkuk@gmail.com`
- **Phone:** `[REQUIRED — ADD A PHONE NUMBER WITH COUNTRY CODE]`
- **Sign-in required:** No; reviewers can select **Continue as Guest** on the first screen.
- **Demo account:** Not required for core review because guest access is available.

### Review Notes

MemoSip is a drink journal and user-generated discovery community. Live messaging, subscriptions, in-app purchases, and advertising are not included.

To review the app without an external account, tap "Continue as Guest" on the first screen. Use the plus button to add a drink. Camera and photo-library permissions are requested only when the corresponding photo action is selected. Location permission is optional and is used only for nearby venue or map features.

Each entry supports Public, Friends, or Only Me visibility. Open an entry to access Report Entry and Block User. Account deletion is available at Profile → Settings → Delete My Account and All Data.

Nutrition, caffeine, sugar, calorie, and alcohol figures are estimates and are explicitly presented as non-medical information.

## Export Compliance

- The app uses standard HTTPS/TLS through Apple, Google, and Firebase SDKs.
- It does not implement proprietary or non-exempt encryption.
- Set `ios.config.usesNonExemptEncryption` to `false` in the Expo configuration and answer the App Store export-compliance question consistently.

## Required Account-Level Decisions

These cannot be invented in advance and must be completed by the account holder:

- **App Review phone number:** add a reachable number with country code.
- **Digital Services Act status:** choose Trader or Non-Trader based on your legal/commercial status and provide any requested verification details.
- **Tax and banking:** complete only if Apple requires agreements for your selected distribution or future paid features.
- **Availability:** confirm countries/regions. Suggested starting point: all eligible regions where the content and age rating are appropriate.

## Pre-Submission Verification

- Publish every URL above and confirm it loads publicly over HTTPS.
- Make Privacy Policy and Terms links tappable from the sign-in/settings screens.
- Confirm reports are written to the moderation backend, not only acknowledged in the interface.
- Confirm blocking is enforced for the signed-in account across sessions.
- Verify account deletion removes the Firebase user and associated Firestore records.
- Test Apple Sign-In, Google Sign-In, and guest access on the submitted build.
- Provide screenshots for every required device class shown in App Store Connect.
- Complete the age-rating, content-rights, privacy, encryption, and DSA questionnaires.
- Confirm support email monitoring and a moderation response process before release.
