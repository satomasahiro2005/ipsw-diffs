## libmrc.dylib

> `/usr/lib/libmrc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0x320` | **`+0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x460` | `0x140` | **`-0x320`** |
| `__TEXT.__text` | `0x6360` | `0x635c` | **`-0x4`** |

### Other Changes

```diff

-3085.0.0.0.1
+3089.0.0.0.1
Functions:
~ __mdns_siphash_with_key_ex : 980 -> 972
~ _DomainNameFromString : 296 -> 300
```
