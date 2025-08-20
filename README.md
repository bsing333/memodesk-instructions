# MemoDesk Instructions & Updates

This repository hosts the complete interactive instruction booklet for MemoDesk.

## Structure
- `instructions/` - Complete interactive instruction booklet (PNG-based + all controls)
  - `pages/` - PNG instruction pages (automatically detected)
  - `assets/` - Custom cursors, icons, and other design elements
- `version.txt` - Current version number for update checking
- `changelog.md` - Update notes and changelog

## How It Works
1. **Instructions**: Complete interactive experience hosted as GitHub Pages
2. **Iframe Loading**: App loads entire instruction system via iframe
3. **Version Check**: App compares local version with `version.txt`
4. **Updates**: When versions differ, app shows update notification

## What's Included in Instructions
- Interactive PNG-based booklet (48 pages)
- Mouse hover-to-scrub functionality
- Keyboard navigation (arrow keys)
- Expand/collapse with animations
- Page turning with left/right clicks
- Page counter (X of 48)
- Instruction text and controls
- All interactive logic and state management

## Deployment
- Push to main branch = automatic GitHub Pages deployment
- No API keys needed - everything is public
- Complete instruction system loads via iframe in MemoDesk app
- Zero code maintenance for instructions after initial setup
