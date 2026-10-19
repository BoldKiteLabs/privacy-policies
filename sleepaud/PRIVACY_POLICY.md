# Privacy Policy for SleepAud

*Last updated: October 2026*

SleepAud, created by BoldKiteLabs ("we", "our", or "the app"), is committed to respecting and protecting user privacy. SleepAud is designed as a distraction-free, privacy-preserving sleep podcast player.

Public Policy URL: [https://boldkitelabs.github.io/privacy-policies/sleepaud/](https://boldkitelabs.github.io/privacy-policies/sleepaud/)

---

### 1. Information Collection & Usage

**SleepAud does not collect, record, or store personal data on any server operated by us.**

- **No User Accounts**: You do not need to register, log in, or provide an email address or credentials to use SleepAud.
- **No Third-Party Analytics**: The app does not include analytics SDKs (e.g. Firebase Analytics, Google Analytics), behavioral profiling, or crash telemetry libraries.
- **No Advertising Trackers**: The application contains no advertising SDKs, cross-app tracking identifiers, or Google Advertising IDs (AAID).

---

### 2. Device Storage & Local Data

All user data configured within SleepAud is stored strictly locally on your Android device:
- **Podcast Subscriptions & Preferences**: Stored locally in your device's private app sandbox (`SharedPreferences`).
- **Audio Cache**: Downloaded audio files are stored in your device's internal app cache directory and can be removed at any time via the "Clear Cache" button within the app.
- **No Cloud Sync**: Your subscriptions and listening progress never leave your device.

---

### 3. Third-Party Network Requests & External Feeds

SleepAud transmits network requests strictly over encrypted HTTPS initiated by user actions:

- **Apple iTunes Search API**: When you perform a search, your search query is sent directly to Apple's iTunes Search API (`https://itunes.apple.com/search`) to locate matching podcast titles and feeds.
- **Podcast RSS Hosts & Audio CDNs**: When subscribing, refreshing feeds, or streaming/downloading episodes, your device connects directly to the respective podcast publisher's RSS hosting server or audio CDN.
- **Technical Connection Details**: Connecting to Apple or third-party podcast servers inherently transmits standard HTTP request headers, which include your device's IP address and the app's User-Agent string (`SleepAud/1.0`). We do not host intermediate proxy servers, and we never collect, intercept, or log this traffic. Third-party audio hosts and Apple operate under their own independent privacy policies.

---

### 4. Device Permissions

SleepAud requests only the minimal permissions required for core audio playback functionality:
- `android.permission.INTERNET`: Required to fetch public podcast RSS feeds, query search results, and stream/download audio episodes.
- `android.permission.ACCESS_NETWORK_STATE`: Checks active network connectivity before initiating streaming requests.
- `android.permission.FOREGROUND_SERVICE` & `android.permission.FOREGROUND_SERVICE_MEDIA_PLAYBACK`: Required to keep audio playback active in the background while your screen is off or while you are asleep.
- `android.permission.WAKE_LOCK`: Ensures the device CPU remains awake for uninterrupted audio decoding when the screen turns off.
- `android.permission.POST_NOTIFICATIONS` (Android 13+): Displays standard Android media playback controls (Play, Pause, Skip, Episode Title) in your system notification drawer and lock screen.

---

### 5. Children's Privacy

SleepAud does not collect any personal data from anyone, including children under the age of 13. Because podcasts are sourced from third-party RSS feeds that may contain adult language or content, SleepAud is directed to users aged 13 and older.

---

### 6. Changes to This Privacy Policy

If this Privacy Policy is updated, the revised version will be published at our public policy URL with an updated revision date.

---

### 7. Contact Us

If you have questions, feedback, or inquiries regarding this Privacy Policy or data privacy in SleepAud, please contact us at:
- **Email**: `boldkitelabs@proton.me`
- **GitHub Issues**: [https://github.com/BoldKiteLabs/privacy-policies/issues](https://github.com/BoldKiteLabs/privacy-policies/issues)
