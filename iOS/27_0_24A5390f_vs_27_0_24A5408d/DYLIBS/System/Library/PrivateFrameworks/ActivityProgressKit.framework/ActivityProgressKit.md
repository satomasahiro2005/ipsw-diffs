## ActivityProgressKit

> `/System/Library/PrivateFrameworks/ActivityProgressKit.framework/ActivityProgressKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25fc` | `0x26d4` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x160` | `0x1a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x125` | `0x165` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x498` | `0x4c8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-390.0.0.0.0
+391.0.0.0.0

-  Functions: 131
-  Symbols:   214
-  CStrings:  15
+  Functions: 133
+  Symbols:   217
+  CStrings:  17
Symbols:
+ -[APKActivityProgress initWithCompletedUnitCount:totalUnitCount:cancelled:shouldHideProgressUI:preserveSubtitleOnFailure:]
+ -[APKActivityProgress preserveSubtitleOnFailure]
+ -[APKActivityProgress setPreserveSubtitleOnFailure:]
+ _OBJC_IVAR_$_APKActivityProgress._preserveSubtitleOnFailure
- -[APKActivityProgress initWithCompletedUnitCount:totalUnitCount:cancelled:shouldHideProgressUI:]
CStrings:
+ "PreserveSubtitleOnFailure"
+ "preserveSubtitleOnFailure"
```
