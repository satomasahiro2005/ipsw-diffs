## ProgressUI

> `/System/Library/PrivateFrameworks/ProgressUI.framework/ProgressUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x322c` | `0x325c` | **`+0x30`** |
| `__TEXT.__cstring` | `0x978` | `0x99e` | **`+0x26`** |
| `__AUTH_CONST.__cfstring` | `0x620` | `0x640` | **`+0x20`** |

### Other Changes

```diff

-2854.0.0.0.0
+2858.0.0.0.0

+  - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

-  CStrings:  87
+  CStrings:  88
Functions:
~ -[PUIProgressWindow _initWithOptions:contextLevel:appearance:environment:] : 652 -> 700
CStrings:
+ "PUIProgressWindow got product type %@"
```
