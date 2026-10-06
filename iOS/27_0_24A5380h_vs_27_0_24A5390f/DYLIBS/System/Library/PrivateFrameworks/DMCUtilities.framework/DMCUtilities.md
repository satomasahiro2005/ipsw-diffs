## DMCUtilities

> `/System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x364f4` | `0x36554` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x4420` | `0x4440` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3aea` | `0x3b06` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x1310` | `0x1318` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x26a8` | `0x26b0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2fb4` | `0x2fbc` | **`+0x8`** |

### Other Changes

```diff

-111.0.0.0.0
+113.0.2.0.0

-  Functions: 1432
-  Symbols:   2810
-  CStrings:  1041
+  Functions: 1433
+  Symbols:   2812
+  CStrings:  1042
Symbols:
+ +[DMCFeatureOverrides essoDeclarationsWaitTimeoutWithDefaultValue:]
+ _DMCDefaultsKeyESSODeclarationsWaitTimeout
Functions:
+ +[DMCFeatureOverrides essoDeclarationsWaitTimeoutWithDefaultValue:]
~ +[DMCFeatureOverrides _allOverrides] : 600 -> 612
CStrings:
+ "ESSODeclarationsWaitTimeout"
```
