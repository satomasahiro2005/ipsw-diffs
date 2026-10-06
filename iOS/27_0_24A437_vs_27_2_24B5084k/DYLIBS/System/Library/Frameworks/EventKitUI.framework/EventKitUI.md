## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f9bc0` | `0x1fb8f0` | **`+0x1d30`** |
| `__AUTH_CONST.__cfstring` | `0xb4c0` | `0xb000` | **`-0x4c0`** |
| `__TEXT.__cstring` | `0xd1a4` | `0xce74` | **`-0x330`** |
| `__AUTH_CONST.__objc_const` | `0x31868` | `0x319e8` | **`+0x180`** |
| `__DATA_CONST.__got` | `0x1c18` | `0x1d78` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x2039c` | `0x204bc` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0xfbf8` | `0xfcc8` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x4898` | `0x4910` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x7e00` | `0x7e60` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x3f78` | `0x3fb0` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x2598` | `0x25c0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2f98` | `0x2fb8` | **`+0x20`** |
| `__AUTH.__data` | `0x1048` | `0x1058` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x17a8` | `0x17b0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1c8c` | `0x1c94` | **`+0x8`** |

### Other Changes

```diff

-1572.0.100.0.0
+1573.1.6.0.0

-  Functions: 12400
-  Symbols:   18525
-  CStrings:  2364
+  Functions: 12428
+  Symbols:   18611
+  CStrings:  2327
Symbols:
+ +[EKReminderTitleDetailCell _circleSymbolFontForTraitCollection:]
+ +[EKUIContextMenuActions filterSuggestedActions:forEvents:]
+ +[EKUIContextMenuActions newEventActionWithHandler:]
+ +[EKUIContextMenuActions newReminderActionWithHandler:]
+ -[EKEventAttendeesEditViewController resetBackgroundColor]
+ -[EKEventEditViewControllerModernImpl invitationResponseSaved]
+ -[EKUIEventInviteesEditViewController eventInviteesViewControllerContentSizeDidChange:]
+ -[EKUIEventInviteesViewController observeValueForKeyPath:ofObject:change:context:]
+ -[EKUIEventStatusButtonsView _foregroundColorForAction:selected:]
+ -[EKUIEventStatusButtonsView _titleFontTransformerForButton:]
+ -[EKUIListViewAllDayEventCell _applyArrangementForLargeText:]
+ -[EKUIListViewAllDayEventCell _dateFieldConstraintsForLargeText:]
+ -[EKUIListViewCell _updateColors]
+ -[EKUIListViewCell needsInactiveAppearance]
+ -[EKUIListViewReminderCell _applyArrangementForLargeText:]
+ -[EKUIListViewReminderCell _arrangementConstraintsForLargeText:]
+ -[EKUIListViewTimedEventCell _adjustLineAxesForLargeText:]
+ -[EKUIListViewTimedEventCell _mergeTimeFieldsForLargeText:]
+ -[EKUIListViewTimedEventCell _timeIntervalTextForStrikethrough:calendar:]
+ -[EKUIYearMonthView horizontalContentOverhang]
+ -[EKUIYearMonthView monthContentBounds]
+ -[UITraitCollection(EventKitUI) ekui_hasLeadingOrTrailingVerticalBar]
+ GCC_except_table23
+ GCC_except_table65
+ GCC_except_table95
+ _CUIKAXAlertCancelButton
+ _CUIKAXAlertDeleteButton
+ _CUIKAXAlertUnsubscribeButton
+ _CUIKAXChooserAddButton
+ _CUIKAXChooserAddHolidayMenuButton
+ _CUIKAXChooserAddMenuButton
+ _CUIKAXChooserShowCompletedRemindersSwitch
+ _CUIKAXChooserShowDeclinedEventsSwitch
+ _CUIKAXDayViewCurrentDay
+ _CUIKAXDeleteCalendarButton
+ _CUIKAXDoneButton
+ _CUIKAXEditorCalendarAccountCell
+ _CUIKAXEditorCalendarColorCell
+ _CUIKAXEditorCalendarSelectedColor
+ _CUIKAXEditorCalendarTitleField
+ _CUIKAXEditorCalendarURLCell
+ _CUIKAXEditorCalendarURLTextField
+ _CUIKAXEditorHolidaySearchField
+ _CUIKAXEditorPreviewCell
+ _CUIKAXEditorPreviewEventsText
+ _CUIKAXEditorSubscriptionDetailsCell
+ _CUIKAXEditorUnsubscribeButton
+ _CUIKAXEventDetailCalendarCell
+ _CUIKAXEventDetailContainer
+ _CUIKAXEventDetailLocationMapCell
+ _CUIKAXEventDetailPreviewCell
+ _CUIKAXEventDetailTitleText
+ _CUIKAXEventEditorAlldaySwitch
+ _CUIKAXEventEditorCalendarSelection
+ _CUIKAXEventEditorCancelButton
+ _CUIKAXEventEditorDeleteCell
+ _CUIKAXEventEditorEndDatePicker
+ _CUIKAXEventEditorNotesCell
+ _CUIKAXEventEditorNotesTextView
+ _CUIKAXEventEditorRepeatCell
+ _CUIKAXEventEditorStartDatePicker
+ _CUIKAXEventEditorTitleField
+ _CUIKAXEventEditorTravelTime
+ _CUIKAXEventEditorUrlCell
+ _CUIKAXMacEventEditorLocationField
+ _CUIKAppearanceSensitiveColor
+ _EKUIInviteesContentSizeObservationContext
+ _OBJC_CLASS_$_CUIKTextProviderUtils
+ _OBJC_CLASS_$_UICommand
+ _OBJC_CLASS_$_UITraitActiveAppearance
+ _OBJC_IVAR_$_EKUIEventInviteesEditViewController._publishedContentSize
+ _OBJC_IVAR_$_EKUIListViewAllDayEventCell._arrangedForLargeText
+ _OBJC_IVAR_$_EKUIListViewAllDayEventCell._dateFieldConstraints
+ _OBJC_IVAR_$_EKUIListViewReminderCell._arrangedForLargeText
+ _OBJC_IVAR_$_EKUIListViewReminderCell._arrangementConstraints
+ _OBJC_IVAR_$_EKUIListViewTimedEventCell._endTimeText
+ _OBJC_IVAR_$_EKUIListViewTimedEventCell._locationSpacer
+ _OBJC_IVAR_$_EKUIListViewTimedEventCell._mergedTimeText
+ _OBJC_IVAR_$_EKUIListViewTimedEventCell._titleSpacer
+ _OBJC_IVAR_$_EKUIListViewTimedEventCell._travelSpacer
+ _UIMenuStandardEdit
+ ___106-[EKEventAttendeesEditViewController initWithFrame:event:overriddenEventStartDate:overriddenEventEndDate:]_block_invoke
+ ___52+[EKUIContextMenuActions newEventActionWithHandler:]_block_invoke
+ ___55+[EKUIContextMenuActions newReminderActionWithHandler:]_block_invoke
+ ___59+[EKUIContextMenuActions filterSuggestedActions:forEvents:]_block_invoke
+ ___61-[EKUIEventStatusButtonsView _titleFontTransformerForButton:]_block_invoke
+ ___block_descriptor_32_e40_B24?0"UIMenuElement"8"NSDictionary"16l
+ ___block_descriptor_48_e8_32w40w_e36_"NSDictionary"16?0"NSDictionary"8lw32l8w40l8
+ ___block_descriptor_56_e8_32w_e18_v16?0"UIButton"8lw32l8
+ ___block_descriptor_64_e8_32s40w_e5_v8?0lw40l8s32l8
- GCC_except_table61
- GCC_except_table63
- GCC_except_table85
- ___block_descriptor_64_e8_32s40w_e18_v16?0"UIButton"8lw40l8s32l8
CStrings:
+ "B24@?0@\"UIMenuElement\"8@\"NSDictionary\"16"
+ "contentSize"
- "EventDetailsContainer"
- "add-calendar-button"
- "add-calendar-menubutton"
- "add-holiday-calendar-menubutton"
- "all-day-switch-cell"
- "calendar-account-cell"
- "calendar-color-cell"
- "calendar-current-selected-color"
- "calendar-preview-cell"
- "calendar-preview-more-events-text"
- "calendar-selection-cell"
- "calendar-subscription-details-cell"
- "calendar-title-field"
- "calendar-url-cell"
- "calendar-url-textfield"
- "cancel-alert-button"
- "cancel-button"
- "current-day"
- "delete-alert-button"
- "delete-calendar-button"
- "delete-event-cell"
- "end-date-picker-cell"
- "event-details-calendar-cell"
- "event-details-location-map-cell"
- "event-details-preview-cell"
- "event-details-title-text"
- "holiday-calendar-search-field"
- "location-field"
- "notes-cell"
- "notes-text-view"
- "repeat-cell"
- "show-completed-reminders-switch"
- "show-declined-events-switch"
- "start-date-picker-cell"
- "title-field"
- "travel-time-cell"
- "unsubscribe-alert-button"
- "unsubscribe-calendar"
- "url-cell"
```
