## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x50` | `0x1aa8` | **`+0x1a58`** |
| `__DATA.__data` | `0x1bc8` | `0x198` | **`-0x1a30`** |
| `__AUTH.__objc_data` | `0x16f0` | `—` | **`-0x16f0`** |
| `__DATA_DIRTY.__objc_data` | `0x2580` | `0x3c70` | **`+0x16f0`** |
| `__DATA.__bss` | `0x1f90` | `0xe90` | **`-0x1100`** |
| `__DATA_DIRTY.__bss` | `0x290` | `0x1390` | **`+0x1100`** |
| `__AUTH.__data` | `0x28` | `—` | **`-0x28`** |
| `__TEXT.__text` | `0x8a9d0` | `0x8a9f8` | **`+0x28`** |

### Other Changes

```diff

-13.1.12.0.0
+13.1.16.0.0
Functions:
~ ___51-[ASDAppQuery notificationCenter:receivedProgress:]_block_invoke : 2496 -> 2536
```
