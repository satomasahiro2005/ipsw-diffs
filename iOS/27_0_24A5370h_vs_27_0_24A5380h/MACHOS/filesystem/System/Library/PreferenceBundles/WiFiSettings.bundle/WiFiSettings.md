## WiFiSettings

> `/System/Library/PreferenceBundles/WiFiSettings.bundle/WiFiSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xd20` | `0xd30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x698` | `0x6a0` | **`+0x8`** |
| `__TEXT.__text` | `0xbd4c` | `0xbd50` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1205.59.4.1.0
+1205.63.4.1.0

-  Symbols:   166
+  Symbols:   167
Symbols:
+ _swift_bridgeObjectRetain_n
Functions:
~ sub_2f6c : 2776 -> 2764
~ sub_cc44 -> sub_cc38 : 1008 -> 1024
```
