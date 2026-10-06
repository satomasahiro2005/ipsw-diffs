## com.apple.quicklook.ThumbnailsAgent

> `/System/Library/Frameworks/QuickLookThumbnailing.framework/Support/com.apple.quicklook.ThumbnailsAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x167c` | `0x17c4` | **`+0x148`** |
| `__TEXT.__objc_methname` | `0xb50` | `0xbc0` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x6e0` | `0x740` | **`+0x60`** |
| `__TEXT.__cstring` | `0xcf` | `0x104` | **`+0x35`** |
| `__DATA.__objc_const` | `0x428` | `0x458` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x390` | `0x3c0` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2f0` | `0x308` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1d8` | `0x1f0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xb0` | `0xc8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x37c` | `0x394` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x468` | `0x475` | **`+0xd`** |
| `__DATA.__objc_ivar` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-215.0.0.0.0
+216.0.0.0.0

-  Functions: 45
-  Symbols:   87
-  CStrings:  174
+  Functions: 47
+  Symbols:   93
+  CStrings:  182
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ _SecTaskCopyValueForEntitlement
+ ___NSArray0__struct
+ ___NSDictionary0__struct
+ _objc_opt_class
+ _objc_opt_isKindOfClass
CStrings:
+ "B"
+ "TB,V_cacheInspectionAllowed"
+ "_cacheInspectionAllowed"
+ "boolValue"
+ "cacheInspectionAllowed"
+ "com.apple.private.quicklook.thumbnailcache.inspector"
+ "setCacheInspectionAllowed:"
+ "v20@0:8B16"
```
