# Privacy Policy — Cronada

**Last updated:** October 1, 2026

## Introduction

Cronada ("the App") is developed by EgeaINC. This Privacy Policy explains how we handle information when you use our App.

## Your Data Stays on Your Device

**EgeaINC does not collect, store, or receive your swimmers, times, or any other content you create in the App.** It is stored only on your device.

The App stores the following data **locally on your device only**:
- **Swimmers:** Names, levels, and notes of the swimmers you register (stored in a local SQLite database)
- **Groups:** Swimmer group assignments
- **Sessions:** Training and competition timing records, with times and splits
- **Pools:** Pool configurations you create
- **Running timers:** The state of the timers while they run, so they can be recovered if the App is closed
- **Preferences:** App settings like language, theme, sound, vibration, and calculator values (stored in SharedPreferences)

This data never leaves your device unless you export or share it yourself, and it is deleted when you uninstall the App.

## Advertising

The free version of the App shows ads provided by **Google AdMob**. Users with Cronada Pro do not see ads, and the App does not start the ads service for them. Ads are never shown on the stopwatch screen.

To show and measure ads, Google AdMob may collect and process:
- The device's advertising ID
- Approximate location derived from the IP address
- Device and app information (model, operating system, language, app version)
- Ad interactions (impressions and taps)

This data is collected and processed by Google under its own policies, not by EgeaINC. Your swimmers, times, and sessions are never shared with AdMob.

- How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy

**Your choices:**
- You can reset or delete your advertising ID, or opt out of personalized ads, in your device settings (Settings → Google → Ads, or Settings → Privacy → Ads, depending on the device).
- In the European Economic Area, the United Kingdom and Switzerland, the App asks for your consent before showing personalized ads, and you can change your choice at any time in Settings → Ad privacy.
- Cronada Pro, a one-time purchase, removes all ads.

## Sharing (Always Initiated by You)

1. **Export PDF/CSV:** You can export session results as PDF or CSV files. They are generated on your device and shared only through the method you choose (WhatsApp, email, etc.).
2. **Share swimmers:** You can share swimmers with another coach through a link. The swimmers' data (names, levels, and notes) travels inside the link, in the part after the "#" sign, which browsers do not send to the server. The page that opens the link (hosted on GitHub Pages) only passes it on to the App on the receiving phone; neither GitHub nor EgeaINC receives it. Whoever gets the link can see what you shared.

## Notifications

While timers are running, the App shows a notification with the time of each lane, so you can see it with the App in the background or the phone locked. It is shown only on your device.

## Internet Usage

The App connects to the internet for:

1. **In-app purchases:** Processed entirely through Google Play Billing. When the App opens, it asks Google Play whether you own Cronada Pro, so a reinstall or a new phone keeps it. We do not have access to your payment information. Google's privacy policy applies to these transactions.
2. **Ads (free version only):** Loading ads from Google AdMob, as described above.
3. **Updates:** Checking Google Play for a newer version of the App.

## Permissions

The App requests the following Android permissions:
- **Internet:** Required for in-app purchases, ads in the free version, and update checks.
- **Notifications:** Used to show the running timers in the notification shade.
- **Foreground service:** Required to keep the timers running accurately when the screen is off or the App is in the background.
- **Vibration:** Used for haptic feedback on the timer buttons (can be disabled in settings).
- **Advertising ID:** Used by Google AdMob to show ads in the free version.

## Children's Privacy

The App is intended for swim coaches and teachers, not for children, and it does not knowingly collect information from children. Coaches may register the names of the swimmers they train, which may include minors; this data is stored only on the coach's device and is never sent to EgeaINC or to AdMob.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Privacy Policy, please open an issue at:
https://github.com/gabriel600r/cronada-feedback/issues

---

*Cronada — Cronómetro de Natación by EgeaINC*
