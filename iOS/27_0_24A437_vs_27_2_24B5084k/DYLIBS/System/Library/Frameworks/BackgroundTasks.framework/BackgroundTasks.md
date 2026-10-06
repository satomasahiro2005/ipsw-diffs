## BackgroundTasks

> `/System/Library/Frameworks/BackgroundTasks.framework/BackgroundTasks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb104` | `0xb228` | **`+0x124`** |
| `__AUTH_CONST.__objc_const` | `0x1890` | `0x18c0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6e0` | `0x700` | **`+0x20`** |
| `__TEXT.__cstring` | `0x74e` | `0x769` | **`+0x1b`** |
| `__TEXT.__objc_methlist` | `0xec0` | `0xed8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x910` | `0x920` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xe0` | `0xe4` | **`+0x4`** |

### Other Changes

```diff

-2467.2.2.0.0
+2467.40.37.0.0

-  Functions: 315
-  Symbols:   675
-  CStrings:  118
+  Functions: 317
+  Symbols:   678
+  CStrings:  119
Symbols:
+ -[BGContinuedProcessingTaskRequest hostManagedProgressUI]
+ -[BGContinuedProcessingTaskRequest setHostManagedProgressUI:]
+ _OBJC_IVAR_$_BGContinuedProcessingTaskRequest._hostManagedProgressUI
CStrings:
+ "hostManagedProgressUI: YES"
```
