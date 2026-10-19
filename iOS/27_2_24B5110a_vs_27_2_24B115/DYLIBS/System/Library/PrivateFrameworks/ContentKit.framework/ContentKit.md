## ContentKit

> `/System/Library/PrivateFrameworks/ContentKit.framework/ContentKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x217a00` | `0x217a3c` | **`+0x3c`** |
| `__AUTH_CONST.__cfstring` | `0x12800` | `0x12820` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1d035` | `0x1d050` | **`+0x1b`** |
| `__DATA_CONST.__got` | `0x1940` | `0x1938` | **`-0x8`** |

### Other Changes

```diff

-  CStrings:  4868
+  CStrings:  4869
Functions:
~ +[NSKeyedUnarchiver(WFFileCoder) wf_securelyUnarchiveObjectWithData:allowedClasses:completionHandler:] : 484 -> 544
CStrings:
+ "WFRemoteExecutionFileCoder"
```
