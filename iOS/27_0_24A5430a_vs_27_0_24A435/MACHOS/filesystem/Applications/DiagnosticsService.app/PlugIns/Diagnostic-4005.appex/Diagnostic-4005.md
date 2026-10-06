## Diagnostic-4005

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4005.appex/Diagnostic-4005`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c80` | `0x1fa4` | **`+0x324`** |
| `__TEXT.__objc_stubs` | `0x640` | `0x740` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x7b9` | `0x888` | **`+0xcf`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x1c0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x540` | `0x5a8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x324` | `0x36c` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x440` | `0x480` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x17a` | `0x1b9` | **`+0x3f`** |
| `__DATA.__objc_selrefs` | `0x280` | `0x2b8` | **`+0x38`** |
| `__TEXT.__cstring` | `0xb4` | `0xe3` | **`+0x2f`** |
| `__TEXT.__objc_methtype` | `0x239` | `0x266` | **`+0x2d`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x250` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe8` | `0x100` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__const` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 53
-  Symbols:   101
-  CStrings:  165
+  Functions: 60
+  Symbols:   107
+  CStrings:  183
Symbols:
+ _kAccelIdentifierPrimary
+ _kAccelIdentifierSecondary
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_release_x24
+ _objc_setProperty_nonatomic_copy
CStrings:
+ "@\"AccelerometerSensorDataInputs\""
+ "@\"NSString\""
+ "Could not resolve target accelerometer service for product: %@"
+ "Primary"
+ "Secondary"
+ "T@\"AccelerometerSensorDataInputs\",&,N,V_accelInputs"
+ "T@\"NSString\",C,N,V_identifier"
+ "_accelInputs"
+ "_identifier"
+ "accel"
+ "accelInputs"
+ "accel_1"
+ "containsObject:"
+ "identifier"
+ "setAccelInputs:"
+ "setIdentifier:"
+ "setWithObjects:"
+ "targetProduct"
```
