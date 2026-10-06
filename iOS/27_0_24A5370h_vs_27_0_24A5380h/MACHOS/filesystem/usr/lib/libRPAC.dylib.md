## libRPAC.dylib

> `/usr/lib/libRPAC.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92ac8` | `0x92b08` | **`+0x40`** |

### Same-size Content Changes

- `__AUTH_CONST.__interpose`
- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _isExplicitVacuumStatement : 348 -> 364
~ _isWriteStatement : 372 -> 388
~ _isBulkReadStatement : 372 -> 388
~ _isBulkWriteStatement : 372 -> 388
~ _updateStmt : 808 -> 788
~ _deleteTrackingStmt : 524 -> 540
~ _resetDyldInsertLibraries : 436 -> 440
```
