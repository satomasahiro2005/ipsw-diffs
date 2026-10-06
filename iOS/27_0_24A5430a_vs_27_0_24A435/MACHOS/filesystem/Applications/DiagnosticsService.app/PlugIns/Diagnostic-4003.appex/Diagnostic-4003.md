## Diagnostic-4003

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4003.appex/Diagnostic-4003`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2024` | `0x23e0` | **`+0x3bc`** |
| `__DATA_CONST.__cfstring` | `0x140` | `0x220` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x780` | `0x860` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x923` | `0x9db` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x5f0` | `0x658` | **`+0x68`** |
| `__TEXT.__cstring` | `0xce` | `0x10a` | **`+0x3c`** |
| `__TEXT.__objc_methlist` | `0x384` | `0x3bc` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x2c8` | `0x2f8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x27e` | `0x2aa` | **`+0x2c`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x470` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x90` | `0xa8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x238` | `0x248` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x100` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 59
-  Symbols:   104
-  CStrings:  189
+  Functions: 64
+  Symbols:   109
+  CStrings:  207
Symbols:
+ _kALSIdentifierInnerFirst
+ _kALSIdentifierInnerSecond
+ _kALSIdentifierPrimary
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_setProperty_nonatomic_copy
- _objc_retain_x3
CStrings:
+ "@\"AmbientLightSensorDataInputs\""
+ "@\"NSString\""
+ "InnerFirst"
+ "InnerSecond"
+ "Primary"
+ "T@\"AmbientLightSensorDataInputs\",&,N,V_alsInputs"
+ "T@\"NSString\",C,N,V_identifier"
+ "_alsInputs"
+ "_identifier"
+ "als"
+ "als2a"
+ "als2b"
+ "alsInputs"
+ "containsObject:"
+ "identifier"
+ "setAlsInputs:"
+ "setIdentifier:"
+ "setWithObjects:"
```
