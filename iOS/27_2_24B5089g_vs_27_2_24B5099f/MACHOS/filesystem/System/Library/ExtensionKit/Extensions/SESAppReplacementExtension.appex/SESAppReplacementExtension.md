## SESAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/SESAppReplacementExtension.appex/SESAppReplacementExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a58` | `0x1c50` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x208` | `0x260` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x3c0` | `0x3f0` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x160` | `0x180` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1e8` | `0x200` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x21c` | `0x227` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x108` | `0x110` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-71.8.0.0.0
+71.9.0.0.0

-  Symbols:   70
-  CStrings:  67
+  Symbols:   73
+  CStrings:  69
Symbols:
+ _objc_release_x24
+ _objc_release_x26
+ _objc_release_x27
Functions:
~ sub_100002890 : 1328 -> 1832
CStrings:
+ "Skipping app extension replacement %{public}s -> %{public}s; nothing to migrate"
+ "entityType"
```
