# CommBank Goal Tracker
## Summary

This pull request adds support for goal icons in the Goal Manager.

### Changes made
- Added support for displaying goal icons.
- Added an "Add icon" button for goals without an icon.
- Integrated the emoji picker for selecting icons.
- Enabled changing an existing goal icon.
- Updated the Goal model to include an icon property.
- Updated GoalManager to save icon changes through Redux and the API.

### Testing
- Verified icon selection.
- Verified icon updates.
- Verified existing icons can be changed.
