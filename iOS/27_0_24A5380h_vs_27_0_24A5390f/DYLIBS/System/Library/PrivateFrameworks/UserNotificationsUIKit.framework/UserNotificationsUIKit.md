## UserNotificationsUIKit

> `/System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf2ec` | `0x1c001c` | **`+0xd30`** |
| `__TEXT.__oslogstring` | `0xfd69` | `0x100b9` | **`+0x350`** |
| `__TEXT.__objc_methlist` | `0x1ac4c` | `0x1acac` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x7ea0` | `0x7ee0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x51c0` | `0x51e8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x2d28` | `0x2d3c` | **`+0x14`** |
| `__AUTH_CONST.__objc_const` | `0x26bb8` | `0x26bc8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x9fbd` | `0x9fcd` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xd24` | `0xd34` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x18a0` | `0x18a8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb18` | `0xcb10` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x7418` | `0x7420` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1774` | `0x1770` | **`-0x4`** |

### Other Changes

```diff

-1065.0.0.0.0
+1070.0.0.0.0

-  Functions: 10958
-  Symbols:   14404
-  CStrings:  2149
+  Functions: 10966
+  Symbols:   14408
+  CStrings:  2162
Symbols:
+ -[NCAppPickerViewController _collectionViewContentHeight]
+ -[NCAppPickerViewController _updateLayoutSizesForWidth:onLayout:]
+ -[NCAppPickerViewController preferredContentSize]
+ -[NCAppPickerViewController viewWillLayoutSubviews]
+ -[NCDigestOnboardingNavigationController viewDidLoad]
+ -[NCNotificationGroupList contentRevealRelayArmed]
+ -[NCNotificationGroupList contentRevealReportCount]
+ -[NCNotificationGroupList setContentRevealRelayArmed:]
+ -[NCNotificationGroupList setContentRevealReportCount:]
+ -[NCNotificationStructuredSectionList notificationListPresentableGroup:didUpdatePreferredContentSize:]
+ GCC_except_table103
+ GCC_except_table147
+ GCC_except_table178
+ GCC_except_table200
+ GCC_except_table203
+ GCC_except_table232
+ _OBJC_IVAR_$_NCAppPickerViewController._cachedLayoutWidth
+ _OBJC_IVAR_$_NCAppPickerViewController._collectionViewHeightConstraint
+ _OBJC_IVAR_$_NCNotificationGroupList._contentRevealRelayArmed
+ _OBJC_IVAR_$_NCNotificationGroupList._contentRevealReportCount
- +[NCAppPickerViewHeader _descriptionFont]
- +[NCAppPickerViewHeader _descriptionText]
- +[NCAppPickerViewHeader _titleFont]
- +[NCAppPickerViewHeader _titleText]
- -[NCAppPickerViewController _updateHeightConstraintAndLayoutIfNeeded:]
- -[NCAppPickerViewController _updateHeightConstraintAndLayout]
- GCC_except_table177
- GCC_except_table184
- GCC_except_table199
- GCC_except_table231
- _OBJC_IVAR_$_NCAppPickerViewController._collectionViewVisibleHeight
- _OBJC_IVAR_$_NCAppPickerViewController._heightConstraint
- _OBJC_IVAR_$_NCAppPickerViewController._topConstraint
- _OBJC_IVAR_$_NCAppPickerViewHeader._descriptionLabel
- _OBJC_IVAR_$_NCAppPickerViewHeader._titleLabel
- ___81-[NCNotificationSeamlessContentView _layoutSubviewInBounds:measuringOnly:traits:]_block_invoke_20
CStrings:
+ "%{public}@ content-reveal last report; re-pinning root stack"
+ "%{public}@ content-reveal relay %{public}@ (deviceAuthenticated %d)"
+ "%{public}@ content-reveal report %lu of %lu for %{public}@ (h=%.1f)"
+ "%{public}@ onInsert escalating to reloadNotificationRequest: request=%{public}@; hadCellUnderSelf=%{BOOL}d"
+ "%{public}@ orientation updated; verticalSizeClass: %lu"
+ "Skip content-reveal re-pin: a scroll is already queued"
+ "Skip content-reveal re-pin: currentPageType is nil"
+ "Skip content-reveal re-pin: history section reveal does not move the stack"
+ "Skip content-reveal re-pin: no below-the-fold content to scroll"
+ "Skip content-reveal re-pin: no page for target type %{public}s"
+ "Skip content-reveal re-pin: user is engaging the view; isUserEngagingView: %{bool}d; isTracking: %{bool}d; isDragging: %{bool}d"
+ "Skipping layout of %{public}@ with non-finite frame %{public}@"
+ "armed"
+ "deviceAuthenticated set to %{bool,public}d; backlightLuminance %{public}ld; shouldAllowScrollValidation %{bool,public}d"
+ "disarmed"
- "%{public}@ orientation updated; verticalSizeClass: %lu; global verticalSizeClass: %lu"
- "ListView's window is nil, using view bounds as a fallback size for orientation check"
```
