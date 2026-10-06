## fsck_exfat

> `/System/Library/Filesystems/exfat.fs/fsck_exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc08` | `0xcf14` | **`+0x30c`** |
| `__DATA_CONST.__const` | `0x370` | `0x3e8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x228` | `0x238` | **`+0x10`** |
| `__DATA.__common` | `0x248` | `0x250` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`

### Other Changes

```diff

-561.0.1.0.0
+561.0.3.0.0

-  Functions: 189
+  Functions: 193
```
