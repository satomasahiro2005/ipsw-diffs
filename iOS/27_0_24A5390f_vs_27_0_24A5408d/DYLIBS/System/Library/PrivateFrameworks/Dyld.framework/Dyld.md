## Dyld

> `/System/Library/PrivateFrameworks/Dyld.framework/Dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51ad8` | `0x51de4` | **`+0x30c`** |
| `__DATA.__bss` | `0x3300` | `0x3480` | **`+0x180`** |
| `__TEXT.__const` | `0x3408` | `0x34b8` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0xe26` | `0xec6` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x2050` | `0x20e0` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x1258` | `0x12bc` | **`+0x64`** |
| `__TEXT.__constg_swiftt` | `0xf70` | `0xf8c` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0xd3b` | `0xd57` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x640` | `0x658` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x11e8` | `0x11f8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1dc` | `0x1e8` | **`+0xc`** |
| `__DATA.__data` | `0xb78` | `0xb80` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x130` | **`+0x4`** |

### Other Changes

```diff

-27060.1.0.0.0
+27062.0.0.0.0

-  Functions: 1448
-  Symbols:   1051
+  Functions: 1459
+  Symbols:   1054
Symbols:
+ _associated conformance 4Dyld10AtlasErrorO13DiscriminatorOSHAASQ
+ _symbolic _____ 4Dyld10AtlasErrorO13DiscriminatorO
+ _symbolic ___________t s5Int32V 4Dyld10AtlasErrorO13DiscriminatorO
```
