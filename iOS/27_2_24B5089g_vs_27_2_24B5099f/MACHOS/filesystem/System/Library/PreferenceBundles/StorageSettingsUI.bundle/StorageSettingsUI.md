## StorageSettingsUI

> `/System/Library/PreferenceBundles/StorageSettingsUI.bundle/StorageSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x897bc` | `0x8a440` | **`+0xc84`** |
| `__TEXT.__cstring` | `0x469b` | `0x47ab` | **`+0x110`** |
| `__DATA_CONST.__cfstring` | `0x1b20` | `0x1b60` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x4960` | `0x49a0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x2b50` | `0x2b88` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x1a18` | `0x1a28` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x3258` | `0x3268` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2600` | `0x2610` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x5765` | `0x5775` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1310` | `0x1318` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1de8` | `0x1df0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-177.1.1.0.0
+177.1.2.0.0

-  Functions: 2523
-  Symbols:   533
-  CStrings:  1744
+  Functions: 2524
+  Symbols:   537
+  CStrings:  1751
Symbols:
+ __ShouldShowInternalUI
+ _cameraVccCapacityDetailID
+ _cameraVccSystemReservedDetailID
+ _os_variant_has_internal_ui
CStrings:
+ "Label in Pro Video Storage detail view, size of the capacity set by the user"
+ "Label in Pro Video Storage detail view, size reserved by the system on top of the capacity"
+ "System Reserved Space"
+ "com.apple.camera.vcc.capacity"
+ "com.apple.camera.vcc.systemReserved"
+ "isVisible"
+ "vccDetails"
```
