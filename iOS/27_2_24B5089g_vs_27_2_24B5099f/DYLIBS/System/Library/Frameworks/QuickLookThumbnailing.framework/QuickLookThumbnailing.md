## QuickLookThumbnailing

> `/System/Library/Frameworks/QuickLookThumbnailing.framework/QuickLookThumbnailing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x610` | `0x148` | **`-0x4c8`** |
| `__DATA_DIRTY.__data` | `0x80` | `0x548` | **`+0x4c8`** |
| `__TEXT.__text` | `0x319a0` | `0x31e0c` | **`+0x46c`** |
| `__DATA.__bss` | `0x8a0` | `0x940` | **`+0xa0`** |
| `__DATA_DIRTY.__bss` | `0x358` | `0x2b8` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x2d55` | `0x2df5` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x538` | `0x550` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cb0` | `0x1cc8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1088` | `0x1098` | **`+0x10`** |

### Other Changes

```diff

-218.1.1.0.0
+218.1.3.200.0

-  Functions: 1603
-  Symbols:   2471
-  CStrings:  533
+  Functions: 1608
+  Symbols:   2477
+  CStrings:  536
Symbols:
+ _NSFileProtectionCompleteUntilFirstUserAuthentication
+ _NSFileProtectionKey
+ _NSFileProtectionNone
+ _QLTProtectCacheAtLocation
+ _QLTProtectCacheItemAtPath
+ _QLTThumbnailCacheProtectionAttributes
CStrings:
+ "Could not raise the protection class of '%@' to %@: %@"
+ "Could not read the attributes of '%@' to protect it: %@"
+ "Raised the protection class of '%@' to %@"
```
