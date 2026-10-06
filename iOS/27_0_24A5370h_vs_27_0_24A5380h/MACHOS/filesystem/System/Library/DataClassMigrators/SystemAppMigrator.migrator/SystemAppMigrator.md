## SystemAppMigrator

> `/System/Library/DataClassMigrators/SystemAppMigrator.migrator/SystemAppMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2c64` | `0x2cb1` | **`+0x4d`** |
| `__TEXT.__text` | `0x7d0c` | `0x7d38` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `0x1640` | `0x1660` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x580` | `0x5a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2d0` | `0x2e0` | **`+0x10`** |
| `__TEXT.__const` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1660.0.0.0.0
+1663.0.0.0.1

-  Symbols:   180
-  CStrings:  544
+  Symbols:   182
+  CStrings:  545
Symbols:
+ _os_eligibility_bring_up_daemon_4_migration
+ _os_eligibility_get_error_description
Functions:
~ sub_37e8 : 296 -> 340
CStrings:
+ "MISystemAppMigrator: Failed to bring up eligibility daemon for migration: %s"
```
