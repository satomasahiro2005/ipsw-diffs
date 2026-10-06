## aned

> `/usr/libexec/aned`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d36c` | `0x7d624` | **`+0x2b8`** |
| `__TEXT.__oslogstring` | `0x6ce5` | `0x6d61` | **`+0x7c`** |
| `__TEXT.__gcc_except_tab` | `0x61a0` | `0x61b4` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0xf80` | `0xf90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1bb8` | `0x1bc0` | **`+0x8`** |

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

-  Functions: 2787
-  Symbols:   4176
-  CStrings:  1755
+  Functions: 2789
+  Symbols:   4178
+  CStrings:  1757
Symbols:
+ __ANEStorageProbeFileIsReadable
+ _pread
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: perTdStats Model patching is not enabled"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
- "%@: Model patching is not enabled"
```
