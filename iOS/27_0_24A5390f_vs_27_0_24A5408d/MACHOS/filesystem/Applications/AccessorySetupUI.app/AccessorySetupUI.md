## AccessorySetupUI

> `/Applications/AccessorySetupUI.app/AccessorySetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa5148` | `0xa5c6c` | **`+0xb24`** |
| `__TEXT.__oslogstring` | `0x349a` | `0x356a` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x37c0` | `0x3800` | **`+0x40`** |
| `__DATA.__data` | `0x2aa0` | `0x2ad0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x6550` | `0x6578` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x61e1` | `0x6201` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1538` | `0x1550` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1600` | `0x1610` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1ed0` | `0x1ec0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xf70` | `0xf68` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.30.0.0.0
+2700.34.0.0.0

-  Functions: 2587
-  Symbols:   909
-  CStrings:  1677
+  Functions: 2592
+  Symbols:   908
+  CStrings:  1682
Symbols:
- _dlclose
CStrings:
+ "createViewModel: no client model for %s, dismissing"
+ "error saving activating state for app-required device: %@"
+ "persistProximityActivatingState: no proximity discovery for device %s"
+ "requiresCompanionApp"
+ "resolvedDisplayImageFileURL"
+ "setState:"
- "displayImageFileURL"
```
