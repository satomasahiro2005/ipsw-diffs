## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2818` | `0xa2880` | **`+0x68`** |
| `__TEXT.__cstring` | `0xbd59` | `0xbd7e` | **`+0x25`** |
| `__AUTH_CONST.__cfstring` | `0x75a0` | `0x75c0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1e30` | `0x1e50` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2cc8` | `0x2ce8` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x240` | `0x250` | **`+0x10`** |

### Other Changes

```diff

-100288.0.8.0.0
+100288.0.9.0.0

-  Functions: 3572
-  Symbols:   3957
-  CStrings:  2577
+  Functions: 3573
+  Symbols:   3958
+  CStrings:  2578
Symbols:
+ ___IOHIDRequestAccess_block_invoke_2
Functions:
~ ___IOHIDRequestAccess_block_invoke : 36 -> 148
+ ___IOHIDRequestAccess_block_invoke_2
~ _IOHIDRequestAccess : 352 -> 320
CStrings:
+ "OSKEXT_BUILD_DATE 21:25:34 Aug  3 2026"
+ "_kTCCAccessRequestOptionSyncCallback"
- "OSKEXT_BUILD_DATE 21:46:15 Jul 10 2026"
```
