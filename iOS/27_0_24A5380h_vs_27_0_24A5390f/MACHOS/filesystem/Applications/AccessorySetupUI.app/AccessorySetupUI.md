## AccessorySetupUI

> `/Applications/AccessorySetupUI.app/AccessorySetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2550` | `0xa5148` | **`+0x2bf8`** |
| `__DATA.__bss` | `0x18b0` | `0x1bb0` | **`+0x300`** |
| `__TEXT.__const` | `0x2704` | `0x28d4` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x6430` | `0x6550` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x338a` | `0x349a` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x1a33` | `0x1ac3` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x3740` | `0x37c0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x6181` | `0x61e1` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x20d0` | `0x2130` | **`+0x60`** |
| `__DATA.__data` | `0x2a48` | `0x2aa0` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x2bea` | `0x2c32` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x15f8` | `0x1638` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1500` | `0x1538` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x1c78` | `0x1cac` | **`+0x34`** |
| `__TEXT.__swift5_assocty` | `0x1e0` | `0x210` | **`+0x30`** |
| `__DATA.__objc_const` | `0x41f0` | `0x4210` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x15e0` | `0x1600` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x130` | `0x148` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__DATA.__objc_data` | `0x3038` | `0x3048` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1ec0` | `0x1ed0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xf68` | `0xf70` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x728` | `0x730` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x678` | `0x680` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x104` | `0x108` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.27.0.0.0
+2700.30.0.0.0

-  Functions: 2543
-  Symbols:   907
-  CStrings:  1668
+  Functions: 2587
+  Symbols:   909
+  CStrings:  1677
Symbols:
+ _OBJC_CLASS_$_UIApplication
+ _objc_release_x10
CStrings:
+ "App Promotion View: Opening manufacturer URL in browser"
+ "Failed to resolve distributor name for %s: %s"
+ "Resolved alt store name: %s for %s"
+ "discoveryDidTimeout fired but currentClientModel is nil; flow already torn down, ignoring"
+ "distributorBundleID"
+ "fetched asset with adamId: %s, appName: %s, distributor: %s"
+ "manufacturerURL"
+ "openURL:options:completionHandler:"
+ "sharedApplication"
+ "shouldUseManufacturerURLFallback"
- "fetched asset with adamId: %s, appName: %s"
```
