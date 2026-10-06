## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25314` | `0x254ec` | **`+0x1d8`** |
| `__TEXT.__cstring` | `0x9861` | `0x995c` | **`+0xfb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1598.0.6.0.0
+1598.40.4.0.0

-  CStrings:  2194
+  CStrings:  2207
Functions:
~ sub_100010c14 : 432 -> 436
~ sub_100012118 -> sub_10001211c : 68172 -> 68640
CStrings:
+ "debugDataCompressionFailed"
+ "debugDataDumpSuccess"
+ "debugDataGetFail"
+ "debugDataGetSuccess"
+ "debugDataHandoffToRxBurn"
+ "debugDataRequestDropped"
+ "debugDataRequestDump"
+ "debugDataTrimCalled"
+ "idleStackFlowVCurveCDPAtSlowGC"
+ "sanitizeDoneTime"
+ "sanitizeReject"
+ "sanitizeStartTime"
+ "sanitizeStatus"
+ "timer_read64_synced"
- "idleStackPurgeableValidityCurveAtSlowGC"
```
