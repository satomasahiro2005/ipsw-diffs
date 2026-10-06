## bluetoothuserd

> `/usr/libexec/bluetoothuserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f4c8` | `0x6eff0` | **`-0x4d8`** |
| `__TEXT.__eh_frame` | `0x1588` | `0x14b8` | **`-0xd0`** |
| `__TEXT.__unwind_info` | `0x13d0` | `0x13a0` | **`-0x30`** |
| `__DATA.__data` | `0x2440` | `0x2450` | **`+0x10`** |
| `__TEXT.__const` | `0x2e48` | `0x2e38` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x558` | `0x550` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x15d2` | `0x15da` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x94` | `0x8c` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x64` | `0x5c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-2700.41.1.1.0
+2700.43.0.0.0

-  Functions: 1811
-  Symbols:   836
+  Functions: 1804
+  Symbols:   835
Symbols:
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
- _swift_retain_x9
CStrings:
+ "FindNearbyLocalFindableAccessoryExtendedRange"
- "bluetoothuserd/Transaction.swift"
```
