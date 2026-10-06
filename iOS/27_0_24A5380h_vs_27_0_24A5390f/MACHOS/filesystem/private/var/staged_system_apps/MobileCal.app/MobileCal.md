## MobileCal

> `/private/var/staged_system_apps/MobileCal.app/MobileCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x177890` | `0x179714` | **`+0x1e84`** |
| `__TEXT.__objc_methname` | `0x351ab` | `0x356ab` | **`+0x500`** |
| `__TEXT.__objc_stubs` | `0x27d60` | `0x28100` | **`+0x3a0`** |
| `__DATA.__objc_const` | `0x1e1b8` | `0x1e3d8` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x179e0` | `0x17b88` | **`+0x1a8`** |
| `__DATA.__objc_selrefs` | `0xc310` | `0xc410` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x6058` | `0x60c0` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x52e0` | `0x5340` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x32e0` | `0x3340` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x4928` | `0x4978` | **`+0x50`** |
| `__DATA.__objc_data` | `0x5da0` | `0x5de8` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x1980` | `0x19b0` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x2ef8` | `0x2f28` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1800` | `0x1820` | **`+0x20`** |
| `__DATA.__data` | `0x43d0` | `0x43e0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x6d39` | `0x6d49` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x9a1d` | `0x9a2d` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x15c8` | `0x15d0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x868` | `0x870` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xac8` | `0xac0` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1944` | `0x194c` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xff0` | `0xff8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-29909.0.0.0.0
+29912.0.0.0.0

-  Functions: 8356
-  Symbols:   1654
-  CStrings:  10772
+  Functions: 8391
+  Symbols:   1661
+  CStrings:  10820
Symbols:
+ _$s13CalendarUIKit20MagicComposeSnapshotVMa
+ _$s13CalendarUIKit20MagicComposeSnapshotVMn
+ _$s19RemindersAppIntents0A35InCalendarEditingReminderPropertiesV20magicComposeSnapshot0E5UIKit05MagicjK0VSgvs
+ _$s19RemindersAppIntents0A41InCalendarReminderCreationModuleInterfaceP20magicComposeSnapshot0E5UIKit05MagickL0VSgvgTj
+ _$sSo24CUIKMagicComposeSnapshotC13CalendarUIKitE8snapshotAC05MagicbC0Vvg
+ _$sSo24CUIKMagicComposeSnapshotC13CalendarUIKitE8snapshotAbC05MagicbC0V_tcfC
+ _CGContextClipToRect
+ _OBJC_CLASS_$_CUIKMagicComposeSnapshot
- _OBJC_CLASS_$_CAShapeLayer
CStrings:
+ "%@ %i"
+ "%@ %i %i %i"
+ "00"
+ "@\"CUIKMagicComposeSnapshot\""
+ "B32@0:8q16q24"
+ "T@\"CUIKMagicComposeSnapshot\",&,N,V_magicComposeSnapshot"
+ "T@\"UIBarButtonItem\",&,N,V_activeAddEventBarButtonItem"
+ "T@\"UIButton\",W,N,V_todayButton"
+ "T@\"UIViewController\",W,N,V_delegate"
+ "TB,N,V_suppressPreferredContentSizeUpdates"
+ "TB,N,V_wasScrolledToTop"
+ "_MobileCalModalPresentationDelegateHolder"
+ "_activeAddEventBarButtonItem"
+ "_backButtonHistoryMenuTitle"
+ "_hasPerformedInitialTodayScroll"
+ "_isTodayVisibleInResults"
+ "_magicComposeSnapshot"
+ "_restoreInboxCalendarsSearchAfterChildVCSwap"
+ "_searchTermFromChildVCSwap"
+ "_showFormSheetSearchAnimated:becomeFirstResponder:completion:"
+ "_suppressPreferredContentSizeUpdates"
+ "_switchToCompositeViewWithMainView:secondaryView:"
+ "_updateTodayButtonVisibility"
+ "_wasScrolledToTop"
+ "_weekNumberBarButtonItem"
+ "activeAddEventBarButtonItem"
+ "applyMagicComposeSnapshot:"
+ "cal_usesFormSheetPresentation"
+ "eventViewControllerShouldHideTitleInEditingMode:"
+ "glassButtonConfiguration"
+ "grammarCheckingType"
+ "hidesWeekNumberLabel"
+ "installFloatingTodayButton"
+ "isInteractive"
+ "isScrolledToTop"
+ "isViewControllerEligibleForJournaling:"
+ "magicComposeSnapshot"
+ "prepareForDeselection"
+ "prepareForReselectionWithState:"
+ "presentationStyleOverrideForChildViewController:"
+ "refreshUIForUpdatedEvent:"
+ "representedMainViewType"
+ "scrollToTop"
+ "setActiveAddEventBarButtonItem:"
+ "setBackButtonDisplayMode:"
+ "setBaseForegroundColor:"
+ "setGrammarCheckingType:"
+ "setHidesWeekNumberLabel:"
+ "setMagicComposeSnapshot:"
+ "setMaximumContentSizeCategory:"
+ "setSelectedDay:onMonthWeekView:animated:"
+ "setSuppressPreferredContentSizeUpdates:"
+ "setTodayButton:"
+ "setWasScrolledToTop:"
+ "suppressPreferredContentSizeUpdates"
+ "todayButton"
+ "todayButtonPressed"
+ "wasScrolledToTop"
+ "willDeselectTab"
+ "willSelectTab"
- "@\"CAShapeLayer\""
- "_cal_ViewControllerTreeIsEligibleForJournalingConsideration:"
- "_childInExplicitDisappear"
- "_platterMaskLayer"
- "_usesFormSheetPresentation"
- "cancelBeginAppearanceTransition"
- "displayCornerRadius"
- "prepareForReselection"
- "presentationStyleOverrideForChildViewControllers"
- "refreshUIForUpdatedEvent"
- "setAutomaticallyShowsSearchResultsController:"
- "setPath:"
```
