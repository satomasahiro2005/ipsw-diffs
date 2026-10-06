## AddressBookLegacy

> `/System/Library/DataClassMigrators/AddressBookLegacy.migrator/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x490` | `0x500` | **`+0x70`** |
| `__TEXT.__text` | `0x2550` | `0x25c0` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x290` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x94` | `0xbc` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x180` | `0x1a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x30f` | `0x319` | **`+0xa`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-12877.100.1.0.0
+12880.200.11.0.0

-  Functions: 43
-  Symbols:   93
-  CStrings:  127
+  Functions: 44
+  Symbols:   100
+  CStrings:  128
Symbols:
+ _ABMigrationGateBegin
+ _ABMigrationGateEnd
+ _ABMigrationGateRenew
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_exception_rethrow
+ _objc_terminate
CStrings:
+ "no errors"
```
