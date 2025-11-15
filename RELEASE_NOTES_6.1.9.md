# Quick Release Notes - Version 6.1.9

**Release Date:** November 15, 2025

---

## Overview
Quick 6.1.9 brings important UI/UX improvements and bug fixes to enhance user experience across the platform. This release focuses on streamlining dialog layouts and improving navigation for end users.

---

## Key Improvements

### 1. **Enhanced Dialog User Experience**
- **Removed Unwanted Scrollbars**: Fixed unnecessary vertical scrollbars appearing in various dialog components, providing a cleaner interface
  - Broadcaster Details dialog
  - Channel Destination dialog
  - Customer/Client Details dialog
  - User Management dialog
  - Campaign Tracking dialog
  - Invoice Management dialog

### 2. **UI/UX Refinements**
- **Collapsed Menu by Default**: The permissions/menu tree view in User Management is now collapsed by default, making the interface less cluttered. Users can expand sections as needed
- **Typo Correction**: Fixed spelling error "Canceld" → "Cancel" in Customer details page

### 3. **Optimized Data Grid**
- **DisplayGMR Component Refinements**: Improved column organization with better role-based visibility:
  - **Broadcaster View**: Essential campaign information and approval statuses
  - **Admin/SuperAdmin View**: Extended administrative and billing details
  - **Manager View**: Simplified management interface
  - **Customer View**: Customer-specific information with billing details

---

## Bug Fixes

✓ Removed excessive vertical scrollbars causing layout issues  
✓ Fixed spelling inconsistencies in UI labels  
✓ Improved dialog rendering and responsiveness  
✓ Enhanced tree view default state for better UX

---

## Technical Details

**Build Information:**
- Framework: .NET 9.0
- Both QuickCoreApi and QuikWebAssembly projects published successfully
- 16 files updated with 43 insertions and 61 deletions

---

## User Impact

### For Broadcasters
- Cleaner interface with proper approval status displays
- Better video upload management experience

### For Administrators
- Enhanced data visibility in administrative dialogs
- Improved form layouts without unwanted scrollbars
- Better access control configuration

### For Customers
- Simplified campaign tracking interface
- Clearer invoice management screens
- More intuitive user permission settings

### For Managers
- Optimized GMR (Campaign) data display
- Better navigation in complex forms
- Improved role-based data filtering

---

## Recommendations

✅ Update all user clients to version 6.1.9  
✅ No database migrations required  
✅ Backward compatible with existing configurations  
✅ No changes to API contracts

---

## Support

For any issues or questions regarding this release, please contact:
- **Technical Support**: [Support Email]
- **Documentation**: [Knowledge Base Link]

---

**End of Release Notes**

*Quick v6.1.9 - Making your media management experience smoother*
