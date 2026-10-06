## UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x742d0` | `0x7441c` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0x5a86` | `0x5ab6` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1090` | `0x10b8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x2440` | `0x2450` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1230` | `0x1238` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-407.1.4.0.0
+407.1.5.0.0

-  Symbols:   952
-  CStrings:  1486
+  Symbols:   953
+  CStrings:  1487
Symbols:
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
Functions:
~ sub_100035754 : 1956 -> 2252
~ sub_10004b7b4 -> sub_10004b8dc : 32 -> 68
CStrings:
+ "Last refresh was within a minute of now, skipping refresh."
+ "Minutes since last refresh: %{public}ld"
- "Last refresh was less than one minute ago, skipping refresh."
```
