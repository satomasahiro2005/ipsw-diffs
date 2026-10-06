## ciphermld

> `/usr/libexec/ciphermld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__text` | `0x8b4` | `0x8b8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-383.0.24.0.0
+383.40.11.0.0

-  Symbols:   54
+  Symbols:   55
Symbols:
+ _$s8CipherML23DataProtectionMigrationO15migrateIfNeededyyFZ
Functions:
~ sub_100000c78 : 1220 -> 1224
```
