## sysstatuscheck

> `/usr/libexec/sysstatuscheck`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0cc` | `0xd22c` | **`+0x160`** |
| `__TEXT.__const` | `0x548` | `0x4c8` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0x5a0` | `0x61c` | **`+0x7c`** |
| `__DATA.__bss` | `0x4c` | `0x4` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x520` | `0x548` | **`+0x28`** |
| `__TEXT.__cstring` | `0xc5a` | `0xc74` | **`+0x1a`** |
| `__TEXT.__auth_stubs` | `0x510` | `0x520` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x290` | `0x298` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x78` | `0x70` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-233.0.0.502.1
+233.0.5.0.0

-  Functions: 247
-  Symbols:   128
-  CStrings:  83
+  Functions: 249
+  Symbols:   127
+  CStrings:  86
Symbols:
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev
CStrings:
+ "/var/db/mmaintenanced/"
+ "Failed to query data for '%s': (%d) %s\n"
+ "Failed to setup environment for memory error reporting (non-fatal)).\n"
+ "Failed to update ownership/permissions for '%s'\n"
+ "Failed to update permisions to %04o and/or user/group ownership to %d/%d for '%s'.\n"
+ "dramecc.db"
+ "memory_errors.db"
+ "vm.ecc.enabled"
- "Failed to migrate ECC database (non-fatal).\n"
- "Failed to query UID for '%s'.\n"
- "Failed to update permissions to %04o and/or user/group ownership to %d/%d for '%s'.\n"
- "Failed to update permissions to %04o for '%s': %d (%s)\n"
- "Failed to update user/group ownership to %d/%d for '%s': %d (%s)\n"
```
