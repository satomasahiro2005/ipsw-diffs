## libusrtcp.dylib

> `/usr/lib/libusrtcp.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5bbcc` | `0x5bd98` | **`+0x1cc`** |
| `__TEXT.__oslogstring` | `0xe6be` | `0xe794` | **`+0xd6`** |
| `__TEXT.__cstring` | `0x1a8e` | `0x1aab` | **`+0x1d`** |

### Other Changes

```diff

-6681.2.2.0.0
+6681.40.80.0.0

-  CStrings:  1120
+  CStrings:  1125
Functions:
~ _nw_tcp_destroy_globals : 276 -> 736
CStrings:
+ "%{public}s called with null globals"
+ "%{public}s called with null globals, backtrace limit exceeded"
+ "%{public}s called with null globals, dumping backtrace:%{public}s"
+ "%{public}s called with null globals, no backtrace"
+ "tcp_heuristics_cache_destroy"
```
