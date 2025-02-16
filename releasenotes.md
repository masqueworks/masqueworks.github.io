---
title: Release Notes
layout: default
parent: Documentation
---

# v0.9.9.10 (Feb 15, 2025)

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
