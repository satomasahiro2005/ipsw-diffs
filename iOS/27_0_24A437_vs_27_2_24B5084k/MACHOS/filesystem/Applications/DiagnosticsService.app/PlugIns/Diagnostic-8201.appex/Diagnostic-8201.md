## Diagnostic-8201

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8201.appex/Diagnostic-8201`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25a54` | `0x2d2dc` | **`+0x7888`** |
| `__TEXT.__gcc_except_tab` | `0x2c0c` | `0x3c58` | **`+0x104c`** |
| `__DATA_CONST.__cfstring` | `0x4ac0` | `0x4b40` | **`+0x80`** |
| `__TEXT.__cstring` | `0x676b` | `0x67b9` | **`+0x4e`** |
| `__DATA_CONST.__const` | `0x5a8` | `0x5e0` | **`+0x38`** |
| `__DATA.__objc_const` | `0x678` | `0x698` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xa8e` | `0xa99` | **`+0xb`** |
| `__TEXT.__objc_methname` | `0xc46` | `0xc50` | **`+0xa`** |
| `__TEXT.__unwind_info` | `0x7e0` | `0x7d8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x70` | `0x74` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-60.0.0.0.0
+62.0.0.0.0

-  CStrings:  1089
+  CStrings:  1095
Symbols:
+ _objc_retain_x25
- _NSLog
CStrings:
+ "%{public}s"
+ "ETROG projector version detected"
+ "ExclaveStatus"
+ "PEARL_PROJECTOR_HW_VERSION"
+ "RGB"
+ "m_isEtrog"
```
