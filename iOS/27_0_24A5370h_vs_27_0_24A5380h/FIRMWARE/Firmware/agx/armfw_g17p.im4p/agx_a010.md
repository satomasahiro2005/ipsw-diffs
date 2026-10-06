## agx_a010

> `Firmware/agx/armfw_g17p.im4p/agx_a010`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_SHARED_RO._RTK_EXT_SHD_DTA` | `0x78000` | `0x8000` | **`-0x70000`** |
| `__TEXT.__text` | `0x3ad88` | `0x3b614` | **`+0x88c`** |
| `__TEXT.__gxf_code` | `0x4f70` | `0x4f40` | **`-0x30`** |
| `__DATA.__zerofill` | `0x5b178` | `0x5b198` | **`+0x20`** |
| `__DATA.__const` | `0x808` | `0x820` | **`+0x18`** |
| `__TEXT.__const` | `0x1cf5` | `0x1cf7` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`
- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`

### Other Changes

```diff

-  Functions: 432
-  Symbols:   186
+  Functions: 433
+  Symbols:   187
Symbols:
+ _gCrashLog
CStrings:
+ "Jun 30 2026 21:13:04"
- "Jun 18 2026 19:50:12"
```
