## libcopyfile.dylib

> `/usr/lib/system/libcopyfile.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a18` | `0x7a88` | **`+0x70`** |

### Other Changes

```diff

-259.0.0.0.0
+260.0.0.0.0
Functions:
~ _nameInDefaultList : 152 -> 160
~ _copyfile_internal : 7668 -> 7744
~ sub_2c0591fac -> _copyfile_set_dst_permissions : 72 -> 476
~ sub_2c0591ff4 -> _copyfile_validate_dst : 72 -> 284
~ _copyfile_fix_perms -> sub_2c11fe2f8 : 216 -> 72
~ _copyfile_set_dst_permissions -> sub_2c11fe340 : 476 -> 72
~ _copyfile_validate_dst -> _copyfile_fix_perms : 284 -> 216
~ _xattr_intent_with_flags : 56 -> 64
~ _xattr_preserve_for_intent : 116 -> 136
```
