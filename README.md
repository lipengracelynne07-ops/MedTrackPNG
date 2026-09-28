# MedTrack PNG — Kimadan Health Centre v2.0.0

Offline-first Android WebView trial application for Kimadan Health Centre.

GitHub Actions builds a debug APK on pushes to `main` or by manual workflow dispatch.

Demo accounts:
- admin / admin123
- dispenser / dispense123
- store / store123
- supervisor / super123
- clinical / clinical123
- viewer / viewer123

Trial modules:
- Role-based sign-in and navigation
- Kimadan facility configuration
- Medicine master and stock status
- Batch-aware stock receiving and expiry
- PNG MDC catalogue reference layer
- Internal medicine orders
- Title/category clearance
- Reviewer approval/rejection
- Audit events and JSON export
- Offline localStorage
- Scrollable content with fixed header/bottom navigation

Known limitation: approval changes order status but does not yet automatically deduct stock or perform guided FEFO issuing.
