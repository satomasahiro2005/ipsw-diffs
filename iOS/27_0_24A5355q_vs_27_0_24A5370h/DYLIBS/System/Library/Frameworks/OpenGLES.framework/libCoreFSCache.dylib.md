## libCoreFSCache.dylib

> `/System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a4c` | `0x5a90` | **`+0x44`** |

### Other Changes

```text
Functions:
~ _fscache_insert_and_retain : 1380 -> 1376
~ _cvmsPoolAlloc : 560 -> 556
~ _relocate_maps : 748 -> 764
~ _fscache_open_worker : 3284 -> 3324
~ _cvmsPoolInsertHeap : 300 -> 296
~ _fscache_close_worker : 1116 -> 1144
~ _fscache_find_and_retain : 212 -> 208
~ _remove_from_hash : 240 -> 236
~ _fscache_remove_all : 296 -> 312
~ _fscache_get_cache_keys : 224 -> 212
```
