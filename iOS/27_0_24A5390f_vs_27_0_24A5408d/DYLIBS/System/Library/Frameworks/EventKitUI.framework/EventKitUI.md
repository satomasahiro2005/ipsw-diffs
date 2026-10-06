## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f6f90` | `0x1f9aec` | **`+0x2b5c`** |
| `__AUTH_CONST.__objc_const` | `0x31630` | `0x31838` | **`+0x208`** |
| `__TEXT.__objc_methlist` | `0x2020c` | `0x2038c` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x2ee0` | `0x2f98` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x7d00` | `0x7da0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0xfb58` | `0xfbf0` | **`+0x98`** |
| `__DATA.__data` | `0x5168` | `0x51c8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x7db8` | `0x7e00` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x3fbc` | `0x3f78` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x1bd8` | `0x1c10` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x780` | `0x7b8` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1778` | `0x17a0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x4878` | `0x4898` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd184` | `0xd1a4` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2584` | `0x2594` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc80` | `0xc90` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x8b8` | `0x8c8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x16fd` | `0x170d` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xdc0` | `0xdcc` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x658` | `0x660` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1c84` | `0x1c8c` | **`+0x8`** |

### Other Changes

```diff

-1568.0.0.0.0
+1572.0.0.0.0

-  Functions: 12358
-  Symbols:   18458
+  Functions: 12398
+  Symbols:   18520
Symbols:
+ +[EKAbstractCalendarEditor usesOverCurrentContextPresentationInView:]
+ +[EKDayTimeView _prefersPadTimeMetricsInViewHierarchy:]
+ +[EKDayTimeView timeInsetForSizeClass:aspectRatioType:inViewHierarchy:]
+ -[EKAbstractCalendarEditor _adjustTableContentInsetForKeyboardNotification:]
+ -[EKDayViewWithGutters _leadingAlignOverlayBandIfNeeded]
+ -[EKDayViewWithGutters _shouldLeadingAlignOverlayBand]
+ -[EKDayViewWithGutters _updateTopLabelsContainerHidden]
+ -[EKEventAttendeePicker _filterBlockedRecipients:completion:]
+ -[EKEventAttendeesEditViewController preferredContentSize]
+ -[EKEventDetailTableView adjustedContentInsetDidChange]
+ -[EKEventEditViewControllerModernImpl willMoveToParentViewController:]
+ -[EKEventViewControllerDefaultImpl _shouldRenderReminderDeleteInList]
+ -[EKEventViewControllerDefaultImpl reminderDeleteDetailItem:requestsDeleteWithSourceView:]
+ -[EKExpandedReminderStackCell _applyBackgroundCornerRadiusVisible:]
+ -[EKExpandedReminderStackCell setupCellWithTitle:completed:editable:date:buttonColor:buttonImageName:backgroundColor:recurringString:shouldMatchDefaultTableStyling:delegate:]
+ -[EKExpandedReminderStackViewController _applyBackgroundColorFromDelegate]
+ -[EKExpandedReminderStackViewController expandedReminderStackShouldMatchDefaultTableStyling]
+ -[EKICSPreviewController eventViewControllerShouldHideNavigationDetailsCancelButton:]
+ -[EKReminderDeleteDetailCell .cxx_destruct]
+ -[EKReminderDeleteDetailCell initWithEvent:editable:]
+ -[EKReminderDeleteDetailCell setSeparatorStyle:]
+ -[EKReminderDeleteDetailItem .cxx_destruct]
+ -[EKReminderDeleteDetailItem cellForSubitemAtIndex:]
+ -[EKReminderDeleteDetailItem defaultCellHeightForSubitemAtIndex:forWidth:forceUpdate:]
+ -[EKReminderDeleteDetailItem eventViewController:didSelectReadOnlySubitem:]
+ -[EKReminderDeleteDetailItem initWithDeleteDelegate:]
+ -[EKReminderDeleteDetailItem reset]
+ -[EKReminderDeleteDetailItem section]
+ -[EKUIEventInviteesEditViewController attendees]
+ GCC_except_table108
+ GCC_except_table111
+ GCC_except_table125
+ GCC_except_table128
+ GCC_except_table131
+ GCC_except_table134
+ GCC_except_table172
+ GCC_except_table29
+ GCC_except_table34
+ GCC_except_table42
+ _OBJC_CLASS_$_CalBlockListFilter
+ _OBJC_CLASS_$_EKReminderDeleteDetailCell
+ _OBJC_CLASS_$_EKReminderDeleteDetailItem
+ _OBJC_CLASS_$_UICornerConfiguration
+ _OBJC_CLASS_$_UICornerRadius
+ _OBJC_IVAR_$_EKExpandedReminderStackCell._matchesDefaultTableStyling
+ _OBJC_IVAR_$_EKReminderDeleteDetailCell._titleLabel
+ _OBJC_IVAR_$_EKReminderDeleteDetailItem._cell
+ _OBJC_IVAR_$_EKReminderDeleteDetailItem._deleteDelegate
+ _OBJC_METACLASS_$_EKReminderDeleteDetailCell
+ _OBJC_METACLASS_$_EKReminderDeleteDetailItem
+ _UIKeyboardAnimationCurveUserInfoKey
+ _UIKeyboardAnimationDurationUserInfoKey
+ __OBJC_$_INSTANCE_METHODS_EKReminderDeleteDetailCell
+ __OBJC_$_INSTANCE_METHODS_EKReminderDeleteDetailItem
+ __OBJC_$_INSTANCE_VARIABLES_EKReminderDeleteDetailCell
+ __OBJC_$_INSTANCE_VARIABLES_EKReminderDeleteDetailItem
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EKReminderDeleteDetailItemDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EKReminderDeleteDetailItemDelegate
+ __OBJC_$_PROTOCOL_REFS_EKReminderDeleteDetailItemDelegate
+ __OBJC_CLASS_RO_$_EKReminderDeleteDetailCell
+ __OBJC_CLASS_RO_$_EKReminderDeleteDetailItem
+ __OBJC_LABEL_PROTOCOL_$_EKReminderDeleteDetailItemDelegate
+ __OBJC_METACLASS_RO_$_EKReminderDeleteDetailCell
+ __OBJC_METACLASS_RO_$_EKReminderDeleteDetailItem
+ __OBJC_PROTOCOL_$_EKReminderDeleteDetailItemDelegate
+ __UITableViewDefaultSectionCornerRadiusForTraitCollection
+ ___120-[EKCalendarChooserDefaultImpl _presentEditor:withIndexPath:barButtonItem:permittedArrowDirections:animated:completion:]_block_invoke
+ ___61-[EKEventAttendeePicker _filterBlockedRecipients:completion:]_block_invoke
+ ___61-[EKEventAttendeePicker _filterBlockedRecipients:completion:]_block_invoke_2
+ ___76-[EKAbstractCalendarEditor _adjustTableContentInsetForKeyboardNotification:]_block_invoke
+ ___block_descriptor_32_e38_"NSString"16?0"CNComposeRecipient"8l
+ ___block_descriptor_34_e71_"NSCollectionLayoutSection"24?0q8"<NSCollectionLayoutEnvironment>"16l
+ ___block_descriptor_56_e8_32s40s48w_e17_v16?0"NSArray"8lw48l8s32l8s40l8
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.153Tm
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.45Tm
+ ___swift_closure_destructor.85Tm
+ _swift_retain_x25
- +[EKDayTimeView timeInsetForSizeClass:aspectRatioType:]
- -[EKEventAttendeePicker predicateForContactWithBlockedAddress]
- -[EKExpandedReminderStackCell setupCellWithTitle:completed:editable:date:buttonColor:buttonImageName:backgroundColor:recurringString:delegate:]
- GCC_except_table124
- GCC_except_table130
- GCC_except_table133
- GCC_except_table171
- GCC_except_table38
- GCC_except_table72
- _OBJC_CLASS_$_UIKeyboard
- ___62-[EKEventAttendeePicker predicateForContactWithBlockedAddress]_block_invoke
- ___block_descriptor_33_e71_"NSCollectionLayoutSection"24?0q8"<NSCollectionLayoutEnvironment>"16l
- ___block_descriptor_40_e8_32s_e25_B24?08"NSDictionary"16ls32l8
- ___swift_closure_destructor.35Tm
- ___swift_closure_destructor.42Tm
- ___swift_closure_destructor.5Tm
- ___swift_closure_destructor.82Tm
CStrings:
+ "@\"NSString\"16@?0@\"CNComposeRecipient\"8"
+ "Gesture controller tried to commit with no dragging view but a live event. Cancelling instead."
- "B24@?0@8@\"NSDictionary\"16"
- "Gesture controller tried to commit, but with no view to drag. Cancelling instead."
```
