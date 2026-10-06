## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x545e4` | `0x54734` | **`+0x150`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3288.40.13.0.0
+3288.40.14.0.0
Functions:
~ _spaceman_chunk_zone_info_init : 68 -> 88
~ _spaceman_iterate_process_bitmap_block : 1028 -> 1044
~ _spaceman_iterate_free_extents_internal : 3792 -> 3864
~ _spaceman_alloc_iterate_chunks : 3516 -> 3588
~ _spaceman_modify_bits : 3604 -> 3736
~ _jobj_validate_key_val : 584 -> 608
CStrings:
+ "3288.40.14"
- "3288.40.13"
```
