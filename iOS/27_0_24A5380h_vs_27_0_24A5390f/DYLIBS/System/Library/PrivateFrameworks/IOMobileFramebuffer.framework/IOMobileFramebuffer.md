## IOMobileFramebuffer

> `/System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b328` | `0x3b530` | **`+0x208`** |
| `__TEXT.__cstring` | `0x96dc` | `0x9757` | **`+0x7b`** |
| `__TEXT.__unwind_info` | `0x928` | `0x930` | **`+0x8`** |

### Other Changes

```diff

-700.50.80.0.0
+700.50.85.0.0

-  Functions: 919
-  Symbols:   1091
-  CStrings:  952
+  Functions: 925
+  Symbols:   1097
+  CStrings:  955
Symbols:
+ _AppleDisplayManagerRearrange
+ _AppleDisplayManagerReconfigComplete
+ _AppleDisplayManagerValidateAllocationSetEx
+ _kern_DisplayRearrange
+ _kern_DisplayReconfigComplete
+ _kern_DisplayResourcesValidateAllocationSetEx
CStrings:
+ "kern_DisplayRearrange called \n"
+ "kern_DisplayReconfigComplete called \n"
+ "kern_DisplayResourcesValidateAllocationSetEx called \n"
```
