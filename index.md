# Privacy Policy for Skyline

**Effective date:** September 24, 2026  
**Developer:** Black and Blue

Skyline is an Android planning app for sunrise, sunset, golden-hour, blue-hour, Moon, and local model-forecast conditions. This policy explains what Skyline processes, why it is used, and the choices available to you.

Skyline does not sell personal data, show third-party advertising, or create public profiles.

## 1. Locations and forecast requests {#privacy}

You can choose a place manually or optionally allow Android location access. Skyline uses the selected coordinates to calculate astronomy times on your device and to request local weather forecasts. Place-search text is used to retrieve matching locations.

In the production service, weather coordinates and place-search text travel over encrypted HTTPS through a Black and Blue Cloudflare Worker to Open-Meteo's commercial weather or geocoding service. The Android app does not contain the commercial provider key. Cloudflare and Open-Meteo may process network information such as IP address and standard service logs under their respective terms. Open-Meteo says paid-API request URLs and IP addresses may be logged for usage monitoring, individual logs are removed after 90 days, and aggregate usage counts may remain ([Open-Meteo terms](https://open-meteo.com/en/terms)). Request URLs can contain selected coordinates or place-search text. Skyline does not use location for advertising or continuous background tracking.

Saved locations and app preferences are stored in app-private storage on your device. Android backup and device transfer are disabled for Skyline data.

## 2. Analytics and crash diagnostics

Skyline uses Google Analytics for Firebase to record the app's `app_opened` event; the SDK also automatically records app lifecycle, screen, session, and in-app purchase or subscription events. Firebase Crashlytics receives crash reports and developer-recorded non-fatal diagnostics. These services may process an app-instance identifier, app version, device model, operating-system information, coarse location inferred from network information, app-interaction events, purchase event details such as product ID and price, crash logs, diagnostics, and network information such as IP address.

Skyline's own telemetry calls do not attach selected locations, search text, forecast content, purchase identifiers, or advertising identifiers to analytics or crash events. The Analytics SDK's automatic purchase events may include product identifiers and prices. Advertising-ID collection and ad-personalization signals are disabled, and the Android release removes advertising and AdServices identifier permissions.

## 3. Optional purchases

Skyline may offer monthly or annual Skyline Pro subscriptions. Pro can provide a seven-day model outlook and up to ten usable saved locations. Eligibility, localized prices, billing periods, renewal terms, and trial details, if any, are shown by Google Play before purchase.

Skyline may also offer optional, repeatable **Student Developer Support** purchases at locally displayed store prices corresponding to US $1, $10, and $100 tiers. These purchases support the developer. They do not unlock Pro, create a lasting entitlement, make a charitable donation, or provide a tax deduction. Each eligible purchase can add one local Support Spark for a one-use thank-you celebration.

Google Play processes payment. RevenueCat helps validate purchases and may process purchase history, product and transaction identifiers, an app-user identifier, app/device/operating-system information, and network information such as IP address. Skyline does not receive full payment-card details and does not send selected locations or forecast content to Google Play or RevenueCat.

## 4. Service providers

Skyline uses:

- **Cloudflare** for the production weather and geocoding proxy.
- **Open-Meteo** for commercial weather and geocoding data.
- **Google Firebase** for analytics and crash diagnostics.
- **Google Play** for app distribution and payment processing.
- **RevenueCat** for purchase validation and subscription entitlement state.

These providers may process information in countries other than yours under their own terms. Service traffic uses encrypted HTTPS connections.

## 5. Retention and security

Saved locations, settings, cached forecast data, and Support Spark state remain on the device until removed in Skyline, app storage is cleared, or the app is uninstalled. Provider records are retained under the applicable provider settings, legal obligations, fraud-prevention needs, and policies.

Skyline uses Android app-private storage, disabled Android backup and transfer, server-side protection of the commercial weather credential, minimal provider event data, and encrypted network connections. No storage or transmission method is completely risk-free. Protect access to your device and keep Android security updates current.

## 6. Delete Skyline data {#delete-skyline-data}

Open **Skyline → Settings → Privacy & Local Data → Delete Local Data**, review the warning, and confirm. This removes saved locations, preferences, cached forecast data, local purchase-support state, and pending celebration state from the device.

You can also clear Skyline's storage in Android settings or uninstall the app. These actions do not delete provider purchase, analytics, crash, or service-log records.

For help identifying or deleting provider information that Black and Blue can administer, email **developer@blackandblue.co.in** with the subject **Skyline privacy request**. Include only the minimum locator requested by support. Do not send passwords, payment-card information, authentication links, raw purchase tokens, or precise location history.

## 7. Children

Skyline is a general-audience planning tool and is not directed to children under 13. It contains no advertising, public profiles, chat, or social sharing. A parent or guardian may contact us if they believe information was provided through inappropriate use of the app.

## 8. Forecast and safety disclaimer {#terms}

Weather forecasts and sky-quality scores are estimates, not guarantees. Conditions can change quickly, and confidence generally decreases farther into the future. Skyline is a planning aid, not a weather-warning, emergency, aviation, marine, navigation, health, or safety service. Use official local authorities and qualified services for safety-critical decisions.

Skyline is provided on an “as available” basis. Purchase prices and terms are shown by Google Play before purchase and are subject to Google Play's billing and refund rules.

## 9. Support {#support}

For product help, billing questions, privacy requests, or safety concerns, email **developer@blackandblue.co.in**. Include the app name, app version, Android version, device model, and a concise description when relevant, but do not send secrets or precise location history.

## 10. Changes

We may update this policy when Skyline, its providers, or legal requirements change. The current version will show its effective date. Material changes will be reflected in the app or store listing when appropriate.

## 11. Contact

- **Developer:** Black and Blue
- **Email:** developer@blackandblue.co.in
- **Privacy page:** https://skyline.blackandblue.co.in/

Users in India may send privacy questions or complaints to the email address above. This contact statement does not designate a statutory grievance officer or publish unverified legal or postal details.
