# Upgrade-Manager-Privacy
Privacy Policy for Upgrade Manager (TestFlight Preview)

_Last Updated: 26th October 2025_

Upgrade Manager is a mobile application created by Luke Allen.
This privacy policy explains how the app handles data for TestFlight users.

---

## Overview

Upgrade Manager connects directly to a user-supplied Jamf Pro environment to view and manage OS upgrades for devices in your Apple estate.

All data displayed in the app is retrieved directly from the user's own Jamf Pro instance; no data is collected, transmitted, or stored by the developer.

---

## Data Collection and Storage

- **Local Data (SwiftData)**
The app stores minimal configuration data (such as server URL and user preferences) locally on the device using Apple's SwiftData framework.

This information never leaves the device and is deleted if the app is removed by the user.

- **Jamf Pro Access**
The app requires users to authenticate with their own Jamf Pro credentials. Once provided, those credentials are stored encrypted in Keychain. The credentials are retrieved and used periodically to generate a Bearer Token which is used to communicate with the user's Jamf Pro server over HTTPS.

The developer of Upgrade Manager has **no access** to any Jamf data or login information.

- **TelemetryDeck Analytics**
Upgrade Manager uses TelemetryDeck to collect anonymous, aggregated usage statistics (e.g., crash frequency, total number of users).

TelemetryDeck does **not** collect any personally identifiable information (PII) or device identifiers.

All analytics data is anonymised before it leaves the device.

Upgrade Manager will **never** use TelemetryDeck to track any information about device data or users of those devices. TelemetryDeck is used purely to communicate the value of the project internally at Jamf.

---

## Data Sharing

Upgrade Manager does **not** share data with any third parties other than TelemetryDeck for anonymous analytics.
No personal, credential, or device information is ever shared with the developer or any external services.

---

## Security

All communication with Jamf Pro occurs over secure HTTPS connections.
No credentials or tokens are stored outside of the user's local device storage.

---

## Contact

If you have any questions about this policy, please contact:
**Luke Allen**
- UpgradeManager@jamf.com

---

© 2025 Luke Allen. All rights reserved.
