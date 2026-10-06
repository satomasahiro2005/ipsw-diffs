## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/ANEStorageMaintainer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8440` | `0x8720` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0x1009` | `0x107a` | **`+0x71`** |
| `__TEXT.__gcc_except_tab` | `0x154` | `0x168` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x580` | `0x590` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x190` | `0x198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-382.100.2.0.0
+382.101.0.0.0

-  Functions: 110
-  Symbols:   402
-  CStrings:  341
+  Functions: 115
+  Symbols:   405
+  CStrings:  343
Symbols:
+ GCC_except_table11
+ __ANEStorageProbeFileIsReadable
+ ___chkstk_darwin
+ _pread
- GCC_except_table10
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
```
