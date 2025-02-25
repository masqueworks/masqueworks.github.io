---
title: Release Notes
layout: default
parent: Documentation
---

# Masque v0.9.9.11 (Feb 24, 2025)

## New Features  
- **Wall Clock Toggle**: Added the ability to turn the wall clock on or off.  
- **Forums Link**: Added a link to the forums for easier access.  

## Improvements  
- **Application Window Bounds Handling**:  
  - Properly handle cases where window bounds were stored while the app was minimized.  
- **Gizmo and Fixture Naming Sync**: If a single gizmo is mapped to a single fixture, their names will now remain in sync.  
- **Media Selection Improvement**: If there is only one media item in the list, it is now automatically selected and sent to the property inspector.  
- **Gizmo Patch Naming**: Improved the naming of array items in the Gizmo Patch for better clarity.  

## Bug Fixes  
- **Canvas Gizmo Names in Live Mode**: Fixed an issue where canvas gizmo names could not be toggled on and off in Live Mode.  
- **Fixture Naming in New Station Wizard**: Creating new fixture names will no longer be overridden when setting the fixture type in the wizard.  
- **Recent Performances in Welcome Window**: Fixed an issue where the Welcome Window was not properly loading recent performances.  

## Policy & Documentation Updates  
- **Updated Agreements**: Revised the **EULA, Privacy Policy, and Terms of Service**.  
- **Website References**: Updated website references throughout the application.  
- **Release Ring Restrictions**: A full license is now required to change the release ring.  

# Masque v0.9.9.10 (Feb 15, 2025)

## New Features  
- **Device Fixture Duplication**: When duplicating a device fixture, it will now be added as a gizmo per the specified setting.  
- **Channel Patch Enhancements**: Added the ability to specify parameters when creating a channel patch.  
- **Channel Inversion**: Users can now invert channels on a per-fixture, per-channel basis.  
- **Custom Channel Naming**: Fixture channels can now be assigned custom names.  

## Improvements  
- **DMX Channel Display**: DMX channels now show the channel index instead of the channel offset in the property editor.  
- **Fine Channel Index Handling**: When setting a Fine Channel index, the MaxValue will now update correctly if it is at its default.  

## Bug Fixes  
- **Performance Folder Behavior**:  
  - Opening the performance folder now defaults to the correct folder.  
  - Fixed an issue where the performance folder was not being saved properly.  
