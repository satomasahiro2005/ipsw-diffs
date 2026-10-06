## heartratecoordinatord

> `/usr/libexec/heartratecoordinatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25870` | `0x25a78` | **`+0x208`** |
| `__TEXT.__objc_stubs` | `0x3ce0` | `0x3d40` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x4058` | `0x4098` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x4d9a` | `0x4dda` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x190c` | `0x1944` | **`+0x38`** |
| `__TEXT.__cstring` | `0x20fb` | `0x211c` | **`+0x21`** |
| `__DATA_CONST.__cfstring` | `0x1f60` | `0x1f80` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1130` | `0x1140` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1180` | `0x1190` | **`+0x10`** |
| `__DATA.__objc_const` | `0x2b90` | `0x2b98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-38.0.0.0.0
+39.0.0.0.0

-  Functions: 896
+  Functions: 900

-  CStrings:  1557
+  CStrings:  1560
CStrings:
+ "com.apple.hrc.external_hr_source"
+ "externalHRSourceBecameActive"
+ "setExternalHeartRateMonitorActive:"
```
