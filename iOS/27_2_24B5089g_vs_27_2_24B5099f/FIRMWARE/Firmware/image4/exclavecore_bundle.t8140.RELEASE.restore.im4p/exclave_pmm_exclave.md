## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_pmm_exclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1217c` | `0x120f8` | **`-0x84`** |
| `__TEXT.__text` | `0x4d644` | `0x4d684` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-1490.40.25.0.0
-  Functions: 1214
+1490.40.28.0.0
+  Functions: 1216

-  CStrings:  1531
+  CStrings:  1529
CStrings:
- "[PMM DEBUG] stats_describe_handler: returning success for statId=%u\n"
- "[PMM DEBUG] stats_describe_handler: statId=%u, total_count=%u\n"
```
