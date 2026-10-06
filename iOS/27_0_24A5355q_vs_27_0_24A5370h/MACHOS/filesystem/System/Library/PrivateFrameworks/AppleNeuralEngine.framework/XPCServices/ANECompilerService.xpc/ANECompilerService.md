## ANECompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANECompilerService.xpc/ANECompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16158` | `0x167c8` | **`+0x670`** |
| `__TEXT.__gcc_except_tab` | `0xee8` | `0x1048` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x1fef` | `0x2025` | **`+0x36`** |
| `__TEXT.__auth_stubs` | `0x790` | `0x7a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x420` | `0x428` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-382.7.4.0.0
+382.9.0.0.0

-  Functions: 285
+  Functions: 286

-  CStrings:  778
+  CStrings:  779
Symbols:
+ _objc_opt_isKindOfClass
- _OUTLINED_FUNCTION_12
CStrings:
+ "%@: aotCacheUrlIdentifier path traversal rejected: %@"
```
