## WatchListKit

> `/System/Library/PrivateFrameworks/WatchListKit.framework/WatchListKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68394` | `0x684d4` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0xa720` | `0xa780` | **`+0x60`** |
| `__TEXT.__cstring` | `0x7f44` | `0x7f9b` | **`+0x57`** |
| `__TEXT.__objc_methlist` | `0x71d4` | `0x71ec` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x11d50` | `0x11d60` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x29a8` | `0x29b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3aa0` | `0x3ab0` | **`+0x10`** |

### Other Changes

```diff

-952.10.6.0.0
+952.10.8.0.0

-  Functions: 2812
-  Symbols:   5649
-  CStrings:  1943
+  Functions: 2814
+  Symbols:   5653
+  CStrings:  1947
Symbols:
+ -[WLKSystemPreferencesStore setSignLanguageCode:]
+ -[WLKSystemPreferencesStore setSignLanguageCodeDownload:]
+ -[WLKSystemPreferencesStore signLanguageCodeDownload]
+ -[WLKSystemPreferencesStore signLanguageCode]
+ _WLKSignLanguageCodeASL
+ _WLKSignLanguageCodeBSL
- -[WLKSystemPreferencesStore setSignLanguageEnabled:]
- -[WLKSystemPreferencesStore signLanguageEnabled]
CStrings:
+ "PreferredSignLanguage"
+ "PreferredSignLanguageDownload"
+ "ase"
+ "bfi"
+ "com.apple.AppleTV.signLanguageSettingDidChange"
- "SignLanguageEnabled"
```
