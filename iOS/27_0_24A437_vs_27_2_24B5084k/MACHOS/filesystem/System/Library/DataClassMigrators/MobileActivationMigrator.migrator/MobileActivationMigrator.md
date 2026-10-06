## MobileActivationMigrator

> `/System/Library/DataClassMigrators/MobileActivationMigrator.migrator/MobileActivationMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x5340` | `0x5360` | **`+0x20`** |
| `__TEXT.__cstring` | `0x34c3` | `0x34dd` | **`+0x1a`** |
| `__DATA_CONST.__objc_arraydata` | `0x5a0` | `0x5a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1145.0.1.0.1
+1145.40.4.0.0

-  CStrings:  843
+  CStrings:  844
CStrings:
+ "ACCHWComponentAuthService"
```
