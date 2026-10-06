## IOMFB_bics_daemon

> `/usr/libexec/IOMFB_bics_daemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31874` | `0x31bdc` | **`+0x368`** |
| `__TEXT.__cstring` | `0x576c` | `0x587c` | **`+0x110`** |
| `__DATA.__data` | `0xc00` | `0xc40` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1320` | `0x1350` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x280` | `0x2a0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xadc` | `0xaf8` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x9a8` | `0x9c0` | **`+0x18`** |
| `__DATA.__bss` | `0x16e0` | `0x16f0` | **`+0x10`** |
| `__TEXT.__const` | `0x5f34` | `0x5f44` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd58` | `0xd60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-700.50.97.13.0
+700.50.104.1.0

-  Functions: 993
-  Symbols:   503
-  CStrings:  827
+  Functions: 997
+  Symbols:   506
+  CStrings:  835
Symbols:
+ ___cxa_atexit
+ ___cxa_guard_acquire
+ ___cxa_guard_release
CStrings:
+ "%s: DCP rejected imported drLTH (payload CRC or key mismatch)"
+ "%s: Failed to publish migration expiry to ioreg: 0x%x\n"
+ "%s: Failed to update migration record on display nand: %s\n"
+ "BICSMigrationLastExpiry"
+ "DMIG"
+ "migrate_status"
+ "publish_migration_last_expiry"
+ "store_migration_record"
```
