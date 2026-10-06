## accessoryupdaterd

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/Support/accessoryupdaterd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f6dc` | `0x4f860` | **`+0x184`** |
| `__TEXT.__oslogstring` | `0x6b2b` | `0x6b8f` | **`+0x64`** |
| `__TEXT.__objc_stubs` | `0x7800` | `0x7820` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x9579` | `0x9598` | **`+0x1f`** |
| `__DATA.__objc_selrefs` | `0x2428` | `0x2430` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x430` | `0x438` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x12f8` | `0x1300` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 2198
-  Symbols:   419
-  CStrings:  3635
+  Functions: 2200
+  Symbols:   420
+  CStrings:  3638
Symbols:
+ _NSURLIsExcludedFromBackupKey
CStrings:
+ "%s: Failed to exclude datavault directory from backup with error %@"
+ "%s: Unknown supported accessory"
+ "setResourceValue:forKey:error:"
```
