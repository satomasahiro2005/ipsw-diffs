## APFoundation

> `/System/Library/PrivateFrameworks/APFoundation.framework/APFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x680` | `0x568` | **`-0x118`** |
| `__DATA_DIRTY.__objc_data` | `0x1810` | `0x1928` | **`+0x118`** |
| `__DATA_DIRTY.__bss` | `0x1688` | `0x1738` | **`+0xb0`** |
| `__DATA.__bss` | `0x5eb0` | `0x5e10` | **`-0xa0`** |
| `__TEXT.__text` | `0x1ef57c` | `0x1ef5a8` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x47fd` | `0x481d` | **`+0x20`** |
| `__DATA.__data` | `0x2208` | `0x2218` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2570` | `0x2580` | **`+0x10`** |
| `__DATA.__common` | `0xcc` | `0xc4` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-557.2.8.0.0
+557.2.9.0.0
CStrings:
+ "Database lock held for more than %llu ms, table: %@, type: %ld"
- "Database lock held for %llu ms"
```
