## SensorKitUI

> `/System/Library/PrivateFrameworks/SensorKitUI.framework/SensorKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1ce0` | `0x1d20` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x2150` | `0x2170` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1a7e` | `0x1a9e` | **`+0x20`** |
| `__TEXT.__text` | `0xbb94` | `0xbbb4` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x173c` | `0x1754` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1300` | `0x1310` | **`+0x10`** |

### Other Changes

```diff

-1038.0.0.0.0
+1039.0.1.0.0

-  Functions: 332
-  Symbols:   794
-  CStrings:  300
+  Functions: 334
+  Symbols:   796
+  CStrings:  302
Symbols:
+ -[SRAuthorizationGroup customSymbolName]
+ -[SRAuthorizationGroup symbolName]
CStrings:
+ "SRCustomSymbolName"
+ "SRSymbolName"
```
