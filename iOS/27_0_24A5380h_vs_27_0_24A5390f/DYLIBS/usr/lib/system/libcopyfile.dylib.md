## libcopyfile.dylib

> `/usr/lib/system/libcopyfile.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a88` | `0x7ab0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x318` | `0x310` | **`-0x8`** |

### Other Changes

```diff

-260.0.0.0.0
+260.0.1.0.0
Functions:
~ _copyfile : 3968 -> 3988
~ _copyfile_set_dst_permissions : 476 -> 500
~ _copyfile_unpack_xattr : 484 -> 480
```
