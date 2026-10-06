## Communications-iOS

> `/System/Library/CoreAccessories/PlugIns/Features/Communications-iOS.feature/Communications-iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xf20` | `0xf60` | **`+0x40`** |
| `__TEXT.__cstring` | `0xb01` | `0xb35` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x810` | `0x830` | **`+0x20`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Symbols:   723
-  CStrings:  202
+  Symbols:   727
+  CStrings:  204
Symbols:
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _CFDictionaryCopyKeys
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
- _CFDictionaryGetKeys
CStrings:
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
```
