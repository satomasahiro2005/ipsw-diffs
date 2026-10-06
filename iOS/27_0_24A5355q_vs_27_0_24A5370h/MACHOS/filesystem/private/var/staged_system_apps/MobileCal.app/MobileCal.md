## MobileCal

> `/private/var/staged_system_apps/MobileCal.app/MobileCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172d64` | `0x174ee4` | **`+0x2180`** |
| `__TEXT.__objc_methname` | `0x3464b` | `0x34ceb` | **`+0x6a0`** |
| `__TEXT.__objc_stubs` | `0x27580` | `0x27980` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0x5ea5` | `0x6235` | **`+0x390`** |
| `__DATA.__objc_const` | `0x1db50` | `0x1dec8` | **`+0x378`** |
| `__TEXT.__objc_methlist` | `0x175b0` | `0x17800` | **`+0x250`** |
| `__DATA_CONST.__cfstring` | `0x5000` | `0x5200` | **`+0x200`** |
| `__TEXT.__objc_methtype` | `0x97fd` | `0x99ad` | **`+0x1b0`** |
| `__DATA.__objc_selrefs` | `0xc0d0` | `0xc200` | **`+0x130`** |
| `__DATA.__data` | `0x4290` | `0x4350` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x5ed8` | `0x5f98` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x69c5` | `0x6a65` | **`+0xa0`** |
| `__DATA.__objc_data` | `0x5c38` | `0x5c88` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x2e78` | `0x2ec8` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1794` | `0x17d4` | **`+0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0x240` | `0x278` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x4890` | `0x48b8` | **`+0x28`** |
| `__DATA_CONST.__objc_arrayobj` | `0x240` | `0x258` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x18dc` | `0x18f4` | **`+0x18`** |
| `__DATA.__bss` | `0x10c8` | `0x10d8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x4e8` | `0x4f8` | **`+0x10`** |
| `__TEXT.__const` | `0x1774` | `0x1784` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1458` | `0x1450` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x850` | `0x858` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x550` | `0x558` | **`+0x8`** |
| `__TEXT.__ustring` | `0x4b4` | `0x4bc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-29902.0.100.0.0
+29906.0.0.0.0

-  Functions: 8246
+  Functions: 8300

-  CStrings:  10606
+  CStrings:  10704
Symbols:
+ _$s10AppIntents24SyncableEntityIdentifierV06entityE6StringSSvg
+ _$s10AppIntents24SyncableEntityIdentifierV5localACyxq_Gx_tcfC
+ _$s10AppIntents24SyncableEntityIdentifierVMn
+ _$s12CalendarLink11EventEntityV2id10AppIntents08SyncableD10IdentifierVyS2SGvg
+ _NSLocaleScriptCode
+ _dispatch_block_cancel
+ _dispatch_block_create
- _$s10AppIntents25_SyncableEntityIdentifierV5localACyxq_Gx_tcfC
- _$s10AppIntents25_SyncableEntityIdentifierVMn
- _$s10AppIntents25_SyncableEntityIdentifierVyxq_GAA0dE11ConvertibleAAMc
- _$s10AppIntents27EntityIdentifierConvertibleP06entityD6StringSSvgTj
- _$s12CalendarLink11EventEntityV2id10AppIntents09_SyncableD10IdentifierVyS2SGvg
- _CUIKAbbreviatedDayOfWeekForDate
- _CUIKDayOfMonthStringForDate
CStrings:
+ "\f\""
+ "-[UINavigationController(Journalling) _cal_RecursiveBuildJournal:ofViewControllerSubtree:transitioningToTraitCollection:stopCondition:useOuterMostDismissPattern:]"
+ "-[UINavigationController(Journalling) _cal_TearDownAndCreateJournalForTransitioningToTraitCollection:viewHierarchyRoot:useOuterMostDismissPattern:dismissCompletion:]"
+ ".,·"
+ "@\"<JournalRestoreQueueDelegate>\""
+ "@\"JournalRestoreQueue\""
+ "@\"ViewControllerJournal\""
+ "@32@0:8@16@?24"
+ "@44@0:8@16@24B32@?36"
+ "AttendeeDataLoad"
+ "Deva"
+ "EEE"
+ "EEEEE"
+ "EEEEEE"
+ "ExternalFormSheetContentSize"
+ "JournalRestoreQueue"
+ "JournalRestoreQueue completed with failure (timeout)"
+ "JournalRestoreQueue: clearing intermediate %@ before restoring %@"
+ "JournalRestoreQueue: enqueue %@ (allowSameTargetReenqueue=%d)"
+ "JournalRestoreQueue: enqueue called after queue completed. target=%@"
+ "JournalRestoreQueue: failsafe timeout fired after %g seconds. Treating as failed completion."
+ "JournalRestoreQueue: restore completed (success=%d, pendingTarget=%@)"
+ "JournalRestoreQueue: starting restore onto %@"
+ "JournalRestoreQueueDelegate"
+ "Mlym"
+ "No cell for row %ld in group controller %{public}@ with %lu notifications. Reference at that index is %@, and there are %lu shared calendar invitations pending reply."
+ "Op start: %@ [%p] cancelled before start; finishing."
+ "Presentation"
+ "Presenting %@ from %@ (canRequirePush path)"
+ "Pushing %@ onto %@"
+ "Skipping present: parent has no window. parent=%@, shown=%@"
+ "SplitViewWindowRootViewController: decrement called with _activeRestoreQueuePauseCount already at 0"
+ "Starting journal restore on %@, generation %ld, journal=%@"
+ "T@\"NSMutableArray\",R,N,V_sharedCalendarInvitationsReplyPending"
+ "T@\"ViewControllerJournal\",R,N,V_journal"
+ "TB,N,GisPaused,V_paused"
+ "TB,N,V_forceCenteredAlignment"
+ "TB,N,V_insetDividerLine"
+ "Thai"
+ "Tq,N,V_weekdayHeaderStyle"
+ "Tq,R,N,V_generation"
+ "_activeRestoreQueue"
+ "_activeRestoreQueuePauseCount"
+ "_attendeeDataLoadSubTestName"
+ "_attendeeLoadComplete"
+ "_cal_RecursiveBuildJournal:ofViewControllerSubtree:transitioningToTraitCollection:stopCondition:useOuterMostDismissPattern:"
+ "_cal_RecursiveRestoreJournal:generation:withRootVC:topMainVC:model:completion:"
+ "_cal_TearDownAndCreateJournalForTransitioningToTraitCollection:viewHierarchyRoot:useOuterMostDismissPattern:dismissCompletion:"
+ "_cancelFailsafeTimer"
+ "_childInExplicitDisappear"
+ "_clearIntermediatePresentationsFromChild:journal:completion:"
+ "_currentTargetVC"
+ "_dayHeaderFramesUpdatePending"
+ "_decrementActiveRestoreQueuePauseCount"
+ "_dismissJournalPresentationFromPresenter:completion:"
+ "_failsafeBlock"
+ "_failsafeTimeout"
+ "_finishTestIfBothComplete"
+ "_forceCenteredAlignment"
+ "_generation"
+ "_incrementActiveRestoreQueuePauseCount"
+ "_insetDividerLine"
+ "_monthMenuListActionHidden"
+ "_overrideContentSize"
+ "_paused"
+ "_pendingTargetVC"
+ "_presentationComplete"
+ "_presentationSubTestName"
+ "_preventChildLazyLoadReentry"
+ "_pumpIfReady"
+ "_recordJournalForChildVCSwapWithTraitCollection:dismissCompletion:"
+ "_recordJournalForTransitioningToTraitCollection:"
+ "_refreshTodayButtonLabels"
+ "_restoreCompleted:"
+ "_setShowsSeparators:"
+ "_startFailsafeTimer"
+ "_state"
+ "_supplementaryColumnUsesPlatter:"
+ "_supplementaryColumnViewControllerWrappingPaletteNav:forSupplementaryVC:"
+ "_updatePlatterChromeForSupplementaryVC:"
+ "_usesFormSheetPresentation"
+ "_weekdayHeaderStyle"
+ "am"
+ "bn"
+ "cal_RestoreFromJournal:topMainVC:model:completion:"
+ "cal_TearDownAndCreateJournalForChildVCSwapWithTraitCollection:dismissCompletion:"
+ "cancelBeginAppearanceTransition"
+ "characterIsMember:"
+ "constraintLessThanOrEqualToConstant:"
+ "containsViewController:"
+ "convertsDayHeaderFramesToPaletteCoords"
+ "deleteCharactersInRange:"
+ "dismissPresentationsForJournalTeardownWithCompletion:"
+ "ekui_prefersFormSheetPresentation"
+ "enqueueRestoreOntoMainVC:allowSameTargetReenqueue:"
+ "fa"
+ "forceCenteredAlignment"
+ "generation changed (%ld -> %ld), aborting restore chain"
+ "initWithArrangedSubviews:"
+ "initWithJournal:delegate:"
+ "insetDividerLine"
+ "isManagedNavigationControllerLoaded"
+ "isPaused"
+ "journal"
+ "journalRestoreQueue:clearPresentationsFromIntermediateMainVC:completion:"
+ "journalRestoreQueue:didCompleteWithSuccess:"
+ "journalRestoreQueue:performJournalRestore:ontoMainVC:completion:"
+ "kn"
+ "mainViewControllerContainer:didSwapChildViewControllerTo:"
+ "mainViewControllerContainer:willSwapChildViewControllerFrom:"
+ "pa"
+ "paused"
+ "pinnedTrailingGroup"
+ "resetForViewControllerUpdate"
+ "setExternalFormSheetContentSize:"
+ "setFailsafeTimeoutForTesting:"
+ "setForceCenteredAlignment:"
+ "setInsetDividerLine:"
+ "setPaused:"
+ "setSpacing:"
+ "setWeekdayHeaderStyle:"
+ "sharedCalendarInvitationsReplyPending"
+ "stringByTrimmingCharactersInSet:"
+ "te"
+ "ur"
+ "v28@0:8@\"JournalRestoreQueue\"16B24"
+ "v32@0:8@\"MainViewControllerContainer\"16@\"MainViewController\"24"
+ "v40@0:8@\"JournalRestoreQueue\"16@\"MainViewController\"24@?<v@?>32"
+ "v48@0:8@\"JournalRestoreQueue\"16@\"ViewControllerJournal\"24@\"MainViewController\"32@?<v@?B>40"
+ "v52@0:8@16@24@32@?40B48"
+ "v64@0:8@16q24@32@40@48@?56"
+ "weekdayHeaderStyle"
+ "\x81a"
+ "\xb1"
+ "\xf0!1"
- "\r!"
- "-[UINavigationController(Journalling) _cal_RecursiveBuildJournal:ofViewControllerSubtree:transitioningToTraitCollection:stopCondition:]"
- "-[UINavigationController(Journalling) cal_TearDownAndCreateJournalForTransitioningToTraitCollection:viewHierarchyRoot:]"
- "Completion handler for: [%@ showViewController:%@ sender:::]"
- "T@\"UIBarButtonItem\",&,N,V_compactTodayBarButtonItem"
- "T@\"UILabel\",&,N,V_todayButtonDayOfMonthCompact"
- "T@\"UILabel\",&,N,V_todayButtonDayOfWeekCompact"
- "TB,N,V_forceCompactWeekdayInitialsHeader"
- "[_replayJournal:%@ withRootVC:%@ topMainVC:%@]"
- "_cal_RecursiveBuildJournal:ofViewControllerSubtree:transitioningToTraitCollection:stopCondition:"
- "_cal_RecursiveRestoreJournal:withRootVC:topMainVC:model:"
- "_compactTodayBarButtonItem"
- "_forceCompactWeekdayInitialsHeader"
- "_needReloadWhenRefreshCompletes"
- "_reloadsSuspendedUntilRefreshCompletes"
- "_todayButtonDayOfMonthCompact"
- "_todayButtonDayOfWeekCompact"
- "cal_RestoreFromJournal:topMainVC:model:"
- "cal_TearDownAndCreateJournalForTransitioningToTraitCollection:viewHierarchyRoot:"
- "compactTodayBarButtonItem"
- "compactTodayButtonView"
- "defaultFontDescriptorWithTextStyle:"
- "forceCompactWeekdayInitialsHeader"
- "recordJournalForTransitioningToTraitCollection:"
- "setAdjustsFontForContentSizeCategory:"
- "setCompactTodayBarButtonItem:"
- "setForceCompactWeekdayInitialsHeader:"
- "setTodayButtonDayOfMonthCompact:"
- "setTodayButtonDayOfWeekCompact:"
- "shouldWaitForAttendeeLoading"
- "todayButtonDayOfMonthCompact"
- "todayButtonDayOfWeekCompact"
- "updateTodayButtonDayOfWeek:dayOfMonth:compact:"
- "\x81Q"
- "\xc1"
- "\xe1"
- "\xe11"
```
