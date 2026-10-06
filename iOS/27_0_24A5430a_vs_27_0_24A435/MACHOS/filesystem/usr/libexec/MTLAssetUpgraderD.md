## MTLAssetUpgraderD

> `/usr/libexec/MTLAssetUpgraderD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18600` | `0x18618` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _OUTLINED_FUNCTION_7 : 12 -> 20
~ _OUTLINED_FUNCTION_8 : 20 -> 12
~ _mdb_txn_renew0 : 1012 -> 1016
~ _mdb_txn_end : 584 -> 588
~ _mdb_cursor_init : 176 -> 180
~ _mdb_freelist_save : 1416 -> 1420
~ _mdb_page_flush : 940 -> 944
~ _mdb_env_open : 760 -> 764
```
