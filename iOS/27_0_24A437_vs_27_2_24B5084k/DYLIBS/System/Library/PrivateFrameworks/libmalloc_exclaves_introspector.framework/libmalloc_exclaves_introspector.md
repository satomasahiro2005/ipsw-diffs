## libmalloc_exclaves_introspector

> `/System/Library/PrivateFrameworks/libmalloc_exclaves_introspector.framework/libmalloc_exclaves_introspector`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4528` | `0x45ac` | **`+0x84`** |
| `__TEXT.__cstring` | `0x2191` | `0x218f` | **`-0x2`** |

### Other Changes

```diff

-886.0.8.0.0
+886.40.15.0.0
Functions:
~ _xzm_segment_group_segment_foreach_span : 452 -> 476
~ _xzm_print_task : 5092 -> 5120
~ __xzm_introspect_enumerate : 852 -> 868
~ ____xzm_introspect_enumerate_block_invoke : 516 -> 560
~ ___xzm_print_block_invoke_4 : 1464 -> 1484
CStrings:
+ "    \"buffer_len\": %u, \n"
+ "    \"max_len\": %u, \n"
+ "BUG IN LIBMALLOC: malloc assertion \"main_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:1033)"
+ "BUG IN LIBMALLOC: malloc assertion \"zone\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:1031)"
- "    \"buffer_len\": %llu, \n"
- "    \"max_len\": %llu, \n"
- "BUG IN LIBMALLOC: malloc assertion \"main_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:995)"
- "BUG IN LIBMALLOC: malloc assertion \"zone\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:993)"
```
