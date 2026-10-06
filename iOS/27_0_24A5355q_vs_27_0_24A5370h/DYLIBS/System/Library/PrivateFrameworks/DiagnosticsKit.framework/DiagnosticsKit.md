## DiagnosticsKit

> `/System/Library/PrivateFrameworks/DiagnosticsKit.framework/DiagnosticsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20a84` | `0x20c4c` | **`+0x1c8`** |
| `__TEXT.__gcc_except_tab` | `0x97c` | `0xa30` | **`+0xb4`** |
| `__TEXT.__oslogstring` | `0x1b5d` | `0x1bce` | **`+0x71`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xa60` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1600` | `0x1608` | **`+0x8`** |

### Other Changes

```diff

-99.0.0.0.0
+102.0.0.0.0

-  Functions: 973
-  Symbols:   1931
-  CStrings:  351
+  Functions: 976
+  Symbols:   1933
+  CStrings:  353
Symbols:
+ GCC_except_table1
+ _OBJC_CLASS_$_NSThread
CStrings:
+ "Timeout while waiting for DKExtensionDiscovery to complete"
+ "waitUntilComplete shouldn't called on the main thread"
```
