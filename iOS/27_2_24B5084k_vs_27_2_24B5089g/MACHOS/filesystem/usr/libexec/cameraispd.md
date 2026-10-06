## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x3060` | `0x3040` | **`-0x20`** |
| `__TEXT.__cstring` | `0x7e7c` | `0x7e62` | **`-0x1a`** |
| `__DATA_CONST.__got` | `0xcd8` | `0xce0` | **`+0x8`** |
| `__TEXT.__text` | `0x7f080` | `0x7f084` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-20.104.4.0.0
+20.105.6.0.0

-  Symbols:   933
-  CStrings:  1936
+  Symbols:   934
+  CStrings:  1935
Symbols:
+ _kFigCaptureStreamMetadata_SmartTapAlgorithmMetadata
Functions:
~ sub_100067498 : 52776 -> 52780
CStrings:
+ "20.105.6"
- "20.104.4"
- "SmartTapAlgorithmMetadata"
```
