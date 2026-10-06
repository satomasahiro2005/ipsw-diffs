## devicedataresetd

> `/System/Library/PrivateFrameworks/EmbeddedDataReset.framework/Support/devicedataresetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38d8` | `0x397c` | **`+0xa4`** |
| `__TEXT.__oslogstring` | `0x7d8` | `0x840` | **`+0x68`** |
| `__TEXT.__objc_methname` | `0xe23` | `0xe6f` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0xba0` | `0xbe0` | **`+0x40`** |
| `__DATA.__objc_const` | `0xe38` | `0xe68` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x64c` | `0x664` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x420` | `0x430` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf0` | `0x100` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.0.1.0.0
+2027.1.1.0.0

-  Functions: 112
-  Symbols:   95
-  CStrings:  327
+  Functions: 114
+  Symbols:   97
+  CStrings:  332
Symbols:
+ ___kCFBooleanTrue
+ _kObliterationSanitizeStorageKey
CStrings:
+ "Caller requested storage sanitization; forwarding kObliterationSanitizeStorageKey to MobileObliteration"
+ "TB,N,V_sanitizeStorage"
+ "_sanitizeStorage"
+ "sanitizeStorage"
+ "setSanitizeStorage:"
```
