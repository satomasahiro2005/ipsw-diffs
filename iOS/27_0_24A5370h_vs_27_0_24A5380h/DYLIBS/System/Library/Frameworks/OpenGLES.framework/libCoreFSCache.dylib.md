## libCoreFSCache.dylib

> `/System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a90` | `0x5a78` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x138` | `0x140` | **`+0x8`** |

### Other Changes

```diff

-403.1.0.0.0
+404.0.0.0.0
Functions:
~ _fscache_open -> _close_data_file : 88 -> 308
~ _close_data_file -> _fscache_open : 308 -> 88
~ _fscache_close_worker : 1144 -> 1120
```
