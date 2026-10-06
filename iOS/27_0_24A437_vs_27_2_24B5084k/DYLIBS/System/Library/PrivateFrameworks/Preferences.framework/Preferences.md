## Preferences

> `/System/Library/PrivateFrameworks/Preferences.framework/Preferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe67e0` | `0xe69e0` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x4524` | `0x462a` | **`+0x106`** |
| `__AUTH_CONST.__objc_dictobj` | `0x28` | `—` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0xbf40` | `0xbf60` | **`+0x20`** |
| `__TEXT.__cstring` | `0xbf5e` | `0xbf7e` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x2a8` | `0x298` | **`-0x10`** |

### Other Changes

```diff

-5315.0.0.0.0
+5315.1.3.0.0

-  Functions: 5590
+  Functions: 5591

-  CStrings:  2276
+  CStrings:  2282
Symbols:
+ _PSIsDataLinkingTerminologyEligible
- _OBJC_CLASS_$_NSConstantDictionary
Functions:
~ -[PSTrackingWelcomeController init] : 648 -> 672
~ -[PSTrackingWelcomeController aboutText] : 372 -> 520
+ _PSIsDataLinkingTerminologyEligible
CStrings:
+ "%s: Showing data linking about text."
+ "Cannot determine data linking terminology eligibility due to error: %d"
+ "TRACKING_ABOUT_TEXT_ALT"
+ "TRACKING_ABOUT_TITLE_ALT"
+ "Unable to determine data linking terminology eligibility "
+ "User is eligible for data linking terminology"
+ "User is not eligible for data linking terminology"
- "SchoolworkPrivacy.bundle"
```
