## DeviceDiscoveryUISettings

> `/System/Library/Settings/DeviceDiscoveryUISettings.settings/DeviceDiscoveryUISettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1503c` | `0x150a4` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xd40` | `0xd50` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x6a8` | `0x6b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2131.10.1.2.11
+2131.20.65.2.1

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 337
-  Symbols:   149
-  CStrings:  69
+  Functions: 338
+  Symbols:   152
+  CStrings:  70
Symbols:
+ _ResetWiFiIdentifierButtonTitle
+ ___CFConstantStringClassReference
+ _objc_claimAutoreleasedReturnValue
CStrings:
+ ""
```
