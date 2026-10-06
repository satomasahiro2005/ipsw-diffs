## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48988` | `0x48830` | **`-0x158`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x2060` | **`-0x20`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-  CStrings:  376
+  CStrings:  375
Functions:
~ +[OBPrivacyFlow _splashPlistFromBundle:forContentName:] : 172 -> 4
~ -[OBPrivacyFlow _splashLocalizedStringForKey:language:preferredDeviceType:] : 368 -> 192
CStrings:
- "-seed"
```
