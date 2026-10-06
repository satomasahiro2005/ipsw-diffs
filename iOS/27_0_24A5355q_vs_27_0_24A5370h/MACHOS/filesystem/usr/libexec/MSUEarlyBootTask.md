## MSUEarlyBootTask

> `/usr/libexec/MSUEarlyBootTask`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c6c` | `0x3c80` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0
Functions:
~ _copy_path_for_booted_os_data : 552 -> 568
~ _main : 8336 -> 8332
~ _msuearlyboottask_dump_mounted_filesystem_info : 220 -> 228
```
