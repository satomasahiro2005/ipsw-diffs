## Diagnostic-4007

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4007.appex/Diagnostic-4007`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cc4` | `0x1fe8` | **`+0x324`** |
| `__TEXT.__objc_stubs` | `0x660` | `0x760` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x7a6` | `0x868` | **`+0xc2`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x1c0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x540` | `0x5a8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x324` | `0x36c` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x440` | `0x480` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x172` | `0x1ad` | **`+0x3b`** |
| `__DATA.__objc_selrefs` | `0x288` | `0x2c0` | **`+0x38`** |
| `__TEXT.__cstring` | `0xb4` | `0xe1` | **`+0x2d`** |
| `__TEXT.__objc_methtype` | `0x239` | `0x25d` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x250` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xe8` | `0xf8` | **`+0x10`** |
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
-  CStrings:  166
+  Functions: 60
+  Symbols:   107
+  CStrings:  184
Symbols:
+ _kGyroIdentifierPrimary
+ _kGyroIdentifierSecondary
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_release_x24
+ _objc_setProperty_nonatomic_copy
CStrings:
+ "@\"GyroSensorDataInputs\""
+ "@\"NSString\""
+ "Could not resolve target gyroscope service for product: %@"
+ "Primary"
+ "Secondary"
+ "T@\"GyroSensorDataInputs\",&,N,V_gyroInputs"
+ "T@\"NSString\",C,N,V_identifier"
+ "_gyroInputs"
+ "_identifier"
+ "containsObject:"
+ "gyro"
+ "gyroInputs"
+ "gyro_1"
+ "identifier"
+ "setGyroInputs:"
+ "setIdentifier:"
+ "setWithObjects:"
+ "targetProduct"
```
