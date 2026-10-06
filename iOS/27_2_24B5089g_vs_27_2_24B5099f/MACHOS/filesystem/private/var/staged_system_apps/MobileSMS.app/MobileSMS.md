## MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c6e0` | `0x1c4d0` | **`-0x210`** |
| `__TEXT.__cstring` | `0x238e` | `0x231a` | **`-0x74`** |
| `__TEXT.__objc_methname` | `0x4f04` | `0x4ec0` | **`-0x44`** |
| `__DATA.__objc_const` | `0x850` | `0x880` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x33e0` | `0x33c0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x798` | `0x778` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x8e0` | `0x8f0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xc4e` | `0xc5b` | **`+0xd`** |
| `__DATA_CONST.__auth_got` | `0x480` | `0x488` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 517
-  Symbols:   326
-  CStrings:  1320
+  Functions: 518
+  Symbols:   328
+  CStrings:  1322
Symbols:
+ _clock_gettime_nsec_np
+ _kShowMessagesSuperUserTest
CStrings:
+ "TQ,N,V_pptLaunchStartTime"
+ "TimeToType"
+ "TimeToTypeSpringboard"
+ "_pptLaunchStartTime"
+ "launchToType"
+ "launchToTypeUnits"
+ "numberWithDouble:"
+ "pptLaunchStartTime"
+ "s"
+ "setPptLaunchStartTime:"
+ "startTimeToTypeSpringboardTest:"
+ "v24@0:8Q16"
- "Bottom inset > IAV height (KB up)"
- "IAV height %.2f"
- "IAV height > 44.0 (IAV is expanded)"
- "Transcript controller returned nil IAV, FAIL"
- "Transcript vending IAV"
- "bottom inset %.2f. IAV %.2f"
- "inputAccessoryView"
- "validateBottomInsetGreaterThanIAVHeight:expected:withResultsDictionary:"
- "validateIAVisExpanded:expected:withResultsDictionary:"
- "validateTranscriptVendingIAV:expected:withResultsDictionary:"
```
