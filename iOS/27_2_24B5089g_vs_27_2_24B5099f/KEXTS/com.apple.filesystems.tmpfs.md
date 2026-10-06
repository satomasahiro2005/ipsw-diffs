## com.apple.filesystems.tmpfs

> `com.apple.filesystems.tmpfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x97f8` | `0x98a8` | **`+0xb0`** |
| `__TEXT.__os_log` | `0x20a` | `0x19e` | **`-0x6c`** |
| `__TEXT_EXEC.__auth_stubs` | `0x630` | `0x640` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x320` | **`+0x8`** |

### Other Changes

```diff

-94.40.3.0.0
-  Functions: 153
+94.40.4.0.0
+  Functions: 154

-  CStrings:  46
+  CStrings:  44
CStrings:
- "error %d mapping UPL, upl_f_offset %llu, upl_len %d\n"
- "error %d unmapping UPL, upl_f_offset %llu, upl_len %d\n"
```
