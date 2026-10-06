## PreviewsFoundationOS

> `/System/Library/PrivateFrameworks/PreviewsFoundationOS.framework/PreviewsFoundationOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143d00` | `0x149404` | **`+0x5704`** |
| `__TEXT.__eh_frame` | `0x7c88` | `0x8120` | **`+0x498`** |
| `__TEXT.__const` | `0xfb8c` | `0xfea4` | **`+0x318`** |
| `__DATA.__bss` | `0xd790` | `0xda90` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0xfc30` | `0xfe90` | **`+0x260`** |
| `__TEXT.__swift5_typeref` | `0x5b57` | `0x5ce3` | **`+0x18c`** |
| `__AUTH.__data` | `0x2520` | `0x26a8` | **`+0x188`** |
| `__TEXT.__unwind_info` | `0x58c8` | `0x5a50` | **`+0x188`** |
| `__TEXT.__swift5_reflstr` | `0x2110` | `0x2270` | **`+0x160`** |
| `__TEXT.__swift5_fieldmd` | `0x3c34` | `0x3d84` | **`+0x150`** |
| `__DATA.__data` | `0x6a08` | `0x6b50` | **`+0x148`** |
| `__TEXT.__cstring` | `0x515b` | `0x528b` | **`+0x130`** |
| `__TEXT.__constg_swiftt` | `0x58e8` | `0x59d8` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x6ec` | `0x7dc` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x31f8` | `0x3298` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x738` | `0x6b8` | **`-0x80`** |
| `__AUTH_CONST.__objc_const` | `0x2728` | `0x2768` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1a70` | `0x1aa8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x2b0` | `0x2d8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x980` | `0x9a0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x1280` | `0x1268` | **`-0x18`** |
| `__TEXT.__swift5_types` | `0x57c` | `0x594` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x1ac` | `0x1c0` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x880` | `0x890` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1c0` | `0x1d0` | **`+0x10`** |

### Other Changes

```diff

-24.0.37.0.0
+24.0.41.0.0

-  Functions: 7945
-  Symbols:   2385
-  CStrings:  418
+  Functions: 8008
+  Symbols:   2414
+  CStrings:  429
Symbols:
+ ___swift_closure_destructor.108Tm
+ ___swift_exist.box.addr_destructor.67Tm
+ ___swift_get_extra_inhabitant_index.74Tm
+ ___swift_store_extra_inhabitant_index.75Tm
+ _associated conformance 20PreviewsFoundationOS17FutureTerminationO12DiscriminantOyx_GSHAASQ
+ _associated conformance 20PreviewsFoundationOS26DiagnosticsCollectionStageO4KindOSHAASQ
+ _objc_retain_x28
+ _symbolic ScTyyt______pG s5ErrorP
+ _symbolic _____ 20PreviewsFoundationOS13StepSchedulerC5State33_B52638DEC558D5A0ADBE6F5887824866LLV
+ _symbolic _____ 20PreviewsFoundationOS17FutureTerminationO12DiscriminantO
+ _symbolic _____ 20PreviewsFoundationOS26DiagnosticsCollectionStageO
+ _symbolic _____ 20PreviewsFoundationOS26DiagnosticsCollectionStageO4KindO
+ _symbolic _____ 20PreviewsFoundationOS26DiagnosticsCollectionStageO8ProgressV
+ _symbolic _____ 20PreviewsFoundationOS4PollV
+ _symbolic _____2id______y______G12continuationt 20PreviewsFoundationOS10IdentifierV ScS12ContinuationV AA26DiagnosticsCollectionStageO
+ _symbolic _____SgXw 20PreviewsFoundationOS23AgentSymbolTableManagerC
+ _symbolic _____SgXwz_Xx 20PreviewsFoundationOS23AgentSymbolTableManagerC
+ _symbolic _____Sg_ABt 10Foundation4DateV
+ _symbolic ______AAt 20PreviewsFoundationOS26DiagnosticsCollectionStageO
+ _symbolic _____ySbG 20PreviewsFoundationOS11UserDefaultV
+ _symbolic _____ySbSg_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____2id______y______G12continuationtG s23_ContiguousArrayStorageC 20PreviewsFoundationOS10IdentifierV ScS12ContinuationV AC26DiagnosticsCollectionStageO
+ _symbolic _____y_____G 20PreviewsFoundationOS21AsyncStreamObservableV AA26DiagnosticsCollectionStageO
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 20PreviewsFoundationOS13StepSchedulerC5State33_B52638DEC558D5A0ADBE6F5887824866LLV
+ _symbolic _____y______G ScS12ContinuationV 20PreviewsFoundationOS26DiagnosticsCollectionStageO
+ _symbolic _____y______G ScS20PreviewsFoundationOSE4SinkV AA26DiagnosticsCollectionStageO
+ _symbolic _____y______GSg ScS12ContinuationV 20PreviewsFoundationOS26DiagnosticsCollectionStageO
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO 20PreviewsFoundationOS26DiagnosticsCollectionStageO
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO 20PreviewsFoundationOS26DiagnosticsCollectionStageO
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 20PreviewsFoundationOS13StepSchedulerC5State33_B52638DEC558D5A0ADBE6F5887824866LLV So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 20PreviewsFoundationOS26DiagnosticsCollectionStageO So16os_unfair_lock_sV
+ _symbolic _____y_____y_______G_____G s13ManagedBufferCsRi__rlE ScS20PreviewsFoundationOSE4SinkV5State33_D30A02C804D374EEAFCBB2947E923937LLV AC26DiagnosticsCollectionStageO So16os_unfair_lock_sV
+ _symbolic xIeghHr_
+ _symbolic y______yyctYbc 20PreviewsFoundationOS17SchedulerIntervalV
+ _type_layout_string 20PreviewsFoundationOS13StepSchedulerC5State33_B52638DEC558D5A0ADBE6F5887824866LLV
+ _type_layout_string 20PreviewsFoundationOS24UserDefaultRepresentableRzlAA0dE0VyxG
- ___swift_closure_destructor.110Tm
- ___swift_exist.box.addr_destructor.69Tm
- ___swift_get_extra_inhabitant_indexTm
- ___swift_store_extra_inhabitant_indexTm
- _associated conformance So8NSStringC20PreviewsFoundationOS25PropertyListRepresentableAC0eF5ValueAcDP_AC0eF4Type
- _symbolic _____ 10Foundation11JSONEncoderC
- _type_layout_string 20PreviewsFoundationOS20DiagnosticsCollectorC5State33_CABFD568AAEEF81D03D1DFDC1F90A1F1LLV
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/FirstSuccess.swift"
+ "Failed to retrieve first error."
+ "Operations required for first success"
+ "[Poll ID: %s]"
+ "[Poll ID: %s] Cancelled Polling"
+ "[Poll ID: %s] Current Time Beyond Limit"
+ "[Poll ID: %s] Finished Polling"
+ "[Poll ID: %s] Received Polled Value: %s"
+ "[Poll ID: %s] Starting polling at: %s and will end before: %s"
+ "cachedValue"
+ "firstSuccess(of:)"
```
