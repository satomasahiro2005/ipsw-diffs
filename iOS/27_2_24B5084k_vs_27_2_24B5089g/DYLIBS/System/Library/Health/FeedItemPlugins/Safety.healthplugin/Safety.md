## Safety

> `/System/Library/Health/FeedItemPlugins/Safety.healthplugin/Safety`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x8f00` | `0x6e80` | **`-0x2080`** |
| `__DATA_DIRTY.__bss` | `0x1e80` | `0x3f00` | **`+0x2080`** |
| `__DATA_DIRTY.__data` | `0x2868` | `0x4318` | **`+0x1ab0`** |
| `__AUTH.__data` | `0x1ad8` | `0x628` | **`-0x14b0`** |
| `__DATA.__data` | `0x1898` | `0x12a0` | **`-0x5f8`** |
| `__AUTH.__objc_data` | `0x17e8` | `0x1490` | **`-0x358`** |
| `__DATA_DIRTY.__objc_data` | `0xf98` | `0x12f0` | **`+0x358`** |
| `__DATA.__common` | `0x288` | `0xb8` | **`-0x1d0`** |
| `__DATA_DIRTY.__common` | `0x230` | `0x400` | **`+0x1d0`** |
| `__TEXT.__text` | `0xb27b0` | `0xb285c` | **`+0xac`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4
Functions:
~ sub_2315a1ff4 -> sub_23172bff4 : 320 -> 344
~ sub_2315cc86c -> sub_231756884 : 268 -> 296
~ sub_2315ccc0c -> sub_231756c40 : 1908 -> 1932
~ sub_2315cdcb0 -> sub_231757cfc : 236 -> 260
~ sub_2315cdd9c -> sub_231757e00 : 392 -> 416
~ sub_2315e7808 -> sub_231771884 : 964 -> 988
~ sub_2315e7e4c -> sub_231771ee0 : 840 -> 864
```
