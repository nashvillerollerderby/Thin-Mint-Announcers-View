# Changelog

All notable changes to Thin Mint Announcer's View are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [1.3.4] - 2026-05-05

### Added
- Tablet-optimized layout for small, medium, and large tablets
- Touch-friendly command dock for tablet users (no keyboard required)
- Network-aware local connection (auto-connects to CRG host when accessed via IP)

### Changed
- Increased tablet typography (~25–30%) for improved readability trackside
- Improved layout proportions to better utilize tablet screen space
- Established iPad Mini as minimum supported device
- Disabled phone layouts while retaining portrait rotate warning

### Fixed
- Fixed issue where remote devices loading from CRG IP would not receive live data (localhost connection bug)

---

## [1.3.3] - 2026-05-04

### Added
- Lead change detection in Inside Track (post-jam)
- Lead change counter (starting at 2)
- Team context added to skater mentions in Inside Track

### Changed
- Standardized CRG v2025+ as required baseline
- Treated WebSocket data as source of truth (reduced fallback logic)
- Improved connection messaging and behavior

### Fixed
- Fixed missing Inside Track triggers for lead changes
- Fixed inconsistent skater/team labeling in insight messages

---

## [1.3.2] - 2026-05-03

### Added
- Expanded Inside Track logic:
  - Lead changes
  - Tight scoring stretches
  - Score plateaus
  - Reset moments
- Jam history export (text format)
- Jam history clear with confirmation

### Changed
- Jam History hotkey updated to `J`
- Reduced visual noise in hotkey/button styling
- Simplified differential display

### Fixed
- Fixed penalty detail panel errors and freezes
- Fixed Inside Track priority conflicts
- Fixed lineup/jam state transition issues

---

## [1.3.1] - 2026-05-02

### Added
- Jammer point accumulation badge
- Six-penalty warning indicator (⚠️)
- Inside Track improvements for game context

### Changed
- Refined alert thresholds (scoreless jams, response suppression)
- Improved badge styling and jammer role transitions

### Fixed
- Fixed penalty detail population issues
- Fixed score sync issues between jam and game totals
- Fixed power jam edge cases after star passes

---

## [1.3.0] - 2026-05-01

### Added
- Inside Track (real-time announcer insight system)
- Inside Track history
- Inside Track mute control

### Changed
- Improved overall information hierarchy
- Refined layout spacing and center panel alignment
- Improved footer and modal presentation

### Fixed
- Fixed About modal layout issues
- Fixed connection feedback visibility

---

## [1.2.0] - 2026-04-30

### Added
- Penalty heat display
- Penalty code reference panel
- Remote connection panel (manual IP entry)
- Dark/light mode support

### Changed
- Improved center panel layout and spacing
- Improved footer and hotkey display

### Fixed
- Fixed About modal footer clipping and border issues
- Fixed state badge alignment

---

## [1.1.0] - 2026-04-29

### Added
- Jam history display
- Period and game summaries
- Lead jammer, star pass, and call-off indicators
- Power jam indicators
- About overlay

### Changed
- Improved layout readability and broadcast-style presentation
- Improved score and lineup display

### Fixed
- Fixed early layout and display inconsistencies

---

## [1.0.0] - 2026-04-29

### 🎉 Initial Release
