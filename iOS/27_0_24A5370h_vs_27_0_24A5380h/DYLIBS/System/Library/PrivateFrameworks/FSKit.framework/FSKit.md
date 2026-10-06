## FSKit

> `/System/Library/PrivateFrameworks/FSKit.framework/FSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53888` | `0x53688` | **`-0x200`** |
| `__TEXT.__objc_methlist` | `0x62a8` | `0x6278` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0xb268` | `0xb258` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c10` | `0x2c00` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1830` | `0x1820` | **`-0x10`** |

### Other Changes

```diff

-974.0.1.0.2
+974.0.7.0.0

-  Functions: 2698
-  Symbols:   4244
+  Functions: 2694
+  Symbols:   4240
Symbols:
- -[FSClient(Project) activateVolume:usingBundle:options:replyHandler:]
- -[FSClient(Project) deactivateVolume:usingBundle:numericOptions:replyHandler:]
- ___69-[FSClient(Project) activateVolume:usingBundle:options:replyHandler:]_block_invoke
- ___78-[FSClient(Project) deactivateVolume:usingBundle:numericOptions:replyHandler:]_block_invoke
```
