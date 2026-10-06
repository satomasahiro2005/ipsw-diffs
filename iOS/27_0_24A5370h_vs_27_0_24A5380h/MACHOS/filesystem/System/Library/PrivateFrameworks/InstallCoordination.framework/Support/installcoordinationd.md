## installcoordinationd

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e888` | `0x8e9bc` | **`+0x134`** |
| `__TEXT.__cstring` | `0x1609d` | `0x161bd` | **`+0x120`** |
| `__DATA_CONST.__cfstring` | `0x84a0` | `0x8540` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x498` | `0x4f8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xcdf5` | `0xce35` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0xf5ab` | `0xf5cb` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xa040` | `0xa060` | **`+0x20`** |
| `__DATA.__objc_const` | `0x94a0` | `0x94b0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4d64` | `0x4d74` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2f60` | `0x2f68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2360` | `0x2368` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-837.0.0.0.0
+840.0.0.0.0

-  Functions: 2985
+  Functions: 2986

-  CStrings:  4916
+  CStrings:  4923
CStrings:
+ "%s: Failed to resolve persona for %@: %@; proceeding with uninstall anyway"
+ "00:20:57"
+ "Jun 26 2026"
+ "This App Cannot Be Deleted"
+ "UNINSTALL_ICON_BODY_RESTRICTED_BY_APP_MANAGED_FEATURES"
+ "UNINSTALL_ICON_TITLE_RESTRICTED_BY_APP_MANAGED_FEATURES"
+ "While this device is under contract, this app will stay installed to help you manage your payments."
+ "appHasAppManagedFeaturesEntitlement"
+ "com.apple.developer.appmanagedfeatures"
- "18:58:40"
- "Jun  9 2026"
```
