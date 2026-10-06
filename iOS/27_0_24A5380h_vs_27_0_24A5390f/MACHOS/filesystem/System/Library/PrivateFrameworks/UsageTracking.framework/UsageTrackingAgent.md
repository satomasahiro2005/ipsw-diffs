## UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x5eb1` | `0x5f41` | **`+0x90`** |
| `__TEXT.__text` | `0x73794` | `0x73810` | **`+0x7c`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x1078` | **`-0x18`** |
| `__DATA.__data` | `0x12e8` | `0x12d8` | **`-0x10`** |
| `__DATA.__objc_const` | `0x3140` | `0x3150` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2410` | `0x2420` | **`+0x10`** |
| `__TEXT.__const` | `0x1ede` | `0x1eee` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1864` | `0x1854` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x138e` | `0x137e` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x450` | `0x440` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x568` | `0x55c` | **`-0xc`** |
| `__DATA.__objc_data` | `0xd40` | `0xd38` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1218` | `0x1220` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2840` | `0x2838` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x860` | `0x858` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x94` | `0x98` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-405.0.0.0.0
+406.0.0.0.0

-  Functions: 1512
-  Symbols:   954
-  CStrings:  1480
+  Functions: 1514
+  Symbols:   953
+  CStrings:  1479
Symbols:
+ _$sScS12ContinuationV15BufferingPolicyO15bufferingNewestyADyx__GSicAFmlFWC
- _$sScS12ContinuationV15BufferingPolicyO9unboundedyADyx__GAFmlFWC
- _$sScSMa
CStrings:
+ "T@\"BPSSink\",&,V_applicationTombstoneSubscription"
+ "T@\"BPSSink\",&,V_intelligenceTombstoneSubscription"
+ "T@\"BPSSink\",&,V_nowPlayingTombstoneSubscription"
+ "T@\"BPSSink\",&,V_videoTombstoneSubscription"
+ "T@\"BPSSink\",&,V_webDomainTombstoneSubscription"
+ "T@\"_TtC18UsageTrackingAgent15SerialProcessor\",R,V_tombstoneDeletedTimeResettingProcessor"
+ "T@\"_TtC18UsageTrackingAgent15SerialProcessor\",R,V_tombstoneDeletedTimeStoringProcessor"
+ "_resetAllDataAndResetBudgetsAfterTombstoneWithCompletionHandler:"
+ "_tombstoneDeletedTimeResettingProcessor"
+ "_tombstoneDeletedTimeStoringProcessor"
+ "tombstoneDeletedTimeResettingProcessor"
+ "tombstoneDeletedTimeStoringProcessor"
- "@\"BPSDrivableSink\""
- "B16@?0@\"BMStoreEvent\"8"
- "T@\"BPSDrivableSink\",&,V_applicationTombstoneSubscription"
- "T@\"BPSDrivableSink\",&,V_intelligenceTombstoneSubscription"
- "T@\"BPSDrivableSink\",&,V_nowPlayingTombstoneSubscription"
- "T@\"BPSDrivableSink\",&,V_videoTombstoneSubscription"
- "T@\"BPSDrivableSink\",&,V_webDomainTombstoneSubscription"
- "T@\"_TtC18UsageTrackingAgent15SerialProcessor\",R,V_deletedTimeSerialProcessor"
- "_deletedTimeSerialProcessor"
- "_resetAllDataAndResetBudgetsAfterTombstone"
- "deletedTimeSerialProcessor"
- "sinkWithCompletion:shouldContinue:"
- "stream"
```
