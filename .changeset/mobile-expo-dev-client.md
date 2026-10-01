---
"@e2e-dev/mobile": minor
---

`mobile({ expoDevClient: 'http://localhost:8081' })` runs an Expo development build on an iOS simulator: every fresh launch of the pinned app loads that dev server instead of the dev launcher, with the dev menu, its onboarding sheet, and its floating action button off, so nothing covers the app. A value that is not an http(s) URL, or the option on Android, is `INVALID_CONFIG`.
