## libmalloc_exclaves_introspector

> `/System/Library/PrivateFrameworks/libmalloc_exclaves_introspector.framework/libmalloc_exclaves_introspector`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44d8` | `0x4528` | **`+0x50`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-886.0.2.0.0
+886.0.4.0.0
Functions:
~ _xzm_segment_group_segment_foreach_span : 416 -> 452
~ ____xzm_introspect_enumerate_block_invoke_2 : 1416 -> 1460
CStrings:
+ "BUG IN LIBMALLOC: malloc assertion \"main_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:995)"
+ "BUG IN LIBMALLOC: malloc assertion \"zone\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:993)"
- "BUG IN LIBMALLOC: malloc assertion \"main_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:960)"
- "BUG IN LIBMALLOC: malloc assertion \"zone\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone_malloc/xzone_introspect.c:958)"
```
