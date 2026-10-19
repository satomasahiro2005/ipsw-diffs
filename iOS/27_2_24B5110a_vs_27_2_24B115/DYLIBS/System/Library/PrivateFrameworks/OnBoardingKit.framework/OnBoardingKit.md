## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49040` | `0x48ee8` | **`-0x158`** |
| `__AUTH_CONST.__cfstring` | `0x20e0` | `0x20c0` | **`-0x20`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-  CStrings:  382
+  CStrings:  381
Functions:
~ +[OBPrivacyFlow _splashPlistFromBundle:forContentName:] : 172 -> 4
~ -[OBPrivacyFlow _splashLocalizedStringForKey:language:preferredDeviceType:] : 368 -> 192
CStrings:
- "-seed"
```
