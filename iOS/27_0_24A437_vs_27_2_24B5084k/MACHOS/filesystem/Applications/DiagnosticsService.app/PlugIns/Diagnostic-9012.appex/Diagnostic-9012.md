## Diagnostic-9012

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9012.appex/Diagnostic-9012`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d04` | `0x2b28` | **`-0x1dc`** |
| `__TEXT.__oslogstring` | `0x1b7` | `0x16e` | **`-0x49`** |
| `__TEXT.__objc_stubs` | `0xd80` | `0xd40` | **`-0x40`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x1a0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x444` | `0x45c` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x259` | `0x264` | **`+0xb`** |
| `__TEXT.__cstring` | `0x254` | `0x24b` | **`-0x9`** |
| `__DATA_CONST.__got` | `0xa0` | `0x98` | **`-0x8`** |
| `__TEXT.__objc_methname` | `0xec1` | `0xec9` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Symbols:   88
-  CStrings:  284
+  Symbols:   87
+  CStrings:  281
Symbols:
+ _MGGetProductType
+ _objc_opt_class
- _MGGetBoolAnswer
- _OBJC_CLASS_$_CRIOServiceController
- _dispatch_semaphore_signal
CStrings:
+ "@24@0:8i16"
+ "Diagnostics not available"
+ "iPad-Unlock-volbtn-top"
+ "packageNameForProductType:"
- "Failed to assert repair_en"
- "InDiagnosticsMode"
- "InternalBuild"
- "Mesa already unlocked"
- "Mesa unlock not supported"
- "Waiting for keychord..."
- "getProtocolVersion"
```
