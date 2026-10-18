# Chhintang Workshop Manager

Android app source for **छिन्ताङ्ग ग्रिल तथा आल्मुनियम वर्क-सप**, धरान–५.

## Features
- Dashboard: recorded income, expenses, cash flow and customer dues
- Project records and agreement amounts
- Transactions linked to projects
- Worker list, attendance and advance/payment records
- Customer ledger
- Quotation estimator
- Report print / Save as PDF, CSV export, JSON backup and restore
- Local storage; works offline after install

## Build APK on GitHub (phone-friendly)
1. Create/open your GitHub repository.
2. Upload all files/folders from this project to the repository root (including `.github/workflows/build-apk.yml`).
3. Open **Actions** tab and select **Build Chhintang Workshop APK**.
4. Tap **Run workflow** (if it did not start automatically after commit).
5. When the workflow succeeds, open the run and download the artifact named `Chhintang-Workshop-Manager-APK`.
6. Extract the downloaded ZIP; install `app-debug.apk` on your Android phone. If Android blocks it, allow installation from that browser/file manager when prompted.

## Important
- This is a debug APK for personal/internal use, not a Play Store release.
- Data stays on the phone. Export JSON backup regularly. Clearing app data or uninstalling can erase records.
- Income/expense cash flow is not the same as audited net profit. Project material/labour costs must be recorded accurately.
- Update the company spelling, proprietor spelling, PAN and registration details if needed before official use.
