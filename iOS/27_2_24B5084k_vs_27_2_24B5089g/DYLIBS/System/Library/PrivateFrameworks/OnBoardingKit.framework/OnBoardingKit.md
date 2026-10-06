## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xff0` | `0xfa0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xcd0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x139e` | `0x136c` | **`-0x32`** |
| `__AUTH_CONST.__cfstring` | `0x20a0` | `0x2080` | **`-0x20`** |
| `__TEXT.__cstring` | `0x19a9` | `0x1989` | **`-0x20`** |
| `__TEXT.__text` | `0x48f28` | `0x48f40` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x62b4` | `0x62c4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4040` | `0x4048` | **`+0x8`** |

### Other Changes

```diff

-3977.1.3.1.0
+3977.1.3.2.0

-  Functions: 1896
-  Symbols:   3483
-  CStrings:  380
+  Functions: 1897
+  Symbols:   3484
+  CStrings:  378
Symbols:
+ -[OBButtonTray _updatePrivacyLinkControllerMarginConstraints]
Functions:
~ -[OBButtonTray layoutSubviews] : 76 -> 84
~ -[OBButtonTray didMoveToSuperview] : 356 -> 76
+ -[OBButtonTray _updatePrivacyLinkControllerMarginConstraints]
~ -[OBPrivacyFlow _showInCombinedListWithDeviceClass:] : 756 -> 564
CStrings:
- "HideFromCombinedListForGMECHINA"
- "HideFromCombinedListForGMECHINA must be a boolean"
```
