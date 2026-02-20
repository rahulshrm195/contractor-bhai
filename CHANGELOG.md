# Contractor Bhai — Changelog

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
- Demo login button changed to "Try Demo" (now fully removed in v1.3)

---

## v1.1 — 21 Feb 2026
### Fixed
- Bottom navigation bar (Find / Work / Messages / Profile) not visible on mobile browsers
- Root cause: 100vh includes browser address bar height on mobile, pushing nav out of view
- Fixed with 100dvh (dynamic viewport height) which adjusts automatically
- Bottom nav changed to position fixed for reliable display on all devices
- Added viewport-fit=cover for iPhone notch / home indicator safe area support

---

## v1.0 — 20 Feb 2026
### Launch
- Initial launch of Contractor Bhai
- Sub-contractor discovery network for Indian construction trades
- Firebase Phone OTP authentication (real SMS)
- Firestore database — users, jobs, messages
- 9 demo contractors seeded across Mumbai, Pune, Delhi, Bangalore, Hyderabad, Chennai, Jaipur, Nashik, Ahmedabad
- 7 demo work postings from major Indian contractors
- Hindi / English bilingual UI
- Light / Dark theme
- WhatsApp support button (+91 82754 07603)
- Deployed at contractorbhai.netlify.app
