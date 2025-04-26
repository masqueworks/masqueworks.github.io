---
title: Release Notes
layout: default
parent: Documentation
---
# Masque v0.9.10.8 (Apr 26, 2025)

## Timeline and Media
- Fixed stretched images in the Timeline and improved scrubbing.
- Better handling of infinite actions; Timeline length now calculated from max media length.
- Play Media Clip includes `MediaEndTime` for better looping; Play Action Duration now reports correctly.
- Clear selection button updated with new icon; scrubbing and multi-selection improved.

## Inspector, Canvas, and Palettes
- Clear Experimental Values button added.
- Palette list separated from media list for better filtering.
- New dialogs for creating Effects and Palettes; Effects saved immediately.
- Added friendly names to Effect channel dropdowns and reordered lists for clarity.
- Inspector improvements for selecting and editing collection items.

## Audio and Gizmo Control
- Removed Audio Mute channel; Mute is now runtime and handled cleanly.
- Audio auditioning respects master fader and media settings.
- Fixes to selections and link releases in the Controls window.
- Deleting fixtures properly syncs with associated gizmos.

## Cues and Macros
- Added `StopCue` macro action.
- Cue linking and AutoFollow improved to consider disabled cues.
- Better Save As behavior to maintain Macro links and recent lists.
- Inspector now shows cue ID and name for macro targeting.

## Fixture and Device Management
- Dragging fixture definitions works correctly; patches update properly.
- Fixes for Station Wizard crashes and fixture creation bugs.
- Removing gizmos updates the venue patch correctly.
- Improved dragging behavior in the Devices and Canvas views.

## System and Undo/Redo
- Duplicating cues and actions now uses serialization.
- Undo system cleaned and reset after performance loading.
- Clearer feedback when modifying palettes and driver connections.
- Performance window shows loop counts; isolated cues no longer affect NextCue.

## Documentation and Publishing
- Documentation updates included in publishing.
- Welcome Window respects "Don't Show" setting.
- License purchase flow improved.
- Added offline documentation access from the app.

## NEW Drivers Window
- Allows driving channels with a node based graph
- Added logic nodes (Clamp, Accumulator, etc.), virtual faders, and gamepad support.
- Better serialization and undo/redo support for nodes.
- Preview features handling clarified.

## General Improvements and Fixes
- Fixed experimental value handling across media and palettes.
- Improved performance cue layout and UI tweaks across views.
- Additional code cleanups, better defaults (e.g., pulse period = 1).
- Improved error handling during Save As and station importing.

---

# Masque v0.9.9.12 (Mar 2, 2025)

### New Features  
- **Basic Pitch Shifting for Audio Media**:  
  - Added a new parameter to audio media that allows pitch shifting by a specified number of tones.  

### Performance Improvements  
- **Faster Startup Times**:  
  - Improved application startup by deferring non-essential work until after the main form has loaded and rendered.  

# Masque v0.9.9.11 (Feb 24, 2025)

### New Features  
- **Wall Clock Toggle**: Added the ability to turn the wall clock on or off.  
- **Forums Link**: Added a link to the forums for easier access.  

### Improvements  
- **Application Window Bounds Handling**:  
  - Properly handle cases where window bounds were stored while the app was minimized.  
- **Gizmo and Fixture Naming Sync**: If a single gizmo is mapped to a single fixture, their names will now remain in sync.  
- **Media Selection Improvement**: If there is only one media item in the list, it is now automatically selected and sent to the property inspector.  
- **Gizmo Patch Naming**: Improved the naming of array items in the Gizmo Patch for better clarity.  

### Bug Fixes  
- **Canvas Gizmo Names in Live Mode**: Fixed an issue where canvas gizmo names could not be toggled on and off in Live Mode.  
- **Fixture Naming in New Station Wizard**: Creating new fixture names will no longer be overridden when setting the fixture type in the wizard.  
- **Recent Performances in Welcome Window**: Fixed an issue where the Welcome Window was not properly loading recent performances.  

### Policy & Documentation Updates  
- **Updated Agreements**: Revised the **EULA, Privacy Policy, and Terms of Service**.  
- **Website References**: Updated website references throughout the application.  
- **Release Ring Restrictions**: A full license is now required to change the release ring.  

# Masque v0.9.9.10 (Feb 15, 2025)

### New Features  
- **Device Fixture Duplication**: When duplicating a device fixture, it will now be added as a gizmo per the specified setting.  
- **Channel Patch Enhancements**: Added the ability to specify parameters when creating a channel patch.  
- **Channel Inversion**: Users can now invert channels on a per-fixture, per-channel basis.  
- **Custom Channel Naming**: Fixture channels can now be assigned custom names.  

### Improvements  
- **DMX Channel Display**: DMX channels now show the channel index instead of the channel offset in the property editor.  
- **Fine Channel Index Handling**: When setting a Fine Channel index, the MaxValue will now update correctly if it is at its default.  

### Bug Fixes  
- **Performance Folder Behavior**:  
  - Opening the performance folder now defaults to the correct folder.  
  - Fixed an issue where the performance folder was not being saved properly.  
