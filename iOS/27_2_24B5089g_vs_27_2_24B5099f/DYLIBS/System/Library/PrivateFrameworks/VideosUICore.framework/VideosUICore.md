## VideosUICore

> `/System/Library/PrivateFrameworks/VideosUICore.framework/VideosUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35700` | `0x3581c` | **`+0x11c`** |
| `__AUTH_CONST.__cfstring` | `0x6340` | `0x6380` | **`+0x40`** |
| `__TEXT.__cstring` | `0x34b5` | `0x34df` | **`+0x2a`** |
| `__DATA_CONST.__objc_selrefs` | `0x3cb0` | `0x3cd8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x568c` | `0x56a4` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1f00` | `0x1f08` | **`+0x8`** |

### Other Changes

```diff

-1145.10.22.0.1
+1145.10.26.0.0

-  Functions: 1883
-  Symbols:   3694
-  CStrings:  963
+  Functions: 1885
+  Symbols:   3697
+  CStrings:  965
Symbols:
+ +[UIScreen(VideosUICore) vui_activeSceneWindow]
+ +[UIScreen(VideosUICore) vui_activeWindowScene]
+ _VUIDefaultsOfflineKeyRenewalPeriodInSeconds
CStrings:
+ "KeyColor"
+ "OfflineKeyRenewalPeriodInSeconds"
```
