## FindingUI

> `/Applications/FindingUI.app/FindingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x1f00` | `0x1f50` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x3370` | `0x3330` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x758` | `0x784` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x1026` | `0x1050` | **`+0x2a`** |
| `__TEXT.__text` | `0x5fc8c` | `0x5fc70` | **`-0x1c`** |
| `__TEXT.__auth_stubs` | `0x1d90` | `0x1da0` | **`+0x10`** |
| `__TEXT.__const` | `0x2ac4` | `0x2ab4` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xed0` | `0xed8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x558` | `0x550` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1440` | `0x1438` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x2f8` | `0x2f4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x100` | `0xfc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-103.30.6.7.1
+104.30.6.14.3

-  Functions: 1336
+  Functions: 1338
Symbols:
+ _$sSo17OS_dispatch_queueC8DispatchE4mainABvgZ
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Not dismissing. Not showing person %s"
- "Not dismissing, not showing person %s"
```
