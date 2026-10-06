## DataDetectorsUI

> `/System/Library/PrivateFrameworks/DataDetectorsUI.framework/DataDetectorsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52a5c` | `0x508c4` | **`-0x2198`** |
| `__AUTH_CONST.__cfstring` | `0x6880` | `0x6ba0` | **`+0x320`** |
| `__TEXT.__cstring` | `0x5b8c` | `0x5cec` | **`+0x160`** |
| `__DATA.__bss` | `0x20` | `0x158` | **`+0x138`** |
| `__TEXT.__objc_methlist` | `0x4d08` | `0x4e38` | **`+0x130`** |
| `__DATA_DIRTY.__bss` | `0x158` | `0x38` | **`-0x120`** |
| `__DATA_CONST.__const` | `0xec0` | `0xf58` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x7ae0` | `0x7b70` | **`+0x90`** |
| `__TEXT.__const` | `0x280` | `0x2e0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3378` | `0x33c8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1488` | `0x14c8` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xd78` | `0xd90` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x4a8` | `0x4b4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xa68` | `0xa70` | **`+0x8`** |

### Other Changes

```diff

-609.0.0.0.0
+611.0.0.0.0

-  Functions: 1904
-  Symbols:   3677
-  CStrings:  1086
+  Functions: 1935
+  Symbols:   3778
+  CStrings:  1111
Symbols:
+ -[DDAction menuAccessibilityIdentifier]
+ -[DDAddEventAction menuAccessibilityIdentifier]
+ -[DDAddToAddressBookAction menuAccessibilityIdentifier]
+ -[DDAddToReadingListAction menuAccessibilityIdentifier]
+ -[DDCallAction userDidNotPickAProvider]
+ -[DDConversionAction menuAccessibilityIdentifier]
+ -[DDCopyAction menuAccessibilityIdentifier]
+ -[DDCreateReminderAction menuAccessibilityIdentifier]
+ -[DDDataDetectorInterceptReporter .cxx_destruct]
+ -[DDDataDetectorInterceptReporter bundleID]
+ -[DDDataDetectorInterceptReporter safariTapToCall]
+ -[DDDataDetectorInterceptReporter setBundleID:]
+ -[DDDataDetectorInterceptReporter setSafariTapToCall:]
+ -[DDDataDetectorInterceptReporter setThirdParty:]
+ -[DDDataDetectorInterceptReporter stringForOption:]
+ -[DDDataDetectorInterceptReporter thirdParty]
+ -[DDDirectionsAction menuAccessibilityIdentifier]
+ -[DDFaceTimeAction menuAccessibilityIdentifier]
+ -[DDFaceTimeAudioAction menuAccessibilityIdentifier]
+ -[DDFlightAction menuAccessibilityIdentifier]
+ -[DDOpenMapsAction menuAccessibilityIdentifier]
+ -[DDOpenURLAction menuAccessibilityIdentifier]
+ -[DDSearchWebAction menuAccessibilityIdentifier]
+ -[DDSendMailAction menuAccessibilityIdentifier]
+ -[DDShareAction menuAccessibilityIdentifier]
+ -[DDShowCalendarAction menuAccessibilityIdentifier]
+ -[DDTelephoneNumberAction menuAccessibilityIdentifier]
+ -[DDTextMessageAction defaultAppClientAdoptionReady]
+ -[DDTextMessageAction defaultSMSAppIsMessages]
+ -[DDTextMessageAction localizedShowInMessages]
+ -[DDTextMessageAction menuAccessibilityIdentifier]
+ -[DDTrackShipmentAction menuAccessibilityIdentifier]
+ -[NSURL dd_emailFromTelScheme]
+ GCC_except_table105
+ GCC_except_table12
+ GCC_except_table14
+ GCC_except_table145
+ GCC_except_table24
+ GCC_except_table26
+ GCC_except_table75
+ GCC_except_table93
+ _DDTrackEventCreationInHostApplication.host
+ _DDTrackEventCreationInHostApplication.onceToken
+ _DDTrackEventCreationInHostApplication.track
+ _DDUISimulateCrash
+ _LoadCrashSupportIfNecessary.__CrashReportHandle
+ _OBJC_IVAR_$_DDDataDetectorInterceptReporter._bundleID
+ _OBJC_IVAR_$_DDDataDetectorInterceptReporter._safariTapToCall
+ _OBJC_IVAR_$_DDDataDetectorInterceptReporter._thirdParty
+ __CNPropertyNameForResult.mapping
+ __CNPropertyNameForResult.sOnce
+ __DefaultRuneLocale
+ ___DDPerformWebSearchFromQuery_block_invoke
+ ___maskrune
+ ___tolower
+ __addressStringForResult
+ __copy_entitlement_value
+ __extensionAuxiliaryHostProtocol.__interface
+ __extensionAuxiliaryHostProtocol.onceToken
+ __extensionAuxiliaryVendorProtocol.__interface
+ __extensionAuxiliaryVendorProtocol.onceToken
+ __isDataDetectorLinkNode
+ __isLinkNode
+ __lookupTextForText:.onceToken
+ __lookupTextForText:.undesirableChars
+ __sTransientAttributesSet
+ __supportsBusinessService
+ _actionsWithURL:result:context:._isUPIEnabled
+ _actionsWithURL:result:context:.onceToken
+ _analyticsQueue.onceToken
+ _analyticsQueue.queue
+ _appLink.entitled
+ _appLink.onceToken
+ _controllerIsAvailable._available
+ _controllerIsAvailable.onceToken
+ _dd_callsRequireExternalPrompt._notAllowed
+ _dd_callsRequireExternalPrompt.onceToken
+ _dd_canReadDefaultBrowser._isEntitled
+ _dd_canReadDefaultBrowser.onceToken
+ _dd_hostApplicationCanListCallProviders.hostApplicationCanListCallProviders
+ _dd_hostApplicationCanListCallProviders.onceToken
+ _dd_isInternalInstall.isInternalInstall
+ _dd_isInternalInstall.onceToken
+ _dd_isLSTrusted._trusted
+ _dd_isLSTrusted.onceToken
+ _dd_transientAttributesSet
+ _dd_transientAttributesSet.onceToken
+ _feedbackListener._session
+ _feedbackListener.once
+ _kDDAddToCalendarAccessibilityIdentifier
+ _kDDAddToContactsAccessibilityIdentifier
+ _kDDAddToReadingListAccessibilityIdentifier
+ _kDDCallAccessibilityIdentifier
+ _kDDConversionAccessibilityIdentifier
+ _kDDCopyAccessibilityIdentifier
+ _kDDCreateReminderAccessibilityIdentifier
+ _kDDFaceTimeAccessibilityIdentifier
+ _kDDFaceTimeAudioAccessibilityIdentifier
+ _kDDGetDirectionsAccessibilityIdentifier
+ _kDDOpenMapsAccessibilityIdentifier
+ _kDDOpenURLAccessibilityIdentifier
+ _kDDPreviewFlightAccessibilityIdentifier
+ _kDDSearchWebAccessibilityIdentifier
+ _kDDSendMailAccessibilityIdentifier
+ _kDDShareAccessibilityIdentifier
+ _kDDShowInCalendarAccessibilityIdentifier
+ _kDDTextMessageAccessibilityIdentifier
+ _kDDTrackShipmentAccessibilityIdentifier
+ _linkAncestorOfNode
+ _sharedController._sSharedController
+ _sharedController.once
+ _unitWithIdentifier:._supportedGroups
+ _unitWithIdentifier:._supportedUnits
+ _unitWithIdentifier:.onceToken
- GCC_except_table102
- GCC_except_table11
- GCC_except_table13
- GCC_except_table140
- GCC_except_table23
- GCC_except_table4
- GCC_except_table74
- GCC_except_table8
- GCC_except_table90
- _OUTLINED_FUNCTION_12
- _OUTLINED_FUNCTION_13
- ___isinfd
- ___isnand
CStrings:
+ "%C"
+ "DD"
+ "arrow.trianglehead.turn.up.right"
+ "bundle_id"
+ "calendar.day"
+ "dd-%@"
+ "dd-add-to-calendar"
+ "dd-add-to-contacts"
+ "dd-add-to-reading-list"
+ "dd-call"
+ "dd-conversion"
+ "dd-copy"
+ "dd-create-reminder"
+ "dd-facetime"
+ "dd-facetime-audio"
+ "dd-get-directions"
+ "dd-open-maps"
+ "dd-open-url"
+ "dd-preview-flight"
+ "dd-search-web"
+ "dd-send-mail"
+ "dd-share"
+ "dd-show-in-calendar"
+ "dd-text-message"
+ "dd-track-shipment"
+ "safari_tap_to_call"
+ "third_party"
- "arrow.triangle.turn.up.right.circle"
- "calendar.badge.plus"
```
