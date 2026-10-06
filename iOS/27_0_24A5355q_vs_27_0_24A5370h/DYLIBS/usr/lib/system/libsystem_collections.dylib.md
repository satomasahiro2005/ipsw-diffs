## libsystem_collections.dylib

> `/usr/lib/system/libsystem_collections.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4264` | `0x4210` | **`-0x54`** |

### Other Changes

```diff

-1782.0.0.0.0
+1786.0.0.0.0
Functions:
~ _os_map_str_find : 224 -> 216
~ _os_map_str_delete : 440 -> 432
~ __os_map_str_insert_no_rehash : 332 -> 324
~ __os_map_str_rehash : 312 -> 300
~ _os_map_128_foreach : 136 -> 128
~ _os_map_str_entry : 228 -> 220
~ _os_map_128_clear : 200 -> 204
~ _os_map_str_foreach : 136 -> 124
~ _os_map_32_foreach : 136 -> 124
~ _os_map_str_clear : 204 -> 200
~ _os_set_128_ptr_clear : 352 -> 356
~ __os_set_32_ptr_rehash : 284 -> 288
~ __os_set_str_ptr_rehash : 284 -> 288
~ __os_map_128_rehash : 300 -> 304
~ __os_set_64_ptr_rehash : 284 -> 288
~ _os_set_str_ptr_clear : 352 -> 356
~ _os_set_str_ptr_foreach : 184 -> 180
~ _os_set_32_ptr_clear : 352 -> 356
~ _os_set_32_ptr_foreach : 184 -> 180
~ _os_set_64_ptr_clear : 352 -> 356
~ _os_set_64_ptr_foreach : 184 -> 180
~ _os_set_128_ptr_foreach : 184 -> 180
~ __os_set_128_ptr_rehash : 284 -> 288
~ _os_map_64_clear : 204 -> 200
~ _os_map_64_foreach : 136 -> 124
~ __os_map_64_rehash : 312 -> 300
```
