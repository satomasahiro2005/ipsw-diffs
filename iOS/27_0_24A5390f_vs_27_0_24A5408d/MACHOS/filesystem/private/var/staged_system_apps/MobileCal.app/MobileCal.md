## MobileCal

> `/private/var/staged_system_apps/MobileCal.app/MobileCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x179714` | `0x17b414` | **`+0x1d00`** |
| `__TEXT.__objc_methname` | `0x356ab` | `0x35c1b` | **`+0x570`** |
| `__TEXT.__objc_stubs` | `0x28100` | `0x28520` | **`+0x420`** |
| `__DATA.__objc_const` | `0x1e3d8` | `0x1e640` | **`+0x268`** |
| `__TEXT.__objc_methlist` | `0x17b88` | `0x17dc8` | **`+0x240`** |
| `__DATA.__objc_selrefs` | `0xc410` | `0xc528` | **`+0x118`** |
| `__TEXT.__cstring` | `0x6d49` | `0x6e09` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x6205` | `0x62a5` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x60c0` | `0x6130` | **`+0x70`** |
| `__DATA.__objc_data` | `0x5de8` | `0x5e38` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x5340` | `0x5380` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x1820` | `0x1844` | **`+0x24`** |
| `__TEXT.__objc_classname` | `0x2f28` | `0x2f48` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x194c` | `0x1958` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x4978` | `0x4980` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x15d0` | `0x15d8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x870` | `0x878` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-29912.0.0.0.0
+29917.0.0.0.0

+  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 8391
-  Symbols:   1661
-  CStrings:  10820
+  Functions: 8442
+  Symbols:   1663
+  CStrings:  10873
Symbols:
+ _UIFontWeightRegular
+ __swift_FORCE_LOAD_$_swiftAppleArchive
CStrings:
+ "AdaptiveColumnSeparator"
+ "LargePhoneMonthWeekView"
+ "LargeWeekViewController _displayEventDetailsPopoverForSelectedEventWithOccurrenceView: journal restore in flight or presentation already active."
+ "MobileCal/MagicComposeFeedbackHandler.swift"
+ "TB,N,V_expandedFormat"
+ "TB,N,V_isExpandedFormat"
+ "TB,N,V_presentsEventDetailsAsSheet"
+ "TB,N,V_scrollsToSelectedDateOnAppear"
+ "TB,N,V_usesScaleSelectionAnimation"
+ "_alignTitlesIfNeededforTraits:mainVC:supplementaryVC:"
+ "_animateSelectionCircle:scaleIn:"
+ "_clearSelectionAfterPresentedDetailsDismissed"
+ "_columnSeparatorViewsInView:"
+ "_expandedFormat"
+ "_hasActivePresentationForEvent:"
+ "_isExpandedFormat"
+ "_isPublishingSelectedDate"
+ "_needsScrollToSelectedDateAfterReflow"
+ "_performWithoutDeferringTransitions:"
+ "_preferredTitleAlignmentForTraits:"
+ "_prefersModalEventPresentation"
+ "_presentsEventDetailsAsSheet"
+ "_scrollToExternallySelectedDate"
+ "_scrollsToSelectedDateOnAppear"
+ "_showDateDepth"
+ "_suppressedColumnSeparators"
+ "_systemImageNamed:withConfiguration:"
+ "_topPinnedSection"
+ "_topVisibleSectionBelowInset"
+ "_usesScaleSelectionAnimation"
+ "_visibleTopY"
+ "activeEditorEvent"
+ "addEventsWithCameraIcon"
+ "addEventsWithCameraText"
+ "addEventsWithCameraTitle"
+ "calendar.and.person"
+ "circleDiameterExpandedFormatForFontSize:"
+ "describeYourEventIcon"
+ "describeYourEventText"
+ "describeYourEventTitle"
+ "expandedFormat"
+ "expandedFormatHourFont"
+ "isExpandedFormat"
+ "isMagicComposeSupportedOnDevice"
+ "isQueuedJournalRestoreInProgress"
+ "isShowingDateProgrammatically"
+ "isVisualIntelligenceCameraSupportedOnDevice"
+ "navigationBarMinimization"
+ "overrideBackgroundColor"
+ "preferredTitleAlignment"
+ "presentsEventDetailsAsSheet"
+ "pulseTodayCell"
+ "pulseTodaySelector"
+ "scrollsToSelectedDateOnAppear"
+ "selectViewConfiguration:preservingSelectedDate:"
+ "setExpandedFormat:"
+ "setIsExpandedFormat:"
+ "setMinimizationBehavior:"
+ "setNavigationBarMinimization:"
+ "setPresentsEventDetailsAsSheet:"
+ "setScrollsToSelectedDateOnAppear:"
+ "setSelectedDate:forceChange:"
+ "setUsesScaleSelectionAnimation:"
+ "shouldMatchDefaultTableStyling"
+ "shouldPresentSplashScreen"
+ "shouldPulseTodaySelectorForSelectedDate:"
+ "subtitle"
+ "timeInsetForSizeClass:aspectRatioType:inViewHierarchy:"
+ "topPadding"
+ "usesScaleSelectionAnimation"
+ "viewControllerForPresentation called with no presenter available"
+ "wantsScaleSelectionAnimation"
+ "weekViewForDayHeaderMeasurement"
- "_activeEditorEvent"
- "_emptyViewForBottomPocket"
- "_hasSetInitialSelectedDate"
- "_prefersCurrentContextEventPresentation"
- "automaticGeocodingEnabled"
- "eventsFoundInAppsEnabled"
- "monthViewScaleIcon"
- "monthViewScaleText"
- "monthViewScaleTitle"
- "mustDisplaySplashScreenToUser"
- "reminderIntegrationIcon"
- "reminderIntegrationText"
- "reminderIntegrationTitle"
- "suggestedEventsFeatureText"
- "suggestedEventsIcon"
- "suggestedEventsTitleText"
- "timeInsetForSizeClass:aspectRatioType:"
- "timeToLeaveAndAutomaticGeocodingFeatureText"
- "timeToLeaveAndAutomaticGeocodingIcon"
- "timeToLeaveAndAutomaticGeocodingTitleText"
```
