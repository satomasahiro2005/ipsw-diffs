## exclave_roottask

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_roottask`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e1974` | `0x4e755c` | **`+0x5be8`** |
| `__DATA.__const` | `0x34e90` | `0x35578` | **`+0x6e8`** |
| `__DATA.__bss` | `0x1b928` | `0x1bc28` | **`+0x300`** |
| `__TEXT.__constg_swiftt` | `0x160a8` | `0x162e8` | **`+0x240`** |
| `__TEXT.__swift5_fieldmd` | `0x122f8` | `0x12528` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x21848` | `0x21a0c` | **`+0x1c4`** |
| `__TEXT.__const` | `0xf1f90` | `0xf2150` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x3c95c` | `0x3cafc` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `0xb11c` | `0xb26c` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0xcdec` | `0xcecc` | **`+0xe0`** |
| `__TEXT.__swift5_builtin` | `0xe74` | `0xed8` | **`+0x64`** |
| `__TEXT.__swift5_capture` | `0x1510` | `0x155c` | **`+0x4c`** |
| `__TEXT.__objc_methtype` | `0x1ea` | `0x226` | **`+0x3c`** |
| `__DATA.__data` | `0xce38` | `0xce70` | **`+0x38`** |
| `__TEXT.__swift5_types` | `0x155c` | `0x1588` | **`+0x2c`** |
| `__TEXT.__swift5_types2` | `0x44` | `0x50` | **`+0xc`** |
| `__TEXT.__chain_fixups` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1460.0.0.502.2
-  Functions: 19092
+1485.0.0.0.3
+  Functions: 19197

-  CStrings:  6020
+  CStrings:  6034
CStrings:
+ "(managed_unt->managed_bitmap[bitmap_index] & BIT(bit)) == 0"
+ ": starting at root, "
+ ": starting in the middle, inserting fake IPCStackEntry"
+ "B16@?0^v8"
+ "B16@?0^{tb_message_accumulator_s=QQQ*}8"
+ "BIT STRING encoded with constructed encoding"
+ "Cannot create dependent member type with NULL base."
+ "Continuation was deinitialized without being resumed."
+ "DecodingError.typeMismatch: Expected value of type "
+ "Explicit tag was not constructed"
+ "INTEGER encoded with constructed encoding"
+ "OCTET STRING encoded with constructed encoding"
+ "OID encoded with constructed encoding"
+ "Unexpected return from endpoint!"
+ "^v8@?0"
+ "_Concurrency/Continuation.swift"
+ "bitmap_index < RAM_BITMAP_SLOTS / BITS_PER_UINT64"
+ "is_managed_notification"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8856)"
+ "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2723)"
+ "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2897)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7826)"
+ "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6822)"
+ "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5328)"
+ "tb_list.c"
+ "thread holds resources after return from call"
+ "v20@?0^{tb_connection_s=(?=[97c]^v)}8I16"
+ "v24@?0^{tb_list_node_s=^{tb_list_node_s}Q^v@?}8^B16"
+ "v24@?0^{xrt_thread_info=IQQ{?=QQQ}{?=AIIQQQ}Q}8Q16"
+ "v32@?0Q8^{xrt_thread_info=IQQ{?=QQQ}{?=AIIQQQ}Q}16Q24"
- " but found null instead"
- "(_boot_info.untyped_regions[UNTYPED_MANAGED] .managed_bitmap[bitmap_word] & BIT(bit)) == 0"
- "(_boot_info.untyped_regions[UNTYPED_MANAGED].managed_bitmap[bitmap_word] & BIT(bit)) == 0"
- "DecodingError.typeMismatch: expected value of type "
- "ExclavePlatform runtime error: FrameLevel2 allocation is not supported yet"
- "Managed Phys Base is "
- "[StackshotConclaveSupport] Offline done"
- "[StackshotConclaveSupport] Offline start"
- "[StackshotConclaveSupport] no 0x%lx in text segment info\n"
- "bitmap_word <= RAM_BITMAP_SLOTS / BITS_PER_UINT64"
- "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8855)"
- "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2722)"
- "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2896)"
- "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7825)"
- "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6821)"
- "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5326)"
```
