## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_pmm_exclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x11e26` | `0x11dbd` | **`-0x69`** |
| `__TEXT.__text` | `0x4d054` | `0x4d00c` | **`-0x48`** |
| `__TEXT.__const` | `0x1d160` | `0x1d140` | **`-0x20`** |
| `__DATA.__bss` | `0x4edf8` | `0x4ee08` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-1490.0.5.0.0
-  Functions: 1212
+1490.0.20.0.0
+  Functions: 1211

-  CStrings:  1514
+  CStrings:  1513
CStrings:
+ "OWNERINFO"
- "[xrt] liblibc_plat_cl4_entry:xrt__init_mapped_nonroot:default"
- "no fixup data for faultable range [%#lx, %#lx) found"
```
