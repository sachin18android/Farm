# Kisan Crop Manager (Android MVP)

A native Android starter app for managing a personal vegetable farm. The project is designed around local-first storage.

## Included in this starter
- Kotlin + Jetpack Compose UI
- Room database for farms, plots, crop cycles, expenses, activities, and labour entries
- Dashboard with active crop count and investment totals
- Create farms, plots, crop cycles, expenses, activities, and labour entries
- Crop investment and cost-per-acre calculations
- Hindi/Hinglish speech-to-text draft entry (Android speech recognition)
- Bill image selection and OCR draft extraction using ML Kit
- Basic task list and report views

## Important limitations
This is an MVP starter, not yet a fully verified production release. The environment used to prepare this source did not contain the Android SDK or Gradle, so an APK could not be built or instrumented here. Open it in Android Studio, sync Gradle, build, and run on a device to validate it.

- OCR is best-effort text extraction. It does not reliably infer every bill field; always review before saving.
- Speech recognition availability/offline behavior depends on the Android device and installed speech services.
- Backup/restore is not implemented in this first source drop and is a required next milestone.
- Full inventory valuation, multiple-product spray sessions, complete sales ledger, cloud sync, and advanced reminder scheduling are planned follow-ups.
- Expense and crop-cost accounting in this MVP counts saved expense records as incurred cost; payments/outstanding are represented as separate fields and not added again to cost.

## Build
1. Install Android Studio with Android SDK Platform 35 and a compatible JDK (17).
2. Open this folder in Android Studio.
3. Allow Gradle sync and dependency downloads.
4. Run the `app` configuration on an Android device/emulator (Android 8.0 / API 26 or newer).

Package: `com.kisancropmanager`
