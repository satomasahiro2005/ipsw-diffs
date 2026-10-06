## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3c2e` | `0x3c96` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x3a60` | `0x3ac0` | **`+0x60`** |
| `__TEXT.__text` | `0x26300` | `0x26334` | **`+0x34`** |
| `__DATA.__bss` | `0x178` | `0x148` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x38` | `0x68` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1f70` | `0x1f98` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x138` | `0x140` | **`+0x8`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Symbols:   1863
-  CStrings:  861
+  Symbols:   1868
+  CStrings:  864
Symbols:
+ _ACCTransportEANative_SessionSocketReadyNotification
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
Functions:
~ ___77-[ACCHWComponentAuth signVeridianChallenge:completionHandler:componentIndex:]_block_invoke_2 : 188 -> 192
~ _systemInfo_copyProductType : 72 -> 96
~ _systemInfo_copyProductVersion : 72 -> 96
CStrings:
+ "ACCTransportEANative_SessionSocketReadyNotification"
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
```
