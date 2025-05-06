# HLExport — User Guide  
*Last updated: 2025‑05‑06*

---

## 0. Permissions
| Preparation | Details |
|-------------|---------|
| **Health access** | When the app first launches, allow all *read* permissions in the dialog that appears. If you want to record **State of Mind** on iOS 18 or later, also allow *write* access. |
| **Notification access** | Grant permission if you’d like daily reminders for mood entry. You can change this later in **Settings > Notifications**. |

---

## 1. Retrieving Health data on the main screen
1. **Specify a date range**  
   - Set the *Start Date* and *End Date*.  
   - Changing the range automatically saves the number of days, which becomes the default next time you launch the app.
2. Tap **Share Health data (raw)** or **Retrieve Health data**  
   - A progress bar appears and the button is grayed out while loading.  
   - To cancel, tap **Cancel Data Retrieval**.
3. Actions available after data retrieval  
   | Button | Action |
   |--------|--------|
   | **Share JSON data** | Creates a JSON file and opens the share sheet. |
   | **Copy JSON data to clipboard** | Copies the JSON directly to the clipboard. |
   | **Cancel** buttons during each process | Interrupts conversion or copy in progress. |

> **Tip:** If no data has been retrieved, the share buttons are automatically disabled.

---

## 2. Recording your current mood
1. On the main screen, tap **Record your current mood**.  
2. Choose your current mood from the 7‑level list and tap **Save**.  

---

## 3. Setting and deleting the daily reminder
### Set
1. In **Settings**, open the *Daily Record Reminder* section.  
2. Select a time under **Notification Time**.  
3. Tap **Set a notification at this time**.  
   - A success message appears and the time is saved.

### Delete
1. In the same section, tap **Delete Notification Setting**.  
2. All scheduled notifications and the saved time are removed.

---

## 4. Changing the default retrieval period
1. In **Settings**, open the *Health data retrieval range* section.  
2. Enter the number of days in the text field.  
   - Entering fewer than 0 or more than 739 374 days (equivalent to BCE) triggers a warning and reverts the value.  
3. The value is saved automatically and becomes the initial range on the main screen.

---

## 5. Viewing the debug log
1. At the bottom of the main screen, turn **Show Debug Log** ON in the *Debug Log* section.  
2. Internal logs for data retrieval and sharing appear in real time.  
3. Tap **Clear Debug Log** to reset the log.  
   - Displaying many logs can slow processing.

---

## 6. Frequently Asked Questions (FAQ)

| Question | Answer |
|----------|--------|
| **I denied the permission dialog by mistake.** | Re‑enable it in **Settings > Privacy & Security > Health > HLExport**. |
| **I see “Cannot write current mood.”** | Writing State of Mind is not available on iOS versions earlier than 18. |
| **An error appears when I select a very large date range.** | You may exceed the iOS sample limit. Split the range and retrieve in parts. |
| **My file disappears after sharing JSON.** | If you don’t pick a destination app in the share sheet, the temporary directory is deleted. Share again and save to Files or a cloud service. |
| **I’m not receiving notifications.** | Check notification permissions and Focus mode. Deleting and re‑adding the reminder often fixes the issue. |

---

## 7. Troubleshooting

| Symptom | Solution |
|---------|----------|
| **“Health access has not been granted.”** | A *Grant access to Health* button appears on the main screen. Tap it to request permissions again. |
| **“Processing…” alert keeps showing.** | Another task (conversion, copy, etc.) is running. Wait for it to finish or cancel before retrying. |
| **The app seems frozen.** | Turn the debug log ON to view progress. Processing may slow in Low Power Mode. |


[PrivacyPolicy](PrivacyPolicy_ENG)