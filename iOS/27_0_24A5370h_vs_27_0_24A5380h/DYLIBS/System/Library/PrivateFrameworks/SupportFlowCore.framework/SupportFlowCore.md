## SupportFlowCore

> `/System/Library/PrivateFrameworks/SupportFlowCore.framework/SupportFlowCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x2280` | `0x2200` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x380` | `0x400` | **`+0x80`** |
| `__TEXT.__text` | `0x248f8` | `0x248a4` | **`-0x54`** |
| `__DATA.__data` | `0x400` | `0x3e0` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x258` | `0x278` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x110` | `0x118` | **`+0x8`** |

### Other Changes

```diff

-37.0.24.0.0
+37.0.26.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 1162
-  Symbols:   387
+  Functions: 1163
+  Symbols:   389
Symbols:
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_SupportFlowCore
```
