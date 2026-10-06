## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/MessageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x151084` | `0x1510dc` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x8ec0` | `0x8f00` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5a0` | `0x578` | **`-0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x648` | `0x638` | **`-0x10`** |
| `__TEXT.__cstring` | `0xa2f6` | `0xa306` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x12a7c` | `0x12a8c` | **`+0x10`** |
| `__AUTH.__data` | `0x360` | `0x358` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0x1a690` | `0x1a698` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc2a8` | `0xc2b0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x254c8` | `0x254cc` | **`+0x4`** |

### Other Changes

```diff

-3901.200.41.0.0
+3901.200.66.2.1

-  CStrings:  2080
+  CStrings:  2082
Functions:
~ _MFUserStyleSheetDictionary : 3972 -> 4036
~ -[MFMailComposeController presentPersonalizeSmartRepliesAlertIfNeededFromViewController:completion:] : 1644 -> 1668
CStrings:
+ " !important"
+ "background"
```
