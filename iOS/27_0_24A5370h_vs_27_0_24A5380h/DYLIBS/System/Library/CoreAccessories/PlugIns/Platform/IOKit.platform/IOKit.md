## IOKit

> `/System/Library/CoreAccessories/PlugIns/Platform/IOKit.platform/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1280` | `0x12c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x11d4` | `0x1208` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x828` | `0x848` | **`+0x20`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Symbols:   897
-  CStrings:  307
+  Symbols:   901
+  CStrings:  309
Symbols:
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
CStrings:
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
```
