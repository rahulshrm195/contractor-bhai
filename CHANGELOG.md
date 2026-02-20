# Contractor Bhai — Changelog

---

## v1.6 — 21 Feb 2026
### Added
- "What's New" section in Profile screen — users can now see all version updates inside the app
- Each version shown as a card with date, version number and changes listed

---

## v1.5 — 21 Feb 2026
### Fixed
- Jobs tab clicking did nothing — div IDs were mismatched (tab-jobs vs main-jobs)
- Messages tab clicking did nothing — same mismatch (tab-msg vs main-messages)
- Added missing setActiveNav() function — bottom nav active state now works correctly

---

## v1.4 — 21 Feb 2026
### Added
- 3 new trades: POP Work (🪟), Cushion/Sofa (🛋️), Tiles (🔲)
- Available in: registration form, post work form, edit profile, and filter pills

---

## v1.3 — 21 Feb 2026
### Removed
- Demo "Try Demo" button removed from login screen — app is now fully live
- demoLogin() function removed from codebase

---

## v1.2 — 21 Feb 2026
### Fixed
- Registration form placeholders showing "Ram / Sharma" — users thought name was pre-filled
- All form placeholders now clearly say "Enter your first name / last name"

---

## v1.1 — 21 Feb 2026
### Fixed
- Bottom navigation bar not visible on mobile browsers
- Fixed with 100dvh (dynamic viewport height)
- Bottom nav changed to position fixed
- Added viewport-fit=cover for iPhone safe area support

---

## v1.0 — 20 Feb 2026
### Launch
- Initial launch of Contractor Bhai
- Sub-contractor discovery network for Indian construction trades
- Firebase Phone OTP authentication (real SMS)
- Firestore database — users, jobs, messages
- 9 demo contractors seeded
- Hindi / English bilingual UI
- Light / Dark theme
- WhatsApp support button (+91 82754 07603)
- Deployed at contractorbhai.netlify.app
