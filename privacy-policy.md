# Scam Shield Privacy Policy

Effective date: 24 October 2026

App: Scam Shield · Android package: `com.scamshield.probe`

Privacy contact: [friendlink00@gmail.com](mailto:friendlink00@gmail.com)

## 1. About this policy

This policy explains how the developer of Scam Shield handles information in the current public Android app and on this privacy-policy website. It covers manual number and link checks, supported Android call screening, locally saved evidence, family tools, and optional settings.

The current public app processes information on your device. It does not have Android's Internet permission and does not automatically upload your contacts, numbers, links, notes, pictures, recordings, or call-screening history to the developer. This does not mean the app never accesses personal information: the local processing and the actions you choose are described below.

## 2. Information used on your device

**Number and link checks.** When you type a number, paste a link, or explicitly share text to Scam Shield, the app processes that input locally to display number details or inspect the link for visible warning signs. The link checker does not visit the link or follow redirects. These checks do not establish a caller's identity or guarantee that a number or website is safe. Check inputs are not automatically uploaded or saved as reports; saving a report or rule is a separate action.

**Contacts.** If you grant Contacts permission, the app can look up whether a supplied or supported incoming number matches your contacts and display a matching contact name. Matching contact names are used locally and are not copied into the app's call-screening history or uploaded. The app does not publish your address book or share it with a community service. Information you separately type into a family entry, report, or note is saved when you choose to save it.

**Call screening.** If you select Scam Shield for Android's caller-ID/spam or call-screening role, Android may provide supported call details, such as the presented number or hidden-number status, time, direction, and other screening information. The app uses these details with local rules and available contact checks to determine a screening response. It does not invent a number for a hidden caller. Locally stored screening history contains masked numbers where available, timestamps, contact-match categories, screening responses, reasons, and timing information, rather than contact names or complete caller numbers. Full numbers are retained separately only when you explicitly save them in a rule, report, or another local feature. The public app does not request permission to read the phone's general call-log database.

**Reports, notes, and pictures.** You can explicitly save report drafts, phone numbers, categories, case notes, event dates, and selected pictures. These remain local drafts and are not automatically submitted to the developer, police, a community database, or any online reporting service. Selected pictures are resized and re-encoded; original filenames, source URIs, and EXIF metadata are not retained in the case record. Information visible within a picture is not automatically redacted. Only include information you are entitled to store.

**Imported audio.** If you select an existing audio file through Android's file picker, the app copies it into its private recording library and can play it locally. The public app does not request microphone permission, record live cellular or internet calls, transcribe audio, or upload recordings. Importing or deleting the app's copy does not modify the original file. The library currently supports up to 20 audio copies, each up to 100 MB.

**Family tools.** Names, phone numbers, reminder frequencies, manually recorded contact dates, trusted-person numbers, and safety instructions are stored locally when you add or save them. Selecting Call or WhatsApp can also mark a local contact date; this is an app interaction record, not evidence that a call connected or a message was delivered. The app does not monitor conversations, track relatives' locations, or send live family alerts in the current public version.

**Preferences and diagnostics.** The app stores local preferences, such as Senior Mode, theme, motion, notifications, and call-screening settings. It keeps a local crash counter and operational status information for troubleshooting. It does not automatically send crash reports, usage analytics, advertising identifiers, IMEI, or a contact database to the developer. Device model and Android version may be displayed locally in About or diagnostic screens.

## 3. Permissions and optional background features

- **Contacts:** optional local contact matching. You can decline or revoke it; contact-related results may then be unavailable.
- **Android call-screening role:** enables Android to route supported screening callbacks to the app. You control this role in Android settings. It is separate from Contacts permission.
- **Notifications:** optional reminders and call-related or service notifications. Reminder notifications may include names you saved and can appear on your lock screen according to your Android notification settings.
- **Display over other apps:** optional floating shortcut for manual number and link checks. It does not read other apps' messages, extract numbers from their screens, capture their screens, or record their audio.
- **Foreground service:** keeps the user-started floating shortcut visible with an ongoing notification. You can stop it from its Stop control or Android settings. The shortcut stops when the screen turns off.
- **Receive boot completed:** lets the app re-schedule enabled local family reminders after the device restarts.
- **Selected-file access:** Android's picker lets you choose individual audio files or pictures. The public app does not request unrestricted storage, location, camera, SMS, Accessibility Service, or microphone access.

You can manage permissions in Android Settings → Apps → Scam Shield → Permissions. Turning off an optional permission or role may disable the feature that needs it.

## 4. Sharing and services you choose

The developer does not sell, rent, or automatically disclose your on-device app data. There is no active advertising SDK, remote analytics service, cloud synchronization, public account service, or in-app payment service in the current public version.

When you select an available Share, Print, Call, WhatsApp, or similar action, Android passes the information needed for that action to the app or service you choose. For example, opening the dialer provides the chosen telephone number; opening a WhatsApp link includes the selected number in that link. That app or service may use the Internet and handles the information under its own policy. Review the content and destination before proceeding.

If you generate a keypad-phone safety card, it is saved to shared device media, such as Pictures/Scam Shield, so that you can print or share it. The card can contain a trusted telephone number and safety instructions. Your gallery, sharing apps, or backup provider may then handle that file independently of Scam Shield.

Read-aloud features pass built-in safety phrases to the text-to-speech engine configured on your device. That engine's operation and any voice downloads are governed by its provider and your device settings. Scam Shield does not use the microphone for this feature.

Android, Google Play, device manufacturers, file providers, email providers, and apps you explicitly open may process information under their own privacy policies. This policy describes Scam Shield's handling, not those providers' independent practices.

## 5. Storage and security

App records are kept in Android app-private storage. Saved local rules, report drafts, case records, family entries, and family safety plans use app-level AES-GCM encryption with keys managed through Android Keystore. Imported audio, masked call-history records, preferences, and the crash counter are not all additionally encrypted by the app; they rely on Android's application isolation and the device's security protections.

The app disables Android's standard automatic app backup. Files you explicitly save outside app-private storage, including generated safety cards and original media, may still be backed up by other apps or your device provider. Keep your device protected and review those providers' settings. No storage or security measure can guarantee absolute protection.

## 6. Retention and deletion

Local rules, reports, notes, pictures, imported audio, family entries, plans, and preferences remain on the device until you remove them through the relevant feature, clear app storage, or uninstall the app. The app applies storage and item limits; call-screening history retains up to the most recent 1,000 entries and a separate bounded operational call log retains up to 100 recent events. Older entries can be removed when these limits are reached. Temporary files from interrupted imports or saves may be cleaned up by the app.

You can delete report drafts and cases in Evidence, remove audio copies in Recordings, remove family reminder entries, delete a saved family safety plan, manage blocked-number rules in Call protection, and clear the app's call history from Evidence. Exact Android menu names can vary by device.

To remove all locally stored app data, use Android Settings → Apps → Scam Shield → Storage → Clear storage, or uninstall Scam Shield. This does not erase your phone's own contacts or call log, original imported files, files saved to shared media, exported or shared copies, or records held by other providers. Delete those separately where appropriate. Storage removal is not a guarantee of forensic secure erasure.

The developer cannot remotely access or delete your local app data because the current app has no developer-operated data server or online account service. No online account deletion is needed to use these local features.

## 7. Support messages and privacy requests

If you email [friendlink00@gmail.com](mailto:friendlink00@gmail.com), the developer receives the email address, message, and attachments you choose to send. They are used to respond, investigate the issue, and handle your request. Email providers also process that correspondence. Do not send passwords, OTPs, PINs, full recordings, contact lists, or private screenshots unless they are necessary for the request.

Support correspondence is retained only as reasonably needed to handle the request, related support records, and applicable legal obligations. You can contact the same address to request access, correction, or deletion of information you have sent to the developer. Where applicable, you may also exercise other privacy rights available under your local law. For data stored only in the app, use the local deletion controls described above.

## 8. This policy website

This page is hosted on GitHub Pages. When you visit it, GitHub may receive technical request information, such as your IP address, browser information, and request logs, as described in the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

The page itself adds no analytics scripts, advertising, cookies, tracking pixels, external fonts, or contact-form trackers. Clicking the email link opens your email app. Contacting support is optional and separate from using Scam Shield.

## 9. Children and family information

The current app does not operate an online account or social service and does not knowingly request children's personal information for a developer-operated online service. Family information entered on a device is handled locally as described above. A parent or guardian should supervise a child's use of the app and avoid adding unnecessary sensitive information. If you believe a child has sent personal information to the support address, contact us so we can review and remove it where appropriate.

## 10. Changes to this policy

We will update this page and its effective date when the app's data handling changes. If online services, recording features, accounts, payments, or other materially different processing are introduced into the public app, the policy and relevant in-app disclosures will be updated before those services are enabled, and any required consent will be requested. Planned or internal prototype features are not active public services described by this policy.

## 11. Contact

For privacy questions, support, or requests about information you have sent us, contact the developer at [friendlink00@gmail.com](mailto:friendlink00@gmail.com). Please include “Scam Shield” in the subject and describe your request without unnecessary personal information.
