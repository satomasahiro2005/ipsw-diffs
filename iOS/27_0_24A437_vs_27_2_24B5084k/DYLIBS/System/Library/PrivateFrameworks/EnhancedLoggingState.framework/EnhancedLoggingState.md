## EnhancedLoggingState

> `/System/Library/PrivateFrameworks/EnhancedLoggingState.framework/EnhancedLoggingState`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e98` | `0x8ca8` | **`-0x1f0`** |
| `__AUTH_CONST.__cfstring` | `0x2320` | `0x22e0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x40b` | `0x3d0` | **`-0x3b`** |
| `__TEXT.__cstring` | `0x1a55` | `0x1a3d` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e8` | `0x8d8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0xbb8` | `0xbb0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x220` | `0x218` | **`-0x8`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  - /System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon

-  Functions: 232
-  Symbols:   595
-  CStrings:  321
+  Functions: 230
+  Symbols:   593
+  CStrings:  318
Symbols:
- -[ELSSnapshot refreshSessionDevice]
- _NSClassFromString
CStrings:
- "Could not decode enhanced logging state session device: %@"
- "DEDBugSession"
- "DEDDevice"
```
