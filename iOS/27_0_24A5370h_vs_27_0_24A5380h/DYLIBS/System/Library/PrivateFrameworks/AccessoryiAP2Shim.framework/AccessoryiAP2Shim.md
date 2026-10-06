## AccessoryiAP2Shim

> `/System/Library/PrivateFrameworks/AccessoryiAP2Shim.framework/AccessoryiAP2Shim`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1600` | `0x1640` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1051` | `0x1085` | **`+0x34`** |
| `__TEXT.__text` | `0xc050` | `0xc080` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x938` | `0x958` | **`+0x20`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Symbols:   826
-  CStrings:  330
+  Symbols:   830
+  CStrings:  332
Symbols:
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
Functions:
~ _systemInfo_copyProductType : 72 -> 96
~ _systemInfo_copyProductVersion : 72 -> 96
CStrings:
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
```
