## Diagnostic-9012

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9012.appex/Diagnostic-9012`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2acc` | `0x2d04` | **`+0x238`** |
| `__TEXT.__objc_stubs` | `0xd20` | `0xd80` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x16e` | `0x1b7` | **`+0x49`** |
| `__DATA_CONST.__cfstring` | `0x180` | `0x1c0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x234` | `0x254` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xeae` | `0xec1` | **`+0x13`** |
| `__DATA_CONST.__auth_got` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 78
-  Symbols:   85
-  CStrings:  278
+  Functions: 79
+  Symbols:   88
+  CStrings:  284
Symbols:
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_CRIOServiceController
+ _dispatch_semaphore_signal
CStrings:
+ "Failed to assert repair_en"
+ "InDiagnosticsMode"
+ "InternalBuild"
+ "Mesa already unlocked"
+ "Mesa unlock not supported"
+ "Waiting for keychord..."
+ "getProtocolVersion"
- "Diagnostics not available"
```
