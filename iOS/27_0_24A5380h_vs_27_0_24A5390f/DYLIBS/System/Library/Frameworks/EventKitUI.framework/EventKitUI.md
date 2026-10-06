## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f6e2c` | `0x1f6f90` | **`+0x164`** |
| `__TEXT.__objc_methlist` | `0x200ac` | `0x2020c` | **`+0x160`** |
| `__DATA_CONST.__objc_selrefs` | `0xfae0` | `0xfb58` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x401c` | `0x3fbc` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x315e8` | `0x31630` | **`+0x48`** |
| `__TEXT.__cstring` | `0xd174` | `0xd184` | **`+0x10`** |

### Other Changes

```diff

-1565.0.0.0.0
+1568.0.0.0.0

-  Functions: 12336
-  Symbols:   18439
+  Functions: 12358
+  Symbols:   18458
Symbols:
+ -[EKCalendarChooser isScrolledToTop]
+ -[EKCalendarChooser scrollToTop]
+ -[EKCalendarChooserDefaultImpl isScrolledToTop]
+ -[EKCalendarChooserDefaultImpl scrollToTop]
+ -[EKCalendarChooserOOPWrapperImpl isScrolledToTop]
+ -[EKCalendarChooserOOPWrapperImpl scrollToTop]
+ -[EKDayViewController hidesWeekNumberLabel]
+ -[EKDayViewController setHidesWeekNumberLabel:]
+ -[EKEventEditViewController refreshUIForUpdatedEvent:]
+ -[EKEventEditViewControllerDefaultImpl applyMagicComposeSnapshot:]
+ -[EKEventEditViewControllerDefaultImpl magicComposeSnapshot]
+ -[EKEventEditViewControllerDefaultImpl refreshUIForUpdatedEvent:]
+ -[EKEventEditViewControllerDefaultImpl willDeselectTab]
+ -[EKEventEditViewControllerDefaultImpl willSelectTab]
+ -[EKEventEditViewControllerModernImpl _notifyEditViewDelegateDidCompleteWithAction:]
+ -[EKEventEditViewControllerModernImpl _shouldHideTitleInEditingModeFromDelegate]
+ -[EKEventEditViewControllerModernImpl applyMagicComposeSnapshot:]
+ -[EKEventEditViewControllerModernImpl magicComposeSnapshot]
+ -[EKEventEditViewControllerModernImpl refreshUIForUpdatedEvent:]
+ -[EKEventEditViewControllerModernImpl willDeselectTab]
+ -[EKEventEditViewControllerModernImpl willSelectTab]
+ -[EKEventEditViewControllerOOPWrapperImpl applyMagicComposeSnapshot:]
+ -[EKEventEditViewControllerOOPWrapperImpl magicComposeSnapshot]
+ -[EKEventEditViewControllerOOPWrapperImpl refreshUIForUpdatedEvent:]
+ -[EKEventEditViewControllerOOPWrapperImpl willDeselectTab]
+ -[EKEventEditViewControllerOOPWrapperImpl willSelectTab]
+ -[EKExpandedReminderStackViewController showViewController:sender:animated:completion:]
+ GCC_except_table124
+ GCC_except_table130
+ GCC_except_table133
+ _OBJC_IVAR_$_EKDayViewController._hidesWeekNumberLabel
+ _OBJC_IVAR_$_EKEventEditViewControllerModernImpl._notifyingEditViewDelegateCompletion
- -[EKEventEditViewController refreshUIForUpdatedEvent]
- -[EKEventEditViewControllerDefaultImpl refreshUIForUpdatedEvent]
- -[EKEventEditViewControllerModernImpl refreshUIForUpdatedEvent]
- -[EKEventEditViewControllerOOPWrapperImpl refreshUIForUpdatedEvent]
- GCC_except_table109
- GCC_except_table123
- GCC_except_table126
- GCC_except_table132
- GCC_except_table26
- GCC_except_table31
- _OBJC_IVAR_$_EKDayPreviewController._originalEventEndDate
- _OBJC_IVAR_$_EKDayPreviewController._originalEventStartDate
- ___54-[EKDayPreviewController _eventsForStartDate:endDate:]_block_invoke
CStrings:
+ "\xf0\xf0!!1"
- "\tZRC"
```
