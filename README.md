# Grand Concert Song Tracker

Interactive mobile-friendly song tracker for Uma Musume Grand Concert scenario.

## Features

- Track song purchases across all career phases
- Technique tracking with carryover system, showing next number of required techniques after buying next song
- Target savings calculation with priority recommendations for current and next phase
- Draggable song priority list customization
- Local storage persistence
- Responsive design optimized for mobile

## Usage

Open `index.html` in a browser. Tap songs to mark as bought. Use phase arrows to navigate.

## Changelog

### v1.7
- Fixed technique counter not accounting for carryover song in requirement calculation
- Fixed TARGET (NEXT PHASE) calculation to exclude current TARGET songs and include friendship bonus songs

### v1.6
- Fixed carryover technique counting: carryover song now correctly replaces the first technique slot
- Technique progress after buying carryover song now shows 1/N instead of 0/N
- Fixed technique requirements when navigating between phases with carryover active
- Fixed unbuying carried-over songs to properly reset technique counter

### v1.5
- Added technique tracking with carryover system
- Added NEXT indicator showing upcoming technique requirements
- Added dual TARGET rows for better organization

### v1.3
- Added draggable song priority list customization

### v1.2
- Fixed rainbow border rendering
- Fixed Girls' Legend U visibility (for real now)

### v1.1
- Fixed Girls' Legend U visibility

### v1.0
- Initial release

## Credits

Created by Sukuna#701119311607
