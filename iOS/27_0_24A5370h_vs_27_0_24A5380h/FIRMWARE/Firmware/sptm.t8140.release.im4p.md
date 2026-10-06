## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5f554` | `0x5f320` | **`-0x234`** |
| `__TEXT.__cstring` | `0x153f0` | `0x1535a` | **`-0x96`** |
| `__DATA_CONST.__const` | `0x7bd0` | `0x7bc8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__LATE_CONST.__late_const`

### Other Changes

```diff

-819.0.0.502.1
-  Functions: 397
+820.0.8.0.0
+  Functions: 399

-  CStrings:  2516
+  CStrings:  2510
CStrings:
+ "SPTM-820.0.8|2026-06-26:21:27:04.769007|"
- "%s: assert 'region->active_refcnt' failed."
- "SPTM-819.0.0.502.1|2026-06-15:23:34:08.118957|"
- "VIOLATION_CPUTRACE_VA_ACTIVE"
- "active_refcnt"
- "cputrace_locked_va_set_buffer_vaddr"
- "is_active0"
- "is_active1"
```
