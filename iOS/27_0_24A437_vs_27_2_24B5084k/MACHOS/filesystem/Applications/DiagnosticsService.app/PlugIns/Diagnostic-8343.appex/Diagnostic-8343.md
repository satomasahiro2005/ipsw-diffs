## Diagnostic-8343

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8343.appex/Diagnostic-8343`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bdc` | `0x17f8` | **`-0x3e4`** |
| `__TEXT.__objc_stubs` | `0x500` | `0x420` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x4ce` | `0x473` | **`-0x5b`** |
| `__TEXT.__objc_methname` | `0x5cf` | `0x58d` | **`-0x42`** |
| `__DATA_CONST.__cfstring` | `0x300` | `0x2c0` | **`-0x40`** |
| `__TEXT.__auth_stubs` | `0x290` | `0x260` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x248` | `0x228` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x158` | `0x140` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x98` | `0x80` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Symbols:   77
-  CStrings:  170
+  Symbols:   71
+  CStrings:  164
Symbols:
- _AMSupportLogSetHandler
- _OBJC_CLASS_$_CRUtils
- _OBJC_CLASS_$_NSNumber
- __logHandler
- _objc_release_x27
- _objc_release_x28
Functions:
~ sub_100001074 : 1408 -> 412
CStrings:
- "PearlFramesDecompressionLastSeenErrorCode"
- "PearlFramesDecompressionLastSeenErrorDescription"
- "code"
- "getInnermostNSError:"
- "localizedDescription"
- "numberWithInteger:"
```
