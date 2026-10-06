## MobileTimer

> `/System/Library/PrivateFrameworks/MobileTimer.framework/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1352a4` | `0x135d4c` | **`+0xaa8`** |
| `__AUTH_CONST.__const` | `0x5b88` | `0x5c68` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0xe9fc` | `0xea84` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x1cc4` | `0x1d20` | **`+0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0x67f8` | `0x6830` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x5060` | `0x5098` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x2c208` | `0x2c238` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x12d63` | `0x12d93` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5988` | `0x59a0` | **`+0x18`** |
| `__TEXT.__const` | `0x21c0` | `0x21d0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x99b2` | `0x99c2` | **`+0x10`** |
| `__AUTH.__data` | `0x7b8` | `0x7b0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x1134` | `0x113c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa18` | `0xa1c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1b4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1b4` | `0x1b8` | **`+0x4`** |

### Other Changes

```diff

-2328.0.0.0.0
+2329.0.0.0.0

-  Functions: 7870
-  Symbols:   9944
-  CStrings:  2851
+  Functions: 7893
+  Symbols:   9960
+  CStrings:  2852
Symbols:
+ +[MTAnalyticsCoordinator testCoordinatorWithAlarmStorage:persistence:reportsManager:currentDateProvider:]
+ -[MTAnalyticsCoordinator currentDateProvider]
+ -[MTAnalyticsCoordinator fetchPendingReportConcernsWithCompletion:]
+ -[MTAnalyticsCoordinator initWithAlarmStorage:dataStore:persistence:reportsManager:currentDateProvider:]
+ -[MTAnalyticsCoordinator isDataStoreReady]
+ -[MTAnalyticsCoordinator loadDataStore]
+ -[MTAnalyticsCoordinator saveReport:completion:]
+ -[MTAnalyticsCoordinator setCurrentDateProvider:]
+ -[MTStoredReportValue isValid]
+ _OBJC_IVAR_$_MTAnalyticsCoordinator._currentDateProvider
+ __OBJC_$_CLASS_METHODS_MTAnalyticsCoordinator
+ ___104-[MTAnalyticsCoordinator initWithAlarmStorage:dataStore:persistence:reportsManager:currentDateProvider:]_block_invoke
+ ___48-[MTAnalyticsCoordinator saveReport:completion:]_block_invoke
+ ___67-[MTAnalyticsCoordinator fetchPendingReportConcernsWithCompletion:]_block_invoke
+ ___69-[MTAnalyticsCoordinator initWithAlarmStorage:dataStore:persistence:]_block_invoke
+ ___block_descriptor_40_e8_32s_e50_24?0"<MTStoredReport>"8"NSMutableDictionary"16ls32l8
+ ___swift_closure_destructor.104Tm
+ ___swift_closure_destructor.118Tm
+ ___swift_closure_destructor.151Tm
+ ___swift_closure_destructor.157Tm
+ ___swift_closure_destructor.166Tm
+ ___swift_closure_destructor.175Tm
+ ___swift_closure_destructor.184Tm
+ ___swift_closure_destructor.193Tm
+ ___swift_closure_destructor.202Tm
+ ___swift_closure_destructor.211Tm
+ ___swift_closure_destructor.281Tm
+ ___swift_closure_destructor.301Tm
+ ___swift_closure_destructor.310Tm
+ ___swift_closure_destructor.337Tm
+ ___swift_closure_destructor.396Tm
+ ___swift_closure_destructor.423Tm
+ ___swift_closure_destructor.429Tm
+ ___swift_closure_destructor.471Tm
+ ___swift_closure_destructor.77Tm
+ ___swift_closure_destructor.86Tm
+ ___swift_closure_destructor.95Tm
+ _symbolic Ieg_Sg
- ___37-[MTAnalyticsCoordinator saveReport:]_block_invoke
- ___block_descriptor_40_e8_32s_e44_24?0"MTCDReport"8"NSMutableDictionary"16ls32l8
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.152Tm
- ___swift_closure_destructor.161Tm
- ___swift_closure_destructor.165Tm
- ___swift_closure_destructor.179Tm
- ___swift_closure_destructor.188Tm
- ___swift_closure_destructor.197Tm
- ___swift_closure_destructor.206Tm
- ___swift_closure_destructor.276Tm
- ___swift_closure_destructor.296Tm
- ___swift_closure_destructor.305Tm
- ___swift_closure_destructor.332Tm
- ___swift_closure_destructor.391Tm
- ___swift_closure_destructor.418Tm
- ___swift_closure_destructor.424Tm
- ___swift_closure_destructor.466Tm
- ___swift_closure_destructor.72Tm
- ___swift_closure_destructor.81Tm
- ___swift_closure_destructor.90Tm
- ___swift_closure_destructor.99Tm
CStrings:
+ "%{public}@ skipping report with invalid date: %{public}@"
+ "@24@?0@\"<MTStoredReport>\"8@\"NSMutableDictionary\"16"
- "@24@?0@\"MTCDReport\"8@\"NSMutableDictionary\"16"
```
