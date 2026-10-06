## com.apple.security.sandbox

> `com.apple.security.sandbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1f18d1` | `0x1f2991` | **`+0x10c0`** |
| `__TEXT_EXEC.__text` | `0x39a60` | `0x39aac` | **`+0x4c`** |
| `__TEXT.__os_log` | `0x1d8e` | `0x1d90` | **`+0x2`** |

### Other Changes

```diff

-3051.40.70.0.0
+3051.40.80.0.0
Functions:
~ sub_fffffff00a9aa21c -> sub_fffffff00a93041c : 420 -> 444
~ _hook_mount_notify_mount : 1228 -> 1264
~ _eval : 13844 -> 13848
~ sub_fffffff00a9c0a08 -> sub_fffffff00a946c48 : 720 -> 704
~ _re_cache_init : 496 -> 504
~ _collection_init : 1008 -> 1028
CStrings:
+ "%s set rootless flags on %s with flags=0x%lx"
- "%s set rootless flags on %s with flags=%lu"
```
