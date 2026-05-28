# PIXL ARCADE v10.3.0 Upgrade Tasks

## Core Upgrades
- [x] Upgrade version from 10.1.0/10.2.0 to 10.3.0 throughout the site
- [x] Fix Google Login (real Firebase Google Auth popup)
- [x] Fix Apple Login (real Firebase Apple Auth — graceful fallback since Apple requires paid config)
- [x] Implement real cloud save via Firestore (load/save user data on login)
- [x] Keep all existing website design/structure intact

## New Features
- [x] Add developer console hack system (game.coins = 9999, game.account.status = UNBAN)
- [x] Enhance ban system with AI bad-name detection (50+ words + l33t speak obfuscation)
- [x] Enhance appeal system with multi-factor AI sincerity analysis
- [x] Ensure 5-min ban timer works properly
- [x] Ensure all 35 games are present and working
- [x] Update changelog modal to v10.3.0 with new features listed

## Verification
- [x] Test the final HTML file renders correctly
- [x] Verify login flow, cloud save, ban system work
- [x] Changelog modal displays v10.3.0 features correctly
