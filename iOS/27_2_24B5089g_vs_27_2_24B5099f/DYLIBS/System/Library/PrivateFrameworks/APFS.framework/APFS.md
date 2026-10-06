## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x1d8` | **`+0x1d8`** |
| `__AUTH.__data` | `0x148` | `—` | **`-0x148`** |
| `__DATA.__data` | `0x9c` | `0xc` | **`-0x90`** |
| `__TEXT.__text` | `0x54734` | `0x54714` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x9e0` | `0x9e8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3288.40.14.0.0
+3288.40.17.0.0
CStrings:
+ "3288.40.17"
- "3288.40.14"
```
