## MobileBackupCacheDeleteService

> `/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackupCacheDeleteService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12768` | `0x12958` | **`+0x1f0`** |
| `__TEXT.__objc_methname` | `0x2624` | `0x2666` | **`+0x42`** |
| `__TEXT.__const` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa28` | `0xa30` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x858` | `0x860` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3038.0.0.0.0
+3039.0.1.0.0

-  Functions: 339
+  Functions: 340

-  CStrings:  847
+  CStrings:  848
Functions:
~ sub_100007340 : 452 -> 496
+ sub_100007530
CStrings:
+ "createIncompleteRestoreDirectoriesWithError:"
+ "removeIncompleteRestoreDirectoriesWithError:"
+ "removeIntermediateRestoreDirectoriesWithError:"
- "cleanupRestoreDirectoriesWithError:"
- "createRestoreDirectoriesWithError:"
```
