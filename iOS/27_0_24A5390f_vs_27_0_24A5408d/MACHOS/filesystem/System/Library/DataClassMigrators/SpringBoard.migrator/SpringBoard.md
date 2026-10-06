## SpringBoard

> `/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3f8` | `0xe4cc` | **`+0xd4`** |
| `__TEXT.__oslogstring` | `0x130b` | `0x139e` | **`+0x93`** |
| `__TEXT.__auth_stubs` | `0x5d0` | `0x5e0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x140` | `0x14c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2f8` | `0x300` | **`+0x8`** |
| `__TEXT.__const` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4630.1.102.0.0
+4636.102.1.0.0

-  Functions: 641
-  Symbols:   378
-  CStrings:  691
+  Functions: 642
+  Symbols:   379
+  CStrings:  692
Symbols:
+ __os_log_fault_impl
CStrings:
+ "[performPosterBoardMigration] posterboard migration timed out after %{public}.0f seconds; not marking complete"
+ "[performPosterBoardMigration] tint color migration did not complete (error: %{public}@, timedOut: %{BOOL}u); will retry next launch"
- "[performPosterBoardMigration] tint color migration failed; migration error prevented completion"
```
