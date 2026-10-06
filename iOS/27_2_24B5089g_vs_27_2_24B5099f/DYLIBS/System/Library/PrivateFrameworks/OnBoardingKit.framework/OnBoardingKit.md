## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48f40` | `0x49000` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x136c` | `0x139e` | **`+0x32`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x20a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1989` | `0x19a9` | **`+0x20`** |

### Other Changes

```diff

-3977.1.3.2.0
+3977.1.4.0.0

-  CStrings:  378
+  CStrings:  380
Functions:
~ -[OBPrivacyFlow _showInCombinedListWithDeviceClass:] : 564 -> 756
CStrings:
+ "HideFromCombinedListForGMECHINA"
+ "HideFromCombinedListForGMECHINA must be a boolean"
```
