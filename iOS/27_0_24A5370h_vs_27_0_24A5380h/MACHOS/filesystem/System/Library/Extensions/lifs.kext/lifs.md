## lifs

> `/System/Library/Extensions/lifs.kext/lifs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x20214` | `0x20244` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-974.0.1.0.2
+974.0.7.0.0
Functions:
~ _lifs_vnop_readdir : 1740 -> 1764
~ _lifs_vnop_getattrlistbulk : 1292 -> 1300
~ _lifs_cache_dirattr : 788 -> 792
~ _lifs_readdir_cached : 740 -> 752
```
