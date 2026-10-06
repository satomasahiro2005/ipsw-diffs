## MobileCalSettings

> `/System/Library/PreferenceBundles/MobileCalSettings.bundle/MobileCalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10078` | `0x100cc` | **`+0x54`** |
| `__TEXT.__objc_methname` | `0x416f` | `0x41af` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x2b20` | `0x2b60` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x10a8` | `0x10b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x112c` | `0x1134` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-29906.0.0.0.0
+29909.0.0.0.0

-  Functions: 308
+  Functions: 309

-  CStrings:  945
+  CStrings:  947
Functions:
~ sub_7d1c : 96 -> 84
+ sub_7d70
CStrings:
+ "_resolvedMagicComposeAvailability"
+ "isMagicComposeRestrictedByMDM"
```
