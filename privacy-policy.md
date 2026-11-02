# Oh, My Bills! Privacy Policy

**Last updated:** 2 November 2026

Oh, My Bills! is an offline-first bill and expense planning application. It does not require an account or login, provide a bank connection, or operate an advertising or behavioural analytics service. Core bill planning and file analysis are designed to run on your device.

## Data stored on your device

The app locally stores information needed for its features, including bills and expenses, recurring schedules, preferences, saved financial outlooks, and Bill Assistant matching records.

Local matching records may include a salted opaque account scope, transaction fingerprint, merchant name or normalized key, payment amount, date, currency, status, confirmed matches, and the most recent payment check. Account labels or merchant descriptions might contain personal information depending on what is included in the imported file.

**Unfinished reviews may also remain on your device between sessions.** Recurring-bill discovery can save suggested merchants, observed months, amounts, and normalized payment evidence while you review them. Missing-bill or payment reviews can save merchant descriptions, amounts, dates, payment evidence, and your review choices. This allows an unfinished review to be resumed. Such information is not limited to confirmed bill fields.

Financial information is stored in the app's local storage under the protections offered by your device operating system. The app does not currently provide a separate app-level encryption layer for all locally saved financial records. Whether local app data is included in device backups depends on your platform and backup configuration; OMB does not run its own cloud backup or financial-data synchronization service.

## Bank CSV imports and local processing

Bill Assistant reads a bank CSV only after you choose it. Historical DBS/POSB exports help suggest recurring bills; current-month exports can suggest matches for unpaid bills. Other supported CSV imports can add bills, recurring schedules, or history after your review.

The app processes the selected CSV on the device and does not intentionally keep the original source file or its unparsed CSV rows as an archive. **Normalized payment and merchant details may be retained in unfinished reviews and matching records**, as described above. The app does not intentionally store full bank account numbers or account balances from these imports in Bill Assistant matching records.

File pickers may first copy selected files into the app's temporary cache. The app attempts to delete app-owned picker copies after processing, including when an import is cancelled or fails. Cleanup is best-effort; device caches and previously created temporary copies may persist until cleaned or reclaimed by the operating system. The app never deliberately deletes the original document you selected.

## Screenshot scanning

Selected bill or subscription screenshots are analysed on the device using Google ML Kit Text Recognition. The text-recognition API does not send selected screenshot images or recognized text to Google or an Oh, My Bills! server for recognition. Images and OCR text are used for the review flow rather than intentionally saved as screenshots or OCR transcripts by OMB. Picker-created temporary copies are subject to best-effort local cleanup.

The Google ML Kit SDK may separately transmit operational information to Google, such as app and device information, per-installation identifiers, performance, API configuration, input/output sizes, events, or errors. Those operational metrics are distinct from the screenshot content and recognized text. See [ML Kit's Android disclosure](https://developers.google.com/ml-kit/android-data-disclosure) and [iOS disclosure](https://developers.google.com/ml-kit/ios-data-disclosure).

Screenshots are not proof that a payment has settled. Any suggested bill or payment change requires your review.

## Review and user control

The app does not automatically mark a bill as paid, settle a payment, create a bill from a bank statement, or change a recurring schedule solely because it found a possible match. You choose whether to add, map, ignore, or otherwise confirm suggested items. You can edit or remove records through the app's available controls.

You can clear local app data through your device settings or by uninstalling the app, subject to any copies or backups retained separately by the device operating system or your chosen export destination.

## Notifications

If you enable bill reminders, OMB schedules local notifications using your device's operating system. Notification content can include a bill name and may be visible on the lock screen depending on your device settings. OMB does not operate a server for delivering these notifications.

## Import, export, and sharing

Files are accessed when you choose to import or export them. When you export a CSV or PDF, the app may create a temporary local file so your device can pass it to the share sheet or a destination you choose. App-owned temporary copies are kept in operating-system-managed cache where supported; generated print files are cleaned on a best-effort basis when no longer needed. A shared temporary file may remain in cache until the operating system reclaims it, to avoid interrupting the receiving app.

If you explicitly save or share an export with another app, a cloud drive, email, messaging service, or another recipient, that destination may receive and store its contents under its own policies. OMB does not select an external recipient or upload financial records to an OMB-operated server.

## Updates and platform services

OMB may contact Expo update services to check for or download software updates, GitHub-hosted release-version information, and Apple or Google platform update services, as applicable. These requests can disclose technical information such as the device's network address and software context to the relevant service; they are not designed to include the user's saved bills or bank transaction records.

The operating system, distribution stores, and third-party platform SDKs may process limited operational information under their respective policies. This means **offline-first does not mean the app generates no network traffic**. Core financial processing is designed to work offline; app updates and certain external services require connectivity.

## Financial disclaimer

The app provides informational financial planning estimates. It does not provide financial or banking advice.

## Contact

For privacy questions regarding Oh, My Bills!, contact support@alwikigai.com.
