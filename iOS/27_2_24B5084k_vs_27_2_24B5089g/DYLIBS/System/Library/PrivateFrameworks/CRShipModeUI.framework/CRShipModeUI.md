## CRShipModeUI

> `/System/Library/PrivateFrameworks/CRShipModeUI.framework/CRShipModeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e264` | `0x2ead4` | **`+0x870`** |
| `__TEXT.__cstring` | `0x38a0` | `0x3b80` | **`+0x2e0`** |
| `__AUTH_CONST.__const` | `0x13c0` | `0x1410` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x608` | `0x648` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1139` | `0x1159` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x840` | `0x858` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x968` | `0x980` | **`+0x18`** |
| `__DATA.__data` | `0xd60` | `0xd70` | **`+0x10`** |
| `__TEXT.__const` | `0xd40` | `0xd50` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x6a4` | `0x6b4` | **`+0x10`** |

### Other Changes

```diff

-1307.40.46.0.0
+1307.40.51.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 850
-  Symbols:   235
-  CStrings:  285
+  Functions: 859
+  Symbols:   237
+  CStrings:  307
Symbols:
+ _AnalyticsSendEventLazy
+ _swift_initStackObject
CStrings:
+ "BatteryTrustFailedAlreadyInShipMode"
+ "BatteryTrustFailedBlockedAtEntry"
+ "BranchChosenOtherShipment"
+ "BranchChosenTradeInRepair"
+ "CoreAnalyticsEvent: %{public}s"
+ "EntryResolvedFresh"
+ "EntryResolvedInProgress"
+ "EntryResolvedIneligible"
+ "EntryResolvedReadyToUndo"
+ "EraseChoiceErase"
+ "FlowEndedAborted"
+ "FlowEndedCancelled"
+ "FlowEndedCompleted"
+ "FlowEndedDiscarded"
+ "IneligibleForShipmentShipChargeLimitUnsupported"
+ "PartnerConfirmed"
+ "ScreenSeenCompletion"
+ "ScreenSeenEraseDeviceConfirmation"
+ "ScreenSeenExplanation"
+ "ScreenSeenPartnerConfirmation"
+ "ScreenSeenProgress"
+ "com.apple.corerepair.UI"
```
