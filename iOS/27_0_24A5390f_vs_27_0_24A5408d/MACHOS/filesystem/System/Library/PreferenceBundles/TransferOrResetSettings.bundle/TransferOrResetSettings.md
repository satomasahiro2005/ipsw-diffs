## TransferOrResetSettings

> `/System/Library/PreferenceBundles/TransferOrResetSettings.bundle/TransferOrResetSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xab90` | `0xaf38` | **`+0x3a8`** |
| `__TEXT.__objc_stubs` | `0x1d00` | `0x1d80` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1f23` | `0x1f9a` | **`+0x77`** |
| `__TEXT.__oslogstring` | `0x5f4` | `0x63e` | **`+0x4a`** |
| `__DATA.__objc_selrefs` | `0x988` | `0x9b0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x190` | `0x1b4` | **`+0x24`** |
| `__DATA.__objc_const` | `0xb08` | `0xaf8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0xa60` | `0xa70` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x540` | `0x548` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x74c` | `0x754` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.0.4.0.0
+2027.0.7.0.0

-  Functions: 202
-  Symbols:   277
-  CStrings:  554
+  Functions: 203
+  Symbols:   278
+  CStrings:  560
Symbols:
+ _objc_retain_x24
CStrings:
+ "ResetNetworkSettings deep link: RESET_NETWORK_LABEL specifier unavailable"
+ "_presentResetActionSheetWithSpecifiers:"
+ "addObjectsFromArray:"
+ "array"
+ "arrayWithArray:"
+ "showResetNetworkSettingsActionSheet"
```
