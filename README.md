# ShiftFlow — Shift & Income Tracker

An iOS app for hourly workers to log shifts, track earnings, and manage their work schedule with iCloud sync across devices.

<!-- <p align="center">
  <img src="screenshots/screenshot1.png" width="200">
  <img src="screenshots/screenshot2.png" width="200">
  <img src="screenshots/screenshot3.png" width="200">
</p> -->

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **UI** | SwiftUI |
| **Data** | SwiftData |
| **Sync** | CloudKit (iCloud) |
| **Payments** | RevenueCat ($4.99 premium) |
| **Architecture** | MVVM |

## Key Features

- **Shift Logging** — Clock in/out with start time, end time, and break duration
- **Earnings Calculator** — Automatic calculation based on hourly rate, overtime, and tips
- **Monthly Overview** — Calendar view with shift summaries and total earnings
- **Multiple Jobs** — Track shifts across different employers with separate rates
- **iCloud Sync** — All data syncs via CloudKit across iPhone and iPad
- **Export** — Generate monthly reports for tax or payroll purposes
- **Israeli Market Support** — ILS (₪) currency formatting

## Architecture

```
ShiftFlow/
├── Models/          # SwiftData models (Shift, Job, Settings)
├── Views/           # SwiftUI views
├── ViewModels/      # Shift calculations, statistics
├── Services/        # CloudKit sync, RevenueCat
└── Utils/           # Date helpers, currency formatting
```

## Links

- [Support](https://peretz2.github.io/ShiftFlow/support.html)
- [Privacy Policy](https://peretz2.github.io/ShiftFlow/privacy.html)
- [Terms of Use](https://peretz2.github.io/ShiftFlow/terms.html)
