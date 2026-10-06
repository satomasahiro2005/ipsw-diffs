## libcache.dylib

> `/usr/lib/system/libcache.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bf4` | `0x2c3c` | **`+0x48`** |

### Other Changes

```text
Functions:
~ _cache_get : 504 -> 508
~ __entry_get_optionally_checking_collisions : 400 -> 392
~ __entry_remove_from_list : 228 -> 240
~ __entry_add_to_list : 196 -> 208
~ _cache_set_and_retain : 1448 -> 1476
~ __value_entry_table_get : 232 -> 216
~ __cache_enforce_limits : 264 -> 268
~ _cache_get_and_retain : 512 -> 524
~ _cache_create : 544 -> 556
~ __value_entry_table_resize : 620 -> 624
~ __entry_table_resize : 584 -> 568
~ __evict_last : 132 -> 136
~ __entry_remove : 300 -> 304
~ __value_entry_remove : 244 -> 248
~ __cache_get_info_for_key : 124 -> 128
~ _cache_invoke : 204 -> 208
~ _cache_print : 880 -> 884
```
