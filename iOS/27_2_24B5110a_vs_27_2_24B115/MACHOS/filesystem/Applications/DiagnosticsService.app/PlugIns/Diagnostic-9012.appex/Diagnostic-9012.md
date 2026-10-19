## Diagnostic-9012

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9012.appex/Diagnostic-9012`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c60` | `0x2e98` | **`+0x238`** |
| `__TEXT.__objc_stubs` | `0xde0` | `0xe40` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x16e` | `0x1b7` | **`+0x49`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x200` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2f0` | `0x310` | **`+0x20`** |
| `__TEXT.__cstring` | `0x25d` | `0x27d` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xf44` | `0xf57` | **`+0x13`** |
| `__DATA_CONST.__auth_got` | `0x188` | `0x198` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4c8` | `0x4d0` | **`+0x8`** |
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

-  Functions: 82
-  Symbols:   87
-  CStrings:  290
+  Functions: 83
+  Symbols:   90
+  CStrings:  296
Symbols:
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_CRIOServiceController
+ _dispatch_semaphore_signal
Functions:
~ sub_100002068 : 152 -> 676
+ sub_100003e18
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
