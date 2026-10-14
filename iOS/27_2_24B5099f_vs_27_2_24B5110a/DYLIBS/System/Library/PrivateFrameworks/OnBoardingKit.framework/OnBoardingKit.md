## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x20a0` | `0x20e0` | **`+0x40`** |
| `__TEXT.__text` | `0x49000` | `0x49040` | **`+0x40`** |
| `__TEXT.__cstring` | `0x19a9` | `0x19c9` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1040` | `0x1048` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1897
+  Functions: 1898

-  CStrings:  380
+  CStrings:  382
Functions:
+ sub_1c700cf90
~ +[OBPrivacyFlow _modelSpecificLocalizedStringKeyForKey:preferredDeviceType:] : 428 -> 460
~ -[OBPrivacyFlow showInCombinedListForPreferredDeviceType:] : 240 -> 232
CStrings:
+ "%@_HOMEACCESSORY"
+ "HomeAccessory"
```
