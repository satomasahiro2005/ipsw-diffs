## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fde34` | `0x2fe0f4` | **`+0x2c0`** |
| `__TEXT.__oslogstring` | `0x2409b` | `0x240fb` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1906c` | `0x190ac` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xeca0` | `0xecd0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x13175` | `0x131a5` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xbbe0` | `0xbc00` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1196c` | `0x1198c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xc358` | `0xc370` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x22778` | `0x22788` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2228` | `0x2230` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x5908` | `0x5910` | **`+0x8`** |

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 15196
-  Symbols:   2726
-  CStrings:  5024
+  Functions: 15201
+  Symbols:   2728
+  CStrings:  5027
Symbols:
+ _IMFileTransferPreviewWasForceRegeneratedNotification
+ _IMSharedHelperRegionForcingFilterUnknownSenders
CStrings:
+ "Preview was force regenerated for guid: %@"
+ "Region %s forces unknown filtering"
+ "__kIMFileTransferPreviewWasForceRegeneratedNotification"
```
