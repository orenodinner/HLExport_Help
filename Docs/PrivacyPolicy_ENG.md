## Privacy Policy

**Last updated: May 6, 2025**

This Privacy Policy (hereinafter, “Policy”) explains what user information the developer **oreno\_dinner** (“we,” “us,” or “our”) collects when you use the application **“HLExport”** (“the App”), and how that information is used and managed. Please read this Policy carefully before installing or using the App.

---

### 1. Information We Collect

| Category                  | Details                                                                                        | How It Is Collected                                                          |
| ------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **Health Data**           | All records stored in Apple HealthKit, including steps, heart rate, sleep, active energy, etc. | Only when the user taps a button and explicitly starts the retrieval process |
| **Mood Entries**          | The user‑entered 7‑level mood value                                                            | When the user enters it on screen                                            |
| **Notification Settings** | Notification time and whether the daily reminder is enabled                                    | When the user registers or updates settings                                  |
| **Debug Logs (optional)** | Diagnostic information about in‑app processes                                                  | Only when the user enables log display in a DEBUG build                      |

> **We do not collect location data, advertising identifiers, contacts, or other personally identifying information.**

---

### 2. Purpose of Use

1. For Health data and Mood entries:

   * Conversion to JSON or plain text and local storage on the device
   * Transfer to external apps or cloud services via the iOS share sheet (only when initiated by the user)
2. Sending daily reminder notifications
3. Displaying debug logs and improving app quality (DEBUG builds only)

---

### 3. Storage and Third‑Party Disclosure

* **On‑device processing**
  All collected data is processed and stored solely on the user’s device. It is never sent automatically to us or any third‑party server.
* **Share sheet transfer**
  Data files are sent to the destination app only when the user taps a share button and selects an app in the iOS share sheet.
* **No third‑party provision**
  We will not provide user information to third parties except when required by law.

---

### 4. Data Retention

| Data                                 | Storage Location                  | Retention / Deletion                                                              |
| ------------------------------------ | --------------------------------- | --------------------------------------------------------------------------------- |
| Converted files (JSON/TXT)           | Temporary directory on the device | May be automatically deleted after sharing is complete or when the app terminates |
| Mood entries                         | Local database of the App         | Retained until the user deletes them within the App or uninstalls the App         |
| Notification settings & default days | UserDefaults                      | Retained until the user changes the setting or uninstalls the App                 |

---

### 5. Security

* Data is handled in an encrypted and protected state using Apple’s **HealthKit** and **Secure Enclave**.
* By design, the App performs no external communications, minimizing the risk of data leakage over a network.

---

### 6. User Rights

* **Access rights**: You can change Health data read/write permissions at any time under **iOS Settings > Privacy & Security > Health**.
* **Notification permissions**: You can modify or revoke them at any time under **iOS Settings > Notifications**.
* **Data deletion**: Uninstalling the App removes all App data stored on the device.

---

### 7. Use by Minors

The App is not intended for children under 13 years of age, and we do not knowingly collect personal information from anyone in that age group.

---

### 8. Changes to This Privacy Policy

We may revise this Policy due to legal changes or feature additions. If significant changes occur, we will notify you within the App or via release notes in the GitHub repository.

---

### 9. Contact

For questions or requests, please contact us at:

* GitHub Issues: [https://github.com/oreno-dinner/HLExport/issues](https://github.com/oreno-dinner/HLExport/issues)

---

If you do not agree with this Policy, please discontinue using the App and delete it from your device.
