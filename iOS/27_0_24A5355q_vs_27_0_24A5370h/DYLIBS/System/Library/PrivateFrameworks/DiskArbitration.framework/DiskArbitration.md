## DiskArbitration

> `/System/Library/PrivateFrameworks/DiskArbitration.framework/DiskArbitration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cc0` | `0x6eac` | **`+0x1ec`** |
| `__TEXT.__cstring` | `0x730` | `0x748` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x218` | `0x228` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x320` | `0x328` | **`+0x8`** |

### Other Changes

```diff

-593.0.0.0.1
+597.0.0.0.0

-  Functions: 162
-  Symbols:   376
-  CStrings:  131
+  Functions: 164
+  Symbols:   378
+  CStrings:  132
Symbols:
+ _DARegisterExitCallback
+ _DARegisterExitCallbackWithBlock
CStrings:
+ "diskarbitrationd exited"
```
