## com.apple.fskit.apfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.apfs.appex/com.apple.fskit.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe56fc` | `0xe5828` | **`+0x12c`** |
| `__TEXT.__cstring` | `0x3b898` | `0x3b87a` | **`-0x1e`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3288.40.13.0.0
+3288.40.14.0.0
Functions:
~ _spaceman_chunk_zone_info_init : 68 -> 88
~ _spaceman_create : 2580 -> 2592
~ sub_100022370 -> sub_100022390 : 1044 -> 1060
~ _spaceman_iterate_free_extents_internal : 3936 -> 3964
~ sub_100025620 -> sub_10002566c : 3628 -> 3700
~ sub_10002644c -> sub_1000264e0 : 3616 -> 3744
~ _jobj_validate_key_val : 584 -> 608
CStrings:
+ "3288.40.14"
+ "CI_COUNT(chunk_info->ci_free_count) >= bcount"
- "3288.40.13"
- "CI_COUNT(chunk_info->ci_free_count) == CI_COUNT(chunk_info->ci_block_count)"
```
