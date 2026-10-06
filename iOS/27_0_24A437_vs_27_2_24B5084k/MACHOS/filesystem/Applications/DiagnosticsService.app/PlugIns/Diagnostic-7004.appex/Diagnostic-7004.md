## Diagnostic-7004

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-7004.appex/Diagnostic-7004`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x374` | `0x268` | **`-0x10c`** |
| `__TEXT.__objc_stubs` | `0x180` | `0x100` | **`-0x80`** |
| `__TEXT.__auth_stubs` | `0x130` | `0xe0` | **`-0x50`** |
| `__DATA_CONST.__objc_intobj` | `0x78` | `0x30` | **`-0x48`** |
| `__DATA_CONST.__cfstring` | `0x80` | `0x40` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x294` | `0x26a` | **`-0x2a`** |
| `__DATA_CONST.__auth_got` | `0xa0` | `0x78` | **`-0x28`** |
| `__TEXT.__cstring` | `0x6c` | `0x4c` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x130` | `0x118` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x28` | `0x18` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Symbols:   40
-  CStrings:  73
+  Symbols:   33
+  CStrings:  68
Symbols:
- _MGGetBoolAnswer
- _OBJC_CLASS_$_CRPearlController
- _OBJC_CLASS_$_NSNumber
- _objc_release_x24
- _objc_release_x25
- _objc_release_x26
- _objc_retain_x8
Functions:
~ sub_100000e24 : 544 -> 276
CStrings:
- "InDiagnosticsMode"
- "InternalBuild"
- "code"
- "numberWithInteger:"
- "powerCycleSensor:"
```
