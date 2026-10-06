## libsystem_malloc.dylib

> `/usr/lib/system/libsystem_malloc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42f6c` | `0x43320` | **`+0x3b4`** |
| `__TEXT.__const` | `0x581` | `0x614` | **`+0x93`** |
| `__TEXT.__cstring` | `0xb648` | `0xb5c5` | **`-0x83`** |
| `__TEXT.__unwind_info` | `0xa80` | `0xaf0` | **`+0x70`** |
| `__DATA.__common` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-883.0.0.0.0
+886.0.2.0.0

-  Functions: 1105
-  Symbols:   1153
-  CStrings:  969
+  Functions: 1102
+  Symbols:   1156
+  CStrings:  965
Symbols:
+ _malloc_vm_guard_objects_enabled
+ _small_check_fail_msg
+ _small_freelist_fail_msg
+ _tiny_check_fail_msg
+ _tiny_freelist_fail_msg
- _OUTLINED_FUNCTION_7
- __malloc_get_sec_transition_policy
CStrings:
+ "BUG IN LIBMALLOC: malloc assertion \"!chunk->xzc_bits.xzcb_preallocated\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7516)"
+ "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_segment.c:2724)"
+ "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_segment.c:2723)"
+ "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_segment.c:2897)"
+ "BUG IN LIBMALLOC: malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7826)"
+ "BUG IN LIBMALLOC: malloc assertion \"gxz.xz\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7718)"
+ "BUG IN LIBMALLOC: malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:6822)"
+ "BUG IN LIBMALLOC: malloc assertion \"prev_slot_value == slot_meta.xasa_value\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:2584)"
+ "BUG IN LIBMALLOC: malloc assertion \"retries < 10\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7576)"
+ "BUG IN LIBMALLOC: malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:5328)"
- "*** check: incorrect tiny region "
- "BUG IN LIBMALLOC: malloc assertion \"!chunk->xzc_bits.xzcb_preallocated\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7515)"
- "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_segment.c:2723)"
- "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_segment.c:2722)"
- "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_segment.c:2896)"
- "BUG IN LIBMALLOC: malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7825)"
- "BUG IN LIBMALLOC: malloc assertion \"gxz.xz\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7717)"
- "BUG IN LIBMALLOC: malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:6821)"
- "BUG IN LIBMALLOC: malloc assertion \"prev_slot_value == slot_meta.xasa_value\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:2579)"
- "BUG IN LIBMALLOC: malloc assertion \"retries < 10\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7575)"
- "BUG IN LIBMALLOC: malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:5326)"
- "check: incorrect small region "
- "check: small free list incorrect"
- "check: tiny free list incorrect "
```
