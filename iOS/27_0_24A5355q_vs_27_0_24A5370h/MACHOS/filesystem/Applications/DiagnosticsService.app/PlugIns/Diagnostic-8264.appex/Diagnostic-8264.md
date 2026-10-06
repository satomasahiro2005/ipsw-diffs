## Diagnostic-8264

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8264.appex/Diagnostic-8264`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4764` | `0x4888` | **`+0x124`** |
| `__TEXT.__oslogstring` | `0x6e4` | `0x79c` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x5f0` | `0x620` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0xdda` | `0xded` | **`+0x13`** |
| `__TEXT.__auth_stubs` | `0x3d0` | `0x3c0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1f8` | `0x1f0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x168` | `0x160` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x354` | `0x35c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x34` | `0x38` | **`+0x4`** |
| `__TEXT.__cstring` | `0x81f` | `0x820` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  Functions: 59
-  Symbols:   123
-  CStrings:  348
+  Functions: 60
+  Symbols:   121
+  CStrings:  352
Symbols:
- _CFDictionaryAddValue
- ___kCFBooleanTrue
CStrings:
+ "Bypassing asset downloading since useLocalFW is set to YES"
+ "TB,R,N,VuseLocalFW"
+ "Using local firmware path, skipping URL requests"
+ "Using local firmware path, skipping URL setup"
+ "useLocalFW"
+ "useLocalFW flag is set to YES"
- "%@,Ticket"
- "getBMUType"
```
