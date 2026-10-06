## lifs

> `/System/Library/Extensions/lifs.kext/lifs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__os_log` | `0x1f16` | `0x1f5d` | **`+0x47`** |
| `__TEXT_EXEC.__text` | `0x20390` | `0x203c8` | **`+0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-974.0.11.0.0
+974.0.13.0.2

-  CStrings:  519
+  CStrings:  520
Functions:
~ _lifs_request_done : 572 -> 628
CStrings:
+ "%s: we got no buffer to copyin, but requested to copyin, returning EIO"
```
