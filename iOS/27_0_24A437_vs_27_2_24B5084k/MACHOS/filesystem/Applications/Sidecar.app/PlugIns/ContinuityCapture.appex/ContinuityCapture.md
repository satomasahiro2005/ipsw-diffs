## ContinuityCapture

> `/Applications/Sidecar.app/PlugIns/ContinuityCapture.appex/ContinuityCapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x6c0` | `0x700` | **`+0x40`** |
| `__DATA_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__cstring` | `0xf89` | `0xf9f` | **`+0x16`** |
| `__TEXT.__text` | `0x9538` | `0x954c` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x260` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-764.22.13.0.0
+764.40.4.122.1

-  Symbols:   177
-  CStrings:  656
+  Symbols:   179
+  CStrings:  658
Symbols:
+ _FigCaptureGetModelSpecificName
+ _OBJC_CLASS_$_NSConstantArray
Functions:
~ sub_100003d68 -> sub_100003e08 : 1180 -> 1200
CStrings:
+ "V68"
+ "iPhone_Rotate_V68"
```
