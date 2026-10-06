## IOMFB_bics_daemon

> `/usr/libexec/IOMFB_bics_daemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f920` | `0x2f354` | **`-0x5cc`** |
| `__DATA.__data` | `0x9b8` | `0xbc8` | **`+0x210`** |
| `__TEXT.__cstring` | `0x4cfc` | `0x4dac` | **`+0xb0`** |
| `__TEXT.__const` | `0x4fc4` | `0x5064` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0xb5c` | `0xaf0` | **`-0x6c`** |
| `__TEXT.__auth_stubs` | `0x13b0` | `0x1370` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0xd18` | `0xcd8` | **`-0x40`** |
| `__DATA.__bss` | `0x16d0` | `0x16a0` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x9f0` | `0x9d0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xec8` | `0xee0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-700.50.66.0.0
+700.50.72.0.0

-  Functions: 972
-  Symbols:   515
-  CStrings:  734
+  Functions: 962
+  Symbols:   511
+  CStrings:  736
Symbols:
- ___cxa_atexit
- ___cxa_guard_abort
- ___cxa_guard_acquire
- ___cxa_guard_release
CStrings:
+ "GenX: Failed to get sensing state: %s\n"
+ "GenX: Sampling aborted, wait for next hour\n"
+ "GenX: Sampling not permitted, wait for next day\n"
+ "GenX: Setting custom timing Sample %d, Hour %d, Day %d\n"
+ "GenX: read_samples %d\n"
+ "GenX: store_samples %d\n"
+ "GenX: trigger_sampling %s\n"
+ "GenXTimingOverrideDay"
+ "GenXTimingOverrideHour"
+ "GenXTimingOverrideSample"
- "GenX: read_samples\n"
- "GenX: store_samples\n"
- "GenX: trigger_sampling\n"
- "Skipping task %s (WIP)\n"
- "save_bicab"
- "save_tbics_history"
- "save_ua_boost"
- "tbics_recovery_lth"
```
