## ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/ANELargeModelCompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19a2c` | `0x19cdc` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0x2571` | `0x25e2` | **`+0x71`** |
| `__TEXT.__gcc_except_tab` | `0x1274` | `0x1288` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x890` | `0x8a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x460` | `0x468` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-382.100.2.0.0
+382.101.0.0.0

-  Functions: 311
-  Symbols:   966
-  CStrings:  880
+  Functions: 314
+  Symbols:   968
+  CStrings:  882
Symbols:
+ __ANEStorageProbeFileIsReadable
+ ___chkstk_darwin
+ _pread
- GCC_except_table10
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
```
