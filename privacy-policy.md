# Privacy Policy for Hindu Calendar

**Effective Date: March 17, 2026**

Thank you for choosing to use the Hindu Calendar app ("App"), developed by ishubhamx ("Developer," "we," "us," or "our"). We are committed to protecting your personal information and your right to privacy.

This Privacy Policy explains what information we collect, how we use it, and what rights you have in relation to it when you use our mobile application.

## 1. Information We Collect

### A. Information You Provide to Us
The App primarily functions as an offline astronomical and astrological calculator. We do not require you to create an account, nor do we ask for personal identifiers like your name, email address, or phone number to use the core features of the App.

### B. Location Information
To calculate accurate Panchang (Hindu astronomical calendar) timings such as Tithi, Nakshatra, Yoga, Karana, and Sunrise/Sunset times for your specific area, the App requires access to your device's location.
*   **How it is used:** Your location data (latitude and longitude) is processed locally on your device using the `@ishubhamx/panchangam-js` library.
*   **Storage:** Your selected or detected location coordinates and name are stored locally on your device.
*   **Limited transmission for online features:** When you use optional online features (such as backend-generated insights content), date, language, and approximate location coordinates are sent to our backend (Firebase Functions) to generate and return those results.

### C. Automatically Collected Information (Analytics & Crashlytics)
To improve the performance and user experience of our App, we use third-party services provided by Google Firebase:
*   **Firebase Analytics:** We may collect anonymous usage data, such as screens visited, features interacted with, device type, operating system version, and approximate geographic region (not precise location). This helps us understand how the app is used.
*   **Firebase Crashlytics:** If the App crashes, we automatically collect crash reports. These reports contain diagnostic information about the crash, including device state at the time of the error, which helps us identify and fix bugs.

### D. Notifications (Push & Local Scheduled)
The App uses two types of notifications:

**Push Notifications (Firebase Cloud Messaging):**
*   **FCM Token:** Your device's FCM token and an app-generated device identifier are transmitted to our backend and stored in Firebase Firestore to enable push delivery.
*   **Usage:** These identifiers are used only for sending app notifications and maintaining notification delivery.
*   **Permissions:** Push notifications are optional and controlled by your device/app notification settings.

**Local Scheduled Notifications (On-Device):**
*   The App schedules time-based reminders locally on your device for events such as Hindu festivals, special tithis, and inauspicious periods (Rahu Kaal, Yamaganda, Gulika Kalam). This scheduling is performed entirely on-device using Android's AlarmManager or the equivalent iOS API — no data is sent to our servers for this purpose.
*   **`SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` (Android):** On Android 12 and above, the App requests the special "Alarms & Reminders" permission to fire these notifications at exact times (e.g., precisely when Rahu Kaal begins). This permission is used solely to trigger on-device reminders and does not provide us access to any personal data.
*   **`RECEIVE_BOOT_COMPLETED` (Android):** The App listens for the device boot event solely to reschedule any local notifications that were cleared when the device restarted. No personal data is collected or transmitted as part of this process.
*   All local notification preferences (which types of alerts you enable) are stored locally on your device only.

*Please note: Data collected by Google Firebase is subject to [Google's Privacy Policy](https://policies.google.com/privacy).*

## 2. How We Use Your Information

We use the minimal information collected or generated for the following purposes:
*   To provide and maintain the App's core functionality (accurate Panchang calculations based on your location).
*   To provide optional backend-generated content (such as dynamic insights).
*   To identify and fix technical issues and bugs (via Crashlytics).
*   To analyze user trends and improve the overall user experience (via Analytics).
*   To deliver push notifications to opted-in devices.
*   To schedule and fire local on-device reminders for festivals, tithis, and inauspicious periods based on your notification preferences.

## 3. How We Share Your Information

We **do not** sell, trade, or rent your personal information to third parties.

We only share information with third-party service providers (like Google Firebase) for the purposes described in this policy, including analytics, crash reporting, backend feature processing, and push notification delivery. These providers are bound by their own privacy policies.

## 4. Third-Party Services

The App may contain links to third-party websites or services (e.g., in the Settings screen or About section). We are not responsible for the privacy practices or the content of these third-party sites. We encourage you to read their privacy policies.

## 5. Security of Your Information

We prioritize the security of your data. The core astrological calculations are primarily performed on-device, and optional online features are processed through secured cloud infrastructure. While no method of transmission over the internet or method of electronic storage is 100% secure, we strive to use commercially acceptable means to protect data handled through our third-party providers.

## 6. Children's Privacy

Our App does not purposefully collect personal information from children under the age of 13. If you are a parent or guardian and believe your child has provided us with personal information (which the app does not inherently ask for), please contact us, and we will take necessary actions.

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. You are advised to review this Privacy Policy periodically for any changes.

## 8. Contact Us

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at:

**Developer:** ishubhamx
**Email:** [Insert Developer Email Here]
**GitHub:** [github.com/ishubhamx](https://github.com/ishubhamx)
